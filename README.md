#Mask-Rcnn 

##use openCV to display demo instead of matplotlib

fork from https://github.com/matterport/Mask_RCNN

####if python3:

download mask_rcnn_coco.h5 from https://github.com/matterport/Mask_RCNN/releases
* cd Mask-Rcnn-openCV
* git clone https://github.com/waleedka/coco.git
rename coco to coco3
* cd coco3/PythonAPI
* make

* cd ..
* python capture_demo.py

####if python2:

download mask_rcnn_coco.h5 from https://github.com/matterport/Mask_RCNN/releases
* cd Mask-Rcnn-openCV
* git clone https://github.com/waleedka/coco.git
* cd coco/PythonAPI
* make

* cd ..
* 'add “from __future__ import print_function, division” in anywhere error occured'
* python capture_demo.py

----------------
coco and coco3 are same , only make by python2 or python3 which you make.
