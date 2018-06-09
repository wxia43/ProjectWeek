__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
<!-- Use the "Upload file" link on the left and then add a line to this list like "File:MyAlgorithmScreenshot.png" -->

</gallery>

==Key Investigators==
<!--  -->
* Colin McCurdy, Mohamed Moselhy

==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
* Load DICOM imageset from python script
* Segment phantom volume and important locations on phantom from background
* analyze the full datasets and return simple statistics on the phantom
|
<!-- Approach and Challenges bullet points -->
* No simple loadDicom function, need to convert DICOM volumes into NRRD
* Segmentation isn't perfect, needed to grow the background to cut out some of the noise surrounding the phantom
* Needed to further automation so that the analysis works on all of my imagesets
|
<!-- Progress and Next steps bullet points (fill out at the end of project week) -->
* Auto segmentation working on two imagesets
* Built code (with help) to convert DICOM volume to NRRD and load into slicer
* Setup basic format of analysis code

* Next Steps:
* clean up code
* Finalize analysis
* further generalize segmentation portion to ensure it works for all of my imagesets
|}

==Background and References==
<!-- I have a large set of images that I need to analyze so I created a pipeline to run through the imagesets and produce simple quantitative values -->
