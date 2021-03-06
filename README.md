# Run Model to Detect Facemask and Recognition
Data for Facemask Detection: [here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblA1VTlQY3JUMkM3NFF4LXlNejhGb2dmRnNKZ3xBQ3Jtc0tsY1ZXTzdEMFVqS21lWXBZNHJQdEJKUWtFdlRWZWhNU0Y2d3EyYnNXb0lvdXVvaENtbV9iRF9uWUZVYklPaVRYUTF2V21xcHZHX3pObThwY1VVZXA2NExxSkRTYl95dHhJZzk5dTltcDNxUlI3Q1p2QQ&q=https%3A%2F%2Fwww.kaggle.com%2Fdeepakat002%2Fface-mask-detection-yolov5)
## Train Yolov5 Detect_FaceMask: 
Google Colab: [here](https://colab.research.google.com/drive/1I7EoMdjxB0cn4pb7NjmyQK0YqXL7MGqc?usp=sharing)
Data for Train on Colab: [here](https://drive.google.com/drive/folders/1xllrPRw1Kg1kxbx4dmBMNSahn97G_ZV9?usp=sharing)
## Performance
|Data|LFW Dataset  |
|--|--|
| Accuracy |~88.05%  |

If you want to Test on LFW on Dataset please go to folder path:`test_performance_on_LFW`


## Prepare Data: 
Save all video about face user video follow this path: `"./video"`
Run command to preprocess data: `python preprocess_video.py`

## Train data for Face Recognite:
Run command: `python train_recognite_face.py`
If you want to check the Accurancy of your Dataset please run with command: `python test_dataset.py` 

## Deploy Model
Run `python detect.py`

### Note:
All Dataset when you run my command  are splitted with scale 80/20

## References
1. Timesler's facenet repo:  [here](https://github.com/timesler/facenet-pytorch)
2. Yolov5_Facemask [here](https://github.com/deepakat002/yolov5_facemask)
3.  Yolov5 [here](https://github.com/ultralytics/yolov5)
