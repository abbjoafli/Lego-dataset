# Lego-dataset
Lego dataset for training a yolo weight either with keras or with darknet.
The .txt files in /annotations are used by darknet and the .xml files in /annotations_xml is used by keras training.

## Testing in yolo (and using)
### testimages
A folder where testimages is saved which can be uses for testing.

### yolo-legogubbe
This folder contains .cfg (config) file and different weights for testing result in opencv. The different weights are from different times in the training

- yolo.weights = yolo9000.weights
- yolo10000.weights = yolo10000.weights
- yolo2.weights = yolo6000.weights
- yolo3.weights = yolo7000.weights
- yolo4.weights = yolo8000.weights
