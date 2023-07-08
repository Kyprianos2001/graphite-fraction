# graphite-fraction
# Graphite Fraction Analysis from SEM Microscopy Images

This code analyzes SEM microscopy images to calculate the graphite fraction present in the images. It performs the following steps:

1. Defines the file names of the SEM microscopy images in the `file_names` variable.
2. Initializes an array to store the graphite fractions (`graphite_fractions`) and a cell array to store the file names (`names`).
3. Loops over each file and performs the following operations:
   - Loads the SEM microscopy image.
   - Converts the image to grayscale.
   - Segments the graphite regions using thresholding.
   - Extracts the properties of the segmented regions.
   - Calculates the total area fraction of graphite.
   - Stores the graphite fraction in the `graphite_fractions` array.
   - Displays the segmented regions overlaid on the original image.
   - Prints the graphite fraction and saves the file name in the `names` array.
4. Creates a scatter plot of the graphite fractions, labeling each point with the corresponding magnification.
5. Adds a dashed horizontal line at y=0.47 as a reference.
6. Adjusts various plot settings for font size, figure size, and plot appearance.

## Prerequisites

The code requires the following dependencies:

- MATLAB Image Processing Toolbox

## Usage

1. Place the SEM microscopy images in the same directory as the code.
2. Update the `file_names` variable with the names of the images you want to analyze.
3. Run the code to calculate the graphite fractions and generate the scatter plot.

## Output

The code outputs the following:

- The calculated graphite fractions for each image, displayed in the MATLAB console.
- A scatter plot showing the graphite fractions for different magnifications.

Feel free to adjust the `picturewidth` and `hw_ratio` parameters in the code to modify the plot size and aspect ratio.


