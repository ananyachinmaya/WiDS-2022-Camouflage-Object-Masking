# WiDS-2022-Camouflage-Object-Masking
This repository consists of everything I used to do the project, including the learning resources, my notes and my codes.
## Introduction
Camouflage Object Masking deals with the task of identifying and segmenting out objects that are not well-distinguished from their backgrounds. This is a specialized problem within the domain of Computer Vision, which has been seeing and continues to see rapid advances and novel techniques.<br>
Camouflage Object Masking has several applications across varied fields including medical image segementation, rare species discovery, the miliary, and so on. Recent work also suggests that research in AI-based segmentation of camouflaged objects could hold key insights into how the hierarchial levels of human visual perception are structured.<br>

## Running the code
The primary framework that is used is <b>PyTorch</b>. To run the code, download the Images and Masks folders from the repository. The paths used in the code are specifically for my PC. Please make changes in the code accordingly. <br>
The FPN_With_Calculated Scheduling folder has the .pt files till 130 epochs. Running the training model code may take too much time so you can directly download these .pt files and add the path on the evaluate model code. to get the outputs directly. The Masks folder has predicted masks but you can remove that part of the code if you just want to pass an image and get the output<br>

## Displaying the Outputs
Observe the last 2 cells of the evaluation model code and make changes accordingly to control how many images you want to display and for how long. The outputs should open in a new window as you run 
