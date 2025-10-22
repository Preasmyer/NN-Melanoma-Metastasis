Data Folder Overview

This folder contains the core data assets used in this project. It includes structured datasets, descriptive documentation, and supporting visual materials to help understand and explore the data.

Contents

final_data.csv - A comma-separated values (CSV) file containing the primary dataset used for analysis. Each row represents a data record, and each column corresponds to a specific feature or variable.

Data_Description.pdf - A markdown file that provides detailed explanations of each column in the CSV file, including data types, units, and any relevant notes on missing values or preprocessing.

images/ A subfolder containing visual assets related to the dataset. These are IHC images to be used in the neural networks. They are downscaled from ~ 80,000x80,000 pixels to 512x512. Future images may be slides from original images if NN accuracy calls for increased resolution.


Usage Notes
Ensure that dataset.csv is loaded with UTF-8 encoding to avoid character issues.

Refer to Data_Description.pdf before performing any analysis to understand the structure and semantics of the data.

Images in the images/ folder may be used for training, testing, or documentation purposes depending on the scope of the project.
