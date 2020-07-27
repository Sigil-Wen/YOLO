# How to run YOLO
Object Detection with YOLO (You Only Look Once). To run YOLO, first download the pretrained weights in the linked google drive (237 MB) and move the weights to the folder "yolo-coco".
https://drive.google.com/file/d/1sbrSFwp4lAgVVDKijGf7hlIzcDbu7Eu_/view?usp=sharing
### Within command prompt, to run YOLO on an image use: 
```
$ python yolo.py --image "IMAGE PATH" --yolo yolo-coco
```
### For videos, use: 
```
$ python yolo_video.py --input "VIDEO PATH" --output "OUTPUT PATH" --yolo yolo-coco
```
Read my article on yolo: https://medium.com/@sigilwen/object-detection-with-yolo-bringing-vision-to-self-driving-cars-980295226830
#### Watch my Video Demo of YOLO(VSauce Parody):https://www.youtube.com/watch?v=AxhBu2uK86I 

Code adopted from PyImageSearch 
