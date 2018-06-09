==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
* detect the uterus of MRI DICOM images in 3D slicer. Images are sent from MATLAB and returned to MATLAB.
|
<!-- Approach and Plan bullet points -->
* autosegment the images in 3D slicer using a manual seed point
* send images (and seed point) from a GUI in Matlab
* write script so 3D slicer does this without any manual interaction
* send mask of uterus back to Matlab

|
* used slicer to implement semi-automatic tools to segment the uterus
* created a bridge to and from MATLAB

|}
