# Person Re-identification Using Clustering

This repository contains Jupyter Notebooks and resources for person re-identification using clustering techniques. The process involves the following steps:
1. Converting video to frames.
2. Detecting bounding boxes around persons in the frames.
3. Cropping the detected objects (persons) from the frames.
4. Clustering the cropped objects using k-means clustering.

## Repository Structure
- `video_to_frames1.ipynb`: Notebook to convert video files into individual frames.
- `frames_to_bounding_boxes.ipynb`: Notebook to detect bounding boxes in frames.
- `bounding_boxes_to_cropped_objects.ipynb`: Notebook to crop objects from frames based on bounding boxes.
- `K-Means_clustering.ipynb`: Notebook to perform k-means clustering on cropped objects.
- `data`: Directory containing example data for testing the notebooks.
- `requirements.txt`: List of dependencies required to run the notebooks.

## Installation
First, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/ankithagithub/Person_Re-Identification_using_clustering.git
cd Person_Re-Identification_using_clustering
Then, install the required dependencies:
pip install -r requirements.txt
Usage
Step 1: Convert Video to Frames

Use video_to_frames.py to convert a video file into individual frames.

bash

python video_to_frames.py --input data/example_video.mp4 --output data/example_frames/

Step 2: Detect Bounding Boxes

Use frames_to_bounding_boxes.py to detect bounding boxes in the frames.

bash

python frames_to_bounding_boxes.py --input data/example_frames/ --output data/bounding_boxes/

Step 3: Crop Objects from Frames

Use bounding_boxes_to_cropped_objects.py to crop objects from frames based on the detected bounding boxes.

bash

python bounding_boxes_to_cropped_objects.py --input data/bounding_boxes/ --output data/cropped_objects/

Step 4: Perform Clustering

Use cropped_objects_clustering.py to perform k-means clustering on the cropped objects.

bash

python cropped_objects_clustering.py --input data/cropped_objects/ --output data/clusters/


