# Hotdog or Not
The repo is a sample for deep-learning model training based on the "Hotdog Or Not" classification task (inspired by the "Silicone Valley" series).

The sample shows how to train a model with PyTorch and convert it to both ONNX and CoreML formats.

## Training code
The training code can be found in the "main.ipynb" Jupiter Notebook. 

## Datasets
Train: https://www.dropbox.com/s/cupinvuotopehty/train.zip?dl=0

Test: https://www.dropbox.com/s/7xakfl2r9gn5p1j/test.zip?dl=0

## Output
The output is a trained model in the following formats (see the source code for reference):
* PyTorch - my_mobilenet_v2.pth
* ONNX - mobilenet_v2-2.onnx
* CoreML - coreml_output-2.mlmodel
