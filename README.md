# trafficCar_ssd
python predict_video.py --model weights/frozen_inference_graph_car_front_rear.pb --labels classes.pbtxt --input input/carTraffic.mp4 --output output/output.avi --num-classes 2

**It is necessary to create a symbolic link from the object_detection folder in the tensorflow library**

https://cutt.ly/Zy40fW1

![Alt text](readme/carTraffic.png?raw=true "Title")
