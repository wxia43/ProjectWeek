__NOTOC__
<gallery>
Image:SPWW Summer2017.png|link=Main_Page#Projects|[[Main_Page#Projects|Projects List]]
Example.jpg
<!-- Use the "Upload file" link on the left and then add a line to this list like "File:MyAlgorithmScreenshot.png" -->

</gallery>

==Key Investigators==
<!-- Add a bulleted list of investigators and their institutions here -->
* Jordan Dekraker (Robarts Research Institute)
* Jess Rodgers (Robarts Research Institute)

==Project Description==
{| class="wikitable"
! style="text-align: left; width:27%" |   Objective
! style="text-align: left; width:27%" |   Approach and Plan
! style="text-align: left; width:27%" |   Progress and Next Steps
|- style="vertical-align:top;"
|
<!-- Objective bullet points -->
*
|
<!-- Approach and Challenges bullet points -->
* Currently implementation first initializes using volumetric fast marching from source and sink, then weights and combines the two. 
* Next, we use iterative finite-differences approach to obtain better solution settings, by using a 26-neighbour average to compute the updated potential field, and terminating when the potential field change is below a specified  threshold (sum of changes < 0.001%) or a maximum iteration is reached. 
* MATLAB code found at https://github.com/jordandekraker/HippUnfolding.
|
<!-- Progress and Next steps bullet points (fill out at the end of project week) -->
* Completed successfully using Slicer's MATLAB bridge.
* http://github.com/jordandekraker/Slicer_LaplaceSolver
|}

==Background and References==
* Relevant paper for using Laplace in cortical laminar profiles: [http://www.sciencedirect.com/science/article/pii/S1053811913003480 http://www.sciencedirect.com/science/article/pii/S1053811913003480]. 
* The Laplace equation is can be useful for indexing within a volume, and provides a level of smoothness that is suitable for most applications in biology. 
* It is often used to index cortical laminae and streams can be generated across the gradient for determining cortical thickness. 
* In our work we also use it to compute the perpendicular gradients across the hippocampus to index its proximal-distal and longitudinal extents.
