# SP-CNN-and-Random-forest-for-LSAs-3D-reconstruction
A framework based on small-patch CNN and random forest was tested for automated modeling of 7T time-of-flight MR angiography acquired lenticulostriate artery (LSA). This method reveals LSA structural changes in cerebral small vessel disease patients. 

rf.ipynb used to train random forest
spcnn.ipynb used to train SP-CNN

if you want to give raw data and get a 3D model and parameters, please first run preprocessing.ipynb, second run seg_standard.ipynb, third run track_standard.ipynb.

You need to install tensorflow>=2.0.

The example file can be download from https://drive.google.com/file/d/1n9ruDIJ09Z1771RbsNQ0Y9_ytq1lsrug/view?usp=drive_link. There is an example nii file for test.
