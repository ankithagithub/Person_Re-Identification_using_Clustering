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
pip install -r requirements.txt

## Usage
Step 1: Convert Video to Frames

Open video_to_frames.ipynb in Jupyter Notebook or Jupyter Lab and run the cells to convert a video file into individual frames.

Step 2: Detect Bounding Boxes

Open frames_to_bounding_boxes.ipynb in Jupyter Notebook or Jupyter Lab and run the cells to detect bounding boxes in the frames.

Step 3: Crop Objects from Frames

Open bounding_boxes_to_cropped_objects.ipynb in Jupyter Notebook or Jupyter Lab and run the cells to crop objects from frames based on the detected bounding boxes.

Step 4: Perform Clustering

Open cropped_objects_clustering.ipynb in Jupyter Notebook or Jupyter Lab and run the cells to perform k-means clustering on the cropped objects.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

##Acknowledgments

Special thanks to all the contributors and the open-source community for providing the tools and libraries used in this project.
