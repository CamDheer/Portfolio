# Portfolio

The "OCT" zip file contains my final year dissertation. This was a final year project which was A Quantitative Analysis 
of Image Segmentation techniques/algorithms using OCT Retinal images in the Search of highest accuracy to support the field of Ophthalmology.
The project aims to take OCT images and segment them using different segmentation algorithms to identify different key aspects of the retina within OCT scans as this is currently a tedious process for clinicians. For each OCT scan there is a corresponding ground truth which has been annotated by a clinical expert. Once the image has been segmented by different algorithms within my code a dice score is produced which shows the similarity between a segmented image and the ground truth image. The higher the dice score the closer the segmentation is to the one of the clinical expert thus being a better segmentation. This score is then shown as an excel file.

The folder called "Manual-Segmentation" contains all of the jpeg images which are raw OCT scans and corresponding files which have the same name but have a ".MAT" extension these are the corresponding ground truths.

All of the data used was provided for by School of Optometry and Vision Science and Copyright(c) 2018 Theoretical & Experimental Epistemology Lab (TEEL), School of Optometry and Vision Science, University of Waterloo, 200 University Ave. West Waterloo, ON, Canada N2L 3G1. All rights reserved.

Once the code has been executed new folders which contains the name of the segmentation techniques used such as "canny edge" are generated and the canny edge version of the OCT scan is saved within the file. This is done for each segmentation technique.

The excel file displays the dice score of each OCT segmented OCT scan when compared with the ground truth and generates an average ground truth score which is used to show which is the best segmentation technique.

