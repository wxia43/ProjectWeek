__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
Image:OriginalSurface.png
Image:SmoothedSurface.png
<!-- Use the "Upload file" link on the left and then add a line to this list like "File:MyAlgorithmScreenshot.png" -->

</gallery>

==Key Investigators==
<!-- Add a bulleted list of investigators and their institutions here -->
* Michael Hardisty

==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
* Deploy Deep Learning Networks in Slicer for the purpose of segmenting vertebral bodies and object recognition
|
<!-- Approach and Plan bullet points -->
* Investigate different approaches for need specific deployment of deep learning networks.
** DeepInfer
** TensorFlow
*** CPP API
*** tfdeploy via pure python
** ROS
* Implement a method for deployment of deep learning methods
|
<!-- Progress and Next steps bullet points (fill out at the end of project week) -->
* Investigated a number of modules that use deep learning on the advice of Andras
* It appears that cross-platform deployment of deep learning networks implemented in tensor flow can be deployable using the methods similar to the ShapeVariationAnalyser
** https://github.com/pdedumast/ShapeVariationAnalyzer
** Specifically they have exposed some deep learning functionality within the logic.  It can be accessed from Slicer using the following python commands:
<pre>Python 2.7.13 (default, Jul 18 2017, 23:29:12) [MSC v.1800 64 bit (AMD64)] on win32
>>> shapeVariationAnalyzerLogic = slicer.modules.shapevariationanalyzer.logic()
>>> import ShapeVariationAnalyzer
>>> shapeVariationAnalyzerLogicCast = ShapeVariationAnalyzer.ShapeVariationAnalyzerLogic( shapeVariationAnalyzerLogic)
>>> shapeVariationAnalyzerLogicCast.trainNetworkClassification()
</pre>
* I will need the ability to load pre-trained networks, which may be exposed but I cannot tell at this time.
* I spent some time learning how to SuperBuild Modules in an effort to enhance the ease with which these and other modules I develop can be maintained and deployed.  I focused on a simpler example.  My superbuild extension is a wrapping of VCG functionality into Slicer.  VCG is used to enhance surface quality. It underlies much functionality in slicer.
** https://github.com/cnr-isti-vclab/vcglib
|}
