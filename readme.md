You will need to download:

1. a pre-trained tensorflow model which performs object detection on MSCOCO objects
2. the associated 90-class text labels from the MSCOCO object dataset

For instance, to download the following model:

     ssdlite_mobilenet_v2_coco_2018_05_09

use wget to fetch the model:

     $ wget http://download.tensorflow.org/models/object_detection/ssdlite_mobilenet_v2_coco_2018_05_09.tar.gz
     $ tar -xzvf ssdlite_mobilenet_v2_coco_2018_05_09.tar.gz

and the label file:

     $ wget https://raw.githubusercontent.com/tensorflow/models/master/research/object_detection/data/mscoco_label_map.pbtxt

Note that other models with different speed/accuracy tradeoffs are available!
If interested, consult the Detection Model Zoo for other pre-trained models:
https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/detection_model_zoo.md