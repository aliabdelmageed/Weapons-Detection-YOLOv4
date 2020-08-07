# Weapons-Detection-YOLOv4
I trained YOLOv4 model using darknet framework to detect weapons in images and videos.

I got the data from open images, I used 3 classes Handgun, Shotgun and Weapon, then I combined them together as single class "Weapon", So I had 1425 images for training and 285 images for validation.

I trained the model for 4000 epochs and got mAP about 65% with threshold=0.5

# tensorflow-YOLOv4
YOLOv4 Implemented in Tensorflow 2.0.

I Converted yolov4-custom.weights to format for tensorflow.

Download yolov4-custom.weights file: https://drive.google.com/file/d/1-bPteE8rV9ObeX4l28A5XWMQjWWtWsBG/view?usp=sharing
