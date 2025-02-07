# Image Dataset Creation

Overview

This project focuses on preparing an image dataset by processing and organizing images based on their associated tags. The notebook provides step-by-step methods to clean metadata, create structured folders, and filter images efficiently.

## Features

* Remove Unnecessary Columns: Cleans metadata by dropping irrelevant information.
* Extract Tags: Identifies and lists all unique tags.
* Organize Images: Creates folders for each tag and moves corresponding images.
* Dataset Validation: Ensures proper distribution of images by analyzing folder contents.
* Filtering: Removes folders containing fewer than five images to maintain dataset quality.

### Prerequisites

* Python 3.x
* Pandas
* OS
* Shutil


## Output

* A structured dataset where images are stored in folders corresponding to their respective tags.
* Summary statistics on folder distribution.

## Applications

* Machine Learning & Deep Learning training datasets
* Image classification projects
* Data preprocessing for AI applications
