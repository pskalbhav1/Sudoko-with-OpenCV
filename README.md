# Sudoko-with-OpenCV

Sudoko can be solved using OpenCV in simple steps as follows:
   
1. Input the Image and analyse it to extract the Sudoko Grid from the Image ( can be done using Hough Lines and contours considering the grid to be the largest contour in the given Image
2. Once, the Sudoko grid is extracted, the next important thing that we need to do is to extract numbers as well as their positions from the grid.
3. A CNN Model is created on the MNIST Dataset which can be used to detect numbers in the given grid.
4. Next step is to make our model solve the Grid. We have different functions which determine if the number is already present in that row, column or 3*3 grid or not. If not, then the number can be placed in that particular co-ordinates, and this position is noted. This method is called BackTracking.
5. Once, we figure out the solutions, all that we need to do is to rewrite/ display the numbers of the image in their proper positions.
     
Using the concepts of Convolutional Neural Networks, OpenCV and BackTracking, we can analyse and solve Sudoko puzzles very fast.
