# Person Re-identification Using Clustering

This repository contains Jupyter Notebooks and resources for person re-identification using clustering techniques. The process involves the following steps:
1. Converting video to frames.
2. Detecting bounding boxes around persons in the frames.
3. Cropping the detected objects (persons) from the frames.
4. Clustering the cropped objects using k-means clustering.

## Repository Structure
- `video_to_frames.ipynb`: Notebook to convert video files into individual frames.
- `frames_to_bounding_boxes.ipynb`: Notebook to detect bounding boxes in frames.
- `bounding_boxes_to_cropped_objects.ipynb`: Notebook to crop objects from frames based on bounding boxes.
- `cropped_objects_clustering.ipynb`: Notebook to perform k-means clustering on cropped objects.
- `data`: Directory containing example data for testing the notebooks.
- `requirements.txt`: List of dependencies required to run the notebooks.

## Installation
First, clone the repository and navigate to the project directory:

```bash
git clone https://github.com/yourusername/Person-re-identification-using-clustering.git
cd Person-re-identification-using-clustering
