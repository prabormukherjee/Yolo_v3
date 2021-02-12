# Yolo_v3

This is the repo where I have modified the famous Yolo v3 algorithm. Here I have implemented the feature to run the video and save them with label. Here the the guide to use this    
`How to use`:
+ fork the repo first
+ take a look at the folder structure,
+ move all the files into the darknet folder (this is important to run the codes)
+ now open a terminal in the darknet folder 
+ to run the default model: `darknet detector demo cfg/coco.data cfg/yolov3-tiny.cfg yolov3-tiny.weights Driving-Chinatown-SF.mp4`
+ to run the modified version: `python3 yolo.py -w=yolov3-tiny.weights cfg=cfg/yolov3-tiny.cfg -v=MArket\ Street.mp4 -l=data/coco.names`    

After tis hopefully it will run the code, with the saved label. The parameter used in the yolo.py is self-explanatory   
If you have isssues like weights not found, please make sure to dowmloads the weights also, as I weight is not present in this repo.
Also you can checkout their original site here <a href='https://pjreddie.com/darknet/yolo/'>YOLO</a>     
See their original repo here <a href='https://github.com/pjreddie/darknet'>Github</a>
