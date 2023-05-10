# Basketball Ball Detector

Link to YOLO 8: https://github.com/ultralytics/ultralytics

Code to train model : yolo task=detect mode=train epochs=100 data=data.yaml model=yolov8m   

Code to run model on webcam : yolo task=detect mode=predict model=best.pt show=true conf=0.5 source=0

Code to run model on image: yolo task=detect mode=predict model=best.pt show=true conf=0.5 source=(IMAGE_PATH)
