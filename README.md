## Dataset (TuSimple)
Pre-trained model is "804_tensor(0.5786)_lane_detection_network.pkl"

## Dataset (CurveLanes)
You can download the dataset from https://github.com/xbjxh/CurveLanes.
Pre-trained model is "savefile/32_tensor(1.1001)_lane_detection_network.pkl"

### Parse Curvelanes
Here are several scripts for parsing and converting datasets to TuSimple style.https://github.com/pandamax/Parse_Curvelanes

## ONNX Inference
- onnx_converter.py: convert trained model into onnx.
- onnx_inference.py: use onnxruntime to run converted onnx model's inference.
