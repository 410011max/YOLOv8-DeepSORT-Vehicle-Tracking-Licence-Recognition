## Steps to run Code

- Install the dependecies
```
pip install -e '.[dev]'
```
- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```
- Put your video or image into `ultralytics\yolo\v8\detect\demo`
- Run YOLOv8 Vehicle Tracking & Counting
```
python predict.py model=yolov8x.pt imgsz=1280 conf=0.8 source=demo/test.mp4
```

### Result

#### Vehicles Detection, Tracking and Counting 
![](./figure/figure1.png)
