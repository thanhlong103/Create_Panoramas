# Image Stitching

This is a Python script that demonstrates image stitching using OpenCV. 

## Installation

- Clone this repository or download the files as a zip archive.
- Install the required dependencies: OpenCV, numpy, math, glob, and matplotlib.

## Usage

1. Place the images you want to stitch in the `./scene` folder. Make sure that the images are named in a way that they are sorted in the order you want them to be stitched.
2. Open the `image_stitching.py` file in a Python editor or IDE.
3. Modify the `image_file1` and `image_file2` variables to select the two images you want to stitch. You can also modify other variables such as `MAX_FEATURES` and `GOOD_MATCH_PERCENT` to customize the feature detection and matching algorithms.
4. Run the script.

The script will display the following images:
- Keypoints detected in the reference and second image.
- Matching corresponding points between the two images.
- The second image aligned to the reference image using homography.
- The final stitched image.
