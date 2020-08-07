## Contents

For detect videos FPS and Latency, in diff GPUs:
GPU1070, GPU1080Ti, Tesla T4 ... 
```bash
$ python detect.py --cfg /home/aiden00/abwu_workspace/yolov4/yolov4.cfg --weights /home/aiden00/abwu_workspace/yolov4/yolov4.weights --source /home/aiden00/abwu_workspace/yolov4/test4.mp4 --img-size 608

$ python detect.py --cfg cfg/yolov3.cfg --weights /home/aiden00/abwu_workspace/yolov4/yolov3.weights --source /home/aiden00/abwu_workspace/yolov4/test4.mp4 --img-size 608

$ python detect.py --cfg /home/aiden00/abwu_workspace/yolov4/yolov4.cfg --weights /home/aiden00/abwu_workspace/yolov4/yolov4.weights --source /home/aiden00/abwu_workspace/yolov4/dog.jpg --img-size 608

$ python detect.py --cfg cfg/yolov3.cfg --weights /home/aiden00/abwu_workspace/yolov4/yolov3.weights --source /home/aiden00/abwu_workspace/yolov4/dog.jpg --img-size 608
```
