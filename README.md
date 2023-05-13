# Object Detection 🎥

## Script Overview

This script performs object detection using YOLOv3. To run the script, follow the instructions below.

### Required Files 🗂️

Download the following files:

1. **Jupyter Notebook**: The notebook is available in this repository.

2. **Model Weights**: Execute the command below in your terminal to download the model weights to your current directory:

`curl -O https://pjreddie.com/media/files/yolov3.weights`

3. **Common Objects in Context (COCO)**: Download the `coco.names` file by running the following command in your terminal:

`curl -O https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names`

4. **Configuration File**: Obtain the configuration file using the command below in your terminal:

`curl -O https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg`

### Running the Code 💻

Follow these steps to run the code:

1. Ensure all the required files are in the same directory.
2. Add the video you want to apply object detection to in the same directory.
3. Rename the video file as `video.mp4`.
4. Open the Notebook and execute the code.

### Output 🍾

The script may take some time to process. Once completed, an `output_video` will be generated in your current directory.
