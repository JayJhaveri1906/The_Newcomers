# Pothole Detection System (image or video)
##               by The_Newcomers
### Read ppt for overview

For Pre Trained wts : - https://drive.google.com/open?id=1bqqA49WElVIsNqJnU61R7XKipD_NpzVj

For local running use: - tensorflow-gpu==1.15 , CUDA V 10.0 , cuDNN V 7.6.5  ( https://www.tensorflow.org/install/gpu#software_requirements )
(tip use a new virtual env using pycharm or something and select basic interpreter as conda python 3.6)

For Google Colabs (easier to run) just use : - tensorflow-gpu==1.14

#### To run: - 
```
python predict.py -c config.json -w /path/of/trained_wts.h5 -i /path/of/image(jpg or png)/or/video(mp4)
```

### Example
![Road with potholes](images/1.jpg?raw=true "Road with Potholes")
### Detected potholes: -
![Road with potholes](images/1_detected.jpg?raw=true "Road with Potholes")
