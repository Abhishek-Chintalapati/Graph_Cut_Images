# Graph_Cut_Images

This Implemnetation follows Compositing along the minimum seam between two images ([Kwatra, et al.] (https://www.csee.umbc.edu/~adamb/641/resources/GraphcutTextures.pdf); [Website] (https://www.cc.gatech.edu/cpl/projects/graphcuttextures/)).

The Implmentation is in Python

My Program works for 3*3 patches with variable patch length

The Adjacency Matrices are written to a file in the same working directory as Adj_matrice_file1, Adj_matrice_file2.......
since I designed for 3*3 patches there would be 12 matrices files generated(including vertical, horizontal overlap regions)   

My Function call is --  quilt(texture, 20, (3, 3), "cut", True)
Texture -- Image
20 -- Patch Length
(3,3) -- patches in each row, column 
cut -- Enable cut 
True -- If you need sequential output at every phase 

I used the follwing modules with latest versions -- 

import math <br />
from skimage import io, util <br />
import heapq <br />
import matplotlib.pyplot as plt <br />
import json <br />
from cmath import inf <br />
from turtle import pd <br />
from unittest.mock import patch <br />
import numpy as np <br />
import os
