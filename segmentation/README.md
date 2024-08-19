# KRoad
2024년 7월 26일 ~ 2024년 8월 19일

[![KRoad AI competition](/pngs/banner.jpg)](https://challenge.gcontest.co.kr/template/m/16335)


## Content
1. [Data Preprocessing](#Data-Preprocessing)
2. [Model Selection](#Model-Selection)
3. [Result](#Result)

## Data Preprocessing

## Model Selection
UperNet + InternImage-B pretrained with Cityscapes

## Result
### UperNet + InternImage

| backbone       | resolution |  mIoU | #params | FLOPs |
|:--------------:|:----------:|:------------:|:-----------:|:----------:|:-------:|:-----:|:----:|:----:|
| InternImage-B  | 512x1024   |   82.09   |     128M     | 1889G |


## Reference
* https://github.com/OpenGVLab/InternImage
* https://github.com/open-mmlab/mmsegmentation
