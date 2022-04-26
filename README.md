# Graph_Cut_Images

This Implemnetation follows Compositing along the minimum seam between two images ([Kwatra, et al.] (https://www.csee.umbc.edu/~adamb/641/resources/GraphcutTextures.pdf); [Website] (https://www.cc.gatech.edu/cpl/projects/graphcuttextures/)).

My Program works for 3*3 patches with variable patch length

The Implmentation is in Python

I used the follwing modules with latest versions -- 

import math
from skimage import io, util
import heapq
import matplotlib.pyplot as plt
import json
from cmath import inf
from turtle import pd
from unittest.mock import patch
import numpy as np
import os
