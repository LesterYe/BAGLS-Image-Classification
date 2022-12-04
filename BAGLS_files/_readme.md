# Benchmark of Automatic Glottis Segmentation (BAGLS)

With the BAGLS dataset, we provide a total of 59,250 endoscopic images with their respective segmentation map together with 559 video snippets and the entire raw data used to generate the BAGLS dataset. Acquired in seven international hospitals, we aimed for a diverse dataset that allows the establishment of robust glottis segmentation algorithms and/or the training of deep neural networks. Our provided test dataset allows to benchmark segmentation methods and ensures comparability across studies.

# Contents

We provide four zip files:

- training.zip
- test.zip
- videos.zip
- raw.zip 

```training.zip``` and ```test.zip``` contain 55,750 and 3,500 endoscopic image/segmentation map/metadata pairs, respectively. The test dataset contained in ```test.zip``` should be used to benchmark the glottis segmentation methods, not the training dataset. The ```videos.zip``` file contains 559 videos with 30 consecutive frames each and their corresponding segmentation map created by the baseline neural network presented in the BAGLS manuscript. The ```raw.zip``` file contains the entire raw data used to create the BAGLS benchmark dataset. It also contains segmentation maps created by the baseline neural network presented in the BAGLS manuscript.

# Files

Files are indexed by numbers starting at 0 (e.g. 0.png). Endoscopic images and segmentation maps are in PNG file format (e.g. 0.png and 0_seg.png), metadata is provided as JSON files (e.g. 0.meta). Videos are provided in mp4 file format (e.g. 0.mp4), together with its respective metadata (e.g. 0.meta) and its respective segmentation maps over time (e.g. 0_seg.mp4).

# Data Preview

On our website [bagls.org](https://www.bagls.org), we provide direct access to training and test set, as well as to video snippets contained in the BAGLS dataset.