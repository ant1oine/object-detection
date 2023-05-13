# Object Detection 🎥

This script performs object detection using YOLOv3. To run the script, follow the instructions below.

### Required Files 🗂️

1. **Jupyter Notebook**: The notebook is available in this repository.

NumPy: `pip install numpy`

cv2: `pip install opencv-python`

2. **Model Weights**: Execute the command below in your terminal to download the model weights:

`curl -O https://pjreddie.com/media/files/yolov3.weights`

3. **Common Objects in Context (COCO)**: Run the following command in your terminal:

`curl -O https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names`

4. **Configuration File**: Obtain the configuration file using the command below in your terminal:

`curl -O https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg`

### Running the Code 💻

1. Ensure all the required files are in the same directory.
2. Put the video you want to apply object detection to in the same directory.
3. Rename the video file as `video.mp4`.
4. Open the Notebook and execute the code.

### Output 🍾

The script may take a few minutes to process. Once completed, an `output_video` will be generated in your current directory.
