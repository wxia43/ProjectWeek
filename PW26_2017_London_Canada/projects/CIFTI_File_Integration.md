__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
<!-- Use the "Upload file" link on the left and then add a line to this list like "File:MyAlgorithmScreenshot.png" -->
File:Approach.JPG
File:ScalarOverlay.png
</gallery>

==Key Investigators== 
<!-- Add a bulleted list of investigators and their institutions here -->
*'''Hossein Rejali''' (KhanLab, Robarts Research Institute)
*'''Serene Abu-Sardanah''' (KhanLab, Robarts Research Institute)

==Project Description==
{| class="wikitable"
! style="text-align: left; width:20%" |   Objective
! style="text-align: left; width:38%" |   Approach and Plan
! style="text-align: left; width:38%" |   Progress and Next Steps
|- style="vertical-align:top;"
|

<!-- Objective bullet points -->
* Investigate the integration of the CIFTI file format into 3D Slicer. 
|
<!-- Approach and Plan -->
* Build Slicer
* Use Converter's to change to a recognizable (Freesurfer) file type
* Use Python/Matlab to prepare data, if needed
* Modify 3D Slicer Internals if needed.
|
<!-- Progress and Next Steps -->
'''Progress:'''
* Built Slicer
* Converted Model and Scalar Overlay data to Native space recognizable to 3D slicer
* Modified 3D slicer source code to allow (.surf) extension to be recognized as compatible Model file extension
* Use of Matlab to read scalar overlay data and output appropriate data required by user. 
* Able to view surface models and overlay data.
'''Next Steps:'''
* Develop a more viable, and automated approach, currently the method uses freesurfer and HCP work bench command line tools to convert files
* Producing a Module reads and displays the surfaces and Scalar overlay with friendly user environment
* Integrate other CIFTI files 
  

|}

==Background and References==
'''CIFTI Background Information:'''
* http://www.nitrc.org/plugins/mwiki/index.php/cifti:MainPage
* https://mandymejia.wordpress.com/2015/08/10/a-laymans-guide-to-working-with-cifti-files/

'''CIFTI Maltab Reader Source Code:'''
* https://github.com/Washington-University/cifti-matlab
*  https://github.com/mathause/MATLAB

'''Convert Tools:'''
* https://surfer.nmr.mgh.harvard.edu/pub/docs/html/mri_convert.help.xml.html
* http://www.humanconnectome.org/software/connectome-workbench
