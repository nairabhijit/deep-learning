# deep-learning

Download the RCNN model file from the URL - http://download.tensorflow.org/models/object_detection/tf2/20200711/faster_rcnn_resnet50_v1_640x640_coco17_tpu-8.tar.gz
File path - faster_rcnn_resnet50_v1_640x640_coco17_tpu-8/saved_model/

**RCNN classes**
```python
{1: '"person"',
 2: '"bicycle"',
 3: '"car"',
 4: '"motorcycle"',
 5: '"airplane"',
 6: '"bus"',
 7: '"train"',
 8: '"truck"',
 9: '"boat"',
 10: '"traffic light"',
 11: '"fire hydrant"',
 13: '"stop sign"',
 14: '"parking meter"',
 15: '"bench"',
 16: '"bird"',
 17: '"cat"',
 18: '"dog"',
 19: '"horse"',
 20: '"sheep"',
 21: '"cow"',
 22: '"elephant"',
 23: '"bear"',
 24: '"zebra"',
 25: '"giraffe"',
 27: '"backpack"',
 28: '"umbrella"',
 31: '"handbag"',
 32: '"tie"',
 33: '"suitcase"',
 34: '"frisbee"',
 35: '"skis"',
 36: '"snowboard"',
 37: '"sports ball"',
 38: '"kite"',
 39: '"baseball bat"',
 40: '"baseball glove"',
 41: '"skateboard"',
 42: '"surfboard"',
 43: '"tennis racket"',
 44: '"bottle"',
 46: '"wine glass"',
 47: '"cup"',
 48: '"fork"',
 49: '"knife"',
 50: '"spoon"',
 51: '"bowl"',
 52: '"banana"',
 53: '"apple"',
 54: '"sandwich"',
 55: '"orange"',
 56: '"broccoli"',
 57: '"carrot"',
 58: '"hot dog"',
 59: '"pizza"',
 60: '"donut"',
 61: '"cake"',
 62: '"chair"',
 63: '"couch"',
 64: '"potted plant"',
 65: '"bed"',
 67: '"dining table"',
 70: '"toilet"',
 72: '"tv"',
 73: '"laptop"',
 74: '"mouse"',
 75: '"remote"',
 76: '"keyboard"',
 77: '"cell phone"',
 78: '"microwave"',
 79: '"oven"',
 80: '"toaster"',
 81: '"sink"',
 82: '"refrigerator"',
 84: '"book"',
 85: '"clock"',
 86: '"vase"',
 87: '"scissors"',
 88: '"teddy bear"',
 89: '"hair drier"',
 90: '"toothbrush"'}
```
**Extract file**
```sh
!tar xzvf pretrained-model.tar.gz
```

**CIFAR 10 classes**
```python
["airplane","automobile","bird","cat","deer","dog","frog","horse","ship","truck"]
```

**Mobile-Net classes**
```python
['person', 'bicycle', 'car', 'motorbike', 'aeroplane', 'bus', 'train', 'truck', 'boat', 'traffic light', 'fire hydrant', 'stop sign', 'parking meter', 'bench', 'bird', 'cat', 'dog', 'horse', 'sheep', 'cow', 'elephant', 'bear', 'zebra', 'giraffe', 'backpack', 'umbrella', 'handbag', 'tie', 'suitcase', 'frisbee', 'skis', 'snowboard', 'sports ball', 'kite', 'baseball bat', 'baseball glove', 'skateboard', 'surfboard', 'tennis racket', 'bottle', 'wine glass', 'cup', 'fork', 'knife', 'spoon', 'bowl', 'banana', 'apple', 'sandwich', 'orange', 'broccoli', 'carrot', 'hot dog', 'pizza', 'donut', 'cake', 'chair', 'sofa', 'pottedplant', 'bed', 'diningtable', 'toilet', 'tvmonitor', 'laptop', 'mouse', 'remote', 'keyboard', 'cell phone', 'microwave', 'oven', 'toaster', 'sink', 'refrigerator', 'book', 'clock', 'vase', 'scissors', 'teddy bear', 'hair drier', 'toothbrush']
```
**Mobile-Net pretrained model weights download link**
[https://github.com/opencv/opencv/wiki/TensorFlow-Object-Detection-API](http://download.tensorflow.org/models/object_detection/ssd_mobilenet_v3_large_coco_2020_01_14.tar.gz)
File path - 
config_file = 'ssd_mobilenet_v3_large_coco_2020_01_14/ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt'
frozen_model = 'ssd_mobilenet_v3_large_coco_2020_01_14/frozen_inference_graph.pb'
