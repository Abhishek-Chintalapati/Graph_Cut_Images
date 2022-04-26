# Graph_Cut_Images

This Implemnetation follows Compositing along the minimum seam between two images [Kwatra, et al.] https://www.csee.umbc.edu/~adamb/641/resources/GraphcutTextures.pdf <br /> https://www.cc.gatech.edu/cpl/projects/graphcuttextures/.

The Implmentation is in Python <br />

My Program works for 3*3 patches with variable patch length <br />

The Adjacency Matrices are written to a file in the same working directory as Adj_matrice_file1, Adj_matrice_file2....... <br />
since I designed for 3*3 patches there would be 12 matrices files generated(including vertical, horizontal overlap regions)   

My Function call is --  quilt(texture, 20, (3, 3), "cut", True) <br />
Texture -- Image <br />
20 -- Patch Length <br />
(3,3) -- patches in each row, column <br />
cut -- Enable cut <br />
True -- If you need sequential output at every phase <br /> 

I used the follwing modules with latest versions -- <br />

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
