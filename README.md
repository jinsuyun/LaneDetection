## Dataset (TuSimple)
Pre-trained model is "804_tensor(0.5786)_lane_detection_network.pkl"

parameters.py
line 54 : train_root_url="<tuSimple_dataset_path>/train_set/"
line 55 : test_root_url="<tuSimple_dataset_path>/test_set/"

## Test
mode 0 : Visualize results on test set
mode 1 : Run the model on the given video. If you want to use this mode, enter your video path at line 63 in "test.py"
mode 2 : Run the model on the given image. If you want to use this mode, enter your image path at line 82 in "test.py"
mode 3 : Test the model on whole test set, and save result as json file.

## Result
TuSimple
Accuracy: 0.96, FP: 0.03, FN: 0.02

## 실행
python test.py -i /input image directory
