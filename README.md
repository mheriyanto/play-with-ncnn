# play-with-ncnn
Repository for playing the computer vision apps: **Face analytics** using ncnn on Raspberry Pi

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
