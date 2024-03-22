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
