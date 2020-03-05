# Pothole Detection System (image or video)
##               by The_Newcomers
### Read ppt for overview

For Pre Trained wts : - https://drive.google.com/open?id=1bqqA49WElVIsNqJnU61R7XKipD_NpzVj

Run `pip install -r requirements.txt` in the pothole detection folder. Then for tensorflow: -

For local running use: - tensorflow-gpu==1.15 , CUDA V 10.0 , cuDNN V 7.6.5  ( https://www.tensorflow.org/install/gpu#software_requirements )
(tip use a new virtual env using pycharm or something and select basic interpreter as conda python 3.6 and then install everything.)

For Google Colabs (easier to run) just use : - tensorflow-gpu==1.14

#### To run: - 
```
python predict.py -c config.json -w /path/of/trained_wts.h5 -i /path/of/image(jpg or png)/or/video(mp4)
```

### Example
![Road with potholes](potholes_detection/images/pothole2.png?raw=true "Road with Potholes")
### Detected potholes: -
![Road with potholes detected](potholes_detection/images/pothole2_detected.png?raw=true "Road with Potholes")

#### Note: - The front end(django) is yet to be connected to the backend.
