# HE staining images of serous effusion cells

This repository contains the dataset used for the **Medical Image Analysis**. The dataset is pre-split into training, validation, and test sets, with corresponding annotations in two formats: TXT and XML.

## Repository Structure

- `Images/`: Contains the images organized into subfolders:
  - `train/`: 80% of the dataset used for training.
  - `val/`: 10% of the dataset used for validation.
  - `test/`: 10% of the dataset used for testing.

- `Labels/`: Contains TXT files corresponding to the images, where each file provides the object class and bounding box information.

- `Annotations/`: Contains XML files that follow the PASCAL VOC format, providing detailed annotations including object classes and bounding boxes.

## Usage

1. Download the repository by cloning it or directly from GitHub.
   ```bash
   git clone https://github.com/Passer-montanus/ResearchData-for-MIA
