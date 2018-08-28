# potholes-detection
This is a deep learning model for detecting the potholes on roads. The model is using YOLO-v2. 

Download the weights from this link : https://drive.google.com/open?id=1VwViHDdc4W8t28rMiuGjxChiAtFxMAjN
and place the weights in the root folder. 

Then
`python predict.py -c config.json -w /path/to/best_weights.h5 -i /path/to/image/or/video`

## Image

![Road with potholes](images/1.jpg?raw=true "Road with Potholes")

## Detected potholes
![Road with potholes detected](images/1_detected.jpg?raw=true "Road with Potholes Detected")
