# GRAD_CAM_Aircraft_detection

# Libraries 
Create conda environment: conda create –n y7 python=3.9
`
import colorsys, os, cv2, numpy as np
`
`
import torch
`
`
import torch.backends.cudnn as cudnn
`
`
import torch.nn as nn
`
`
from PIL import Image, ImageDraw, ImageFont
`
`
from torch.autograd import Variable
`

Make dataset_class.txt file, where objects class names, and anchor.txt, using same anchor of YOLOv4-Darknet repository 
we have. Yolov4.cfg file of darknet and parsing the Yolov4.cfg, by run config.py. All the dataset are stored Full_DATASET folder. 
Run the conversion.py to generate DATA.txt file, where we have all images path, their bounding box values and class id.
