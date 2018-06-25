## Finetuning

```
# transfer learning
__C.TRANSFER = True
__C.TRANSFER_SELECT = 'POSITIVE'
__C.TRANSFER_WEIGHT = 1
```

## Data Preparation

Put your source data into Pascal Foramtted folder with folder name VOC2007 and link with data/VOCdevkit2007, put your target data into VOC2012 and link data/VOCdevkit2012 and follow the VOC_0712 training from [py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn)