# ModelMorphis
Model Morphis

## Project Details: Visualize an ML or Deep Learning Model ##
- Transform models from one type to another
- Create a model testing framework so any model can be tested directly
- Create and package the model scoring pipeline as pkl package which can run on any environment
- Display Model Metrics
- Compare two models with same origin
- Model Runtime performance comparision among various runtimes
- (Let's Talk)

## Supported Model Types ##

|Model Types   | Supported extensions   | Visualization  | Transformation Count | 
|---|---|---|---| 
|ONNX   | .onnx, .pb, .pbtxt  |   |    |
|Keras   | .h5, .keras  |   |   |
|TensorFlow Lite    |.tflite   |   |   |
|TensorFlow.js   |model.json, .pb   |   |   |
|TensorFlow   |.pb, .meta, .pbtxt   |   |   |
|PyTorch   | .pt, .pth  |   |   |
|Torch   |.t7   |   |   |
|CoreML   | .mlmodel  |   |   |
|Caffe    | .caffemodel, .prototxt  |   |   |
|Caffe2   |predict_net.pb, predict_net.pbtxt   |   |   |
|MXNet  | .model, -symbol.json  |   |   |
|TorchScript   |.pt, .pth   |   |   |
|NCNN   | .param  |   |   |
|CNTK   | .model, .cntk  |   |   |
|Deeplearning4j   |.zip   |   |   |
|PaddlePaddle   |.zip, __model__   |   |   |
|Darknet   |.cfg   |   |   |
|scikit-learn   | .pkl  |   |   |
|H2O.ai    |MOJO Models .zip   |   |   |
|Spark Mlib & PySpark  | .ml  |   |   |

## Supported Runtime ##
|Runtime/Library|Version|Tested|Verified| 
|---|---|---|---| 
|Python|3.7|  |  | 
|TensorFlow| |  |  | 
|TensorFlow-gpu|  |  |  | 

## Model Transformation Status ##

|Model|ONNX|Keras|TensorFlow Lite|TensorFlow.js|TensorFlow|PyTorch|Torch|CoreML|Caffe|Caffe2|MXNet|TorchScript|NCNN|CNTK|Deeplearning4j|PaddlePaddle|Darknet|scikit-learn|H2O.ai|Spark Mlib & PySpark|
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---| 
|ONNX|   X |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|Keras|    | X  |   |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|TensorFlow Lite |  |  | X  |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|TensorFlow.js|  |   |   |  X |  |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|TensorFlow|    |   |   |    |   X |    |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|PyTorch|     |   |   |    |    |  X  |    |    |    |    |    |    |    |    |    |    |    |    |    |    |
|Torch|    |   |   |    |    |    | X   |    |    |    |    |    |    |    |    |    |    |    |    |    |
|CoreML|  |   |   |    |    |    |    |  X  |    |    |    |    |    |    |    |    |    |    |    |    |
|Caffe|  |   |   |    |    |    |    |    |  X  |    |    |    |    |    |    |    |    |    |    |    |
|Caffe2|   |   |   |    |    |    |    |    |  |  X  |    |    |    |    |    |    |    |    |    |    |
|MXNet|   |   |   |    |    |    |    |    |  |  |  X  |    |    |    |    |    |    |    |    |    |
|TorchScript|   |  |   |   |   |   |   |   |    |  |  | X  |    |    |    |    |    |    |    |    |
|NCNN|  |   |   |    |    |    |    |    |    |    |  |   | X |   |    |    |    |    |    |    |
|CNTK|  |   |   |    |    |    |    |    |    |    |    |  |   |  X |   |    |    |    |    |    |
|Deeplearning4j|  |   | |  |   | |  | |    |    |    |    |    |    |  X  |    |    |    |    |    |
|PaddlePaddle|  |   |   |    |   |  |  |  |  |  |  |    |    |    |    |  X |    |    |    |    |
|Darknet|   |   |   |    |    |    |    |    |   |  |  |    |  |   |  |    |  X  |    |    |    |
|scikit-learn| |   |   |  |  |    |  |  |  |    |    |    |    |    |  |  |    |  X  |    |    |
|H2O.ai|   |   |   |    |    |  |  |    |    |  |    |  |    |  |    |   |    |    | X   |    |
|Spark Mlib & PySpark|  |   |   |  |  |  |  |  |    |  |  |  |  |  |  |  |  |  |    |  X  |


## Current Progress: ##
- I have completed the model transformation engine one type to another supporting 90% of above-listed models
- Some model types are already integrated with model visualization framework (about 20% completed)
- The base of the Model Visualization framework is ready however more work needed to support various model types
- Current code run at the command-line with very basic flask based web code enabled
- I do have a full project development plan ready with weekly sprints which will be followed with the team.

Note: If you are interested in contributing to the project please make sure you can meet the following requirement:
- Self-motivated and can commit about 6 hours minimum on a daily basis to code
- Have some experience as machine learning engineer and full-stack development with expertise into python and react

