__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
Image:Htcvivepic.png
</gallery>

==Key Investigators==
* Adam Rankin (Robarts Research Institute)
* Andras Lasso (Queen's University)
* Isabella Morgan (Robarts Research Institute/University of Waterloo)
* Uditha Jayarathne (Robarts Research Institute)
* Franklin King (Brigham and Women's Hospital)

==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
* Extend CTK with OpenVR specific view classes
** See [http://www.commontk.org/docs/html/classctkVTKAbstractView.html ctkVTKAbstractView], [http://www.commontk.org/docs/html/classctkVTKRenderView.html ctkVTKRenderView]
* Extend Slicer with new CTK subclasses
** See [http://apidocs.slicer.org/master/classqMRMLThreeDWidget.html qMRMLThreeDWidget.html], [http://apidocs.slicer.org/master/classqMRMLThreeDView.html qMRMLThreeDView], [http://apidocs.slicer.org/master/classqMRMLLayoutManager.html qMRMLLayoutManager]
|
<!-- Approach and Plan bullet points -->
* Add subclass to ctkVTKAbstractView/ctkVTKRenderView that uses a vtkOpenVRRenderer/vtkOpenVRRenderWindow as base
** Possible factory intelligent building?
* Add new classes in Slicer for VR view, add entry in layout manager for new view type
|
<!-- Progress and Next steps bullet points (fill out at the end of project week) -->
*
|}

==Background and References==
<!-- Use this space for information that may help people better understand your project, like links to papers, source code, or data -->
