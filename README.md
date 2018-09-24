# PyTorch-Image-Dehazing
PyTorch implementation of some single image dehazing networks. 

Currently Implemented:
AOD-Net

**Prerequisites:**
1. Python 3 
2. Pytorch 0.4

**Preparation:**
1. Create folder "data".
2. Download and extract the dataset into "data" from the original author's project page. (https://sites.google.com/site/boyilics/website-builder/project-page). 

**Training:**
1. Run train.py. The script will automatically dump some validation results into the "samples" folder after every epoch.

**Testing:**
1. Run dehaze.py. The script takes images in the "test_images" folder and dumps the dehazed images into the "results" folder.

**Evaluation:**
WIP.  
Some qualitative results are shown below:

![Alt text](results/test.png?raw=true "Title")  
![Alt text](results/test7.jpg?raw=true "Title")  
![Alt text](results/test4.jpg?raw=true "Title")  
![Alt text](results/test9.jpg?raw=true "Title")  
![Alt text](results/test13.jpg?raw=true "Title")  
![Alt text](results/test15.jpg?raw=true "Title")
