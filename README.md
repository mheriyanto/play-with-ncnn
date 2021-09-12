# play-with-ncnn
Repository for playing the computer vision apps using ncnn on Raspberry Pi. Tech stack: Python, Docker &amp; ncnn. Source C++: https://gitlab.com/mheriyanto/play-with-ncnn-dev 

## Install library

```console
$ pip3 install -r docker/requirements.txt
```
## Run demo

```console
$ git clone https://github.com/mheriyanto/play-with-ncnn.git
$ cd play-with-ncnn
$ python3 inference.py --backend ncnn --img_fold samples
```

## References
+ NanoDet: Super fast and lightweight anchor-free object detection model. [here](https://github.com/RangiLyu/nanodet)