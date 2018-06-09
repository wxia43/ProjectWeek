__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
<!-- Use the "Upload file" link on the left and then add a line to this list like "File:MyAlgorithmScreenshot.png" -->
File:DataProbe_wVolume.png
File:DataProbe_noVolume.png
</gallery>

==Key Investigators==
<!-- Add a bulleted list of investigators and their institutions here -->
* Jason Kai (Robarts Research Institute)
* Saeed Bakhshmand (CSTAR)
* Hossein Rejali (Robarts Research Institute)
* Brian Wang (KhanLab)
* Serene Abu-Sardanah (Robarts Research Institute)

==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
* Create a data probe to be used in the 3D viewer to be able to report position and extract information.
|
<!-- Approach and Plan bullet points -->
* Use the cursor to determine position in 3D space
* Report position to user and extract corresponding information at that location
* Make use of existing Slicer libraries via Python to implement
|
<!-- Progress and Next steps bullet points (fill out at the end of project week) -->
* Cursor returns 2 out of 3 positions, switched to the crosshair which can return RAS position 
* RAS position returned via CrosshairNode in upper left corner of the 3D viewer using vtkCornerAnnotation
* Used RAS position to extract information from background layer in slice views '''only if''' volume is available. This is value is returned in upper right corner of the 3D viewer
* Able to pull information from background layer via Editor library of Slicer (there may be a more direct way of doing this)

Next steps:
* Extract information directly from vtkPolyData if available
* Report back values in a widget instead of within viewer 
|}

==Background and References==
<!-- Use this space for information that may help people better understand your project, like links to papers, source code, or data -->
Source code: [http://github.com/kaitj/dataprobe3d DataProbe3D]
