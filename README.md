World Flags Annotated Dataset – VGG Annotation Project
Overview
This project focuses on annotating world flag images using image-level labels and attributes. The dataset was annotated with the VGG Image Annotator (VIA) and is designed for classification and metadata-based learning tasks.

Task Type
Image classification
Image-level attribute annotation

Dataset Structure
Images are organized into folders based on continent category:
Africa
Asia
Europe
North_America
South_America
Oceania

Each image belongs to one continent folder and contains multiple descriptive attributes. The annotations/ folder contains the JSON file with metadata for each flag.

Annotated Attributes
For each image, the following attributes were annotated using VIA:
country: name of the country
capital: capital city
currency: official currency
language: primary language(s)
calling_code: international calling code
highest_point: highest geographical point
lowest_point: lowest geographical point
major_religion: main religion(s)
area: total area in sq km
continent: continent where the country is located
flag_colors: number of colors in the flag

Annotation Methodology
Image-level annotation only
Attributes stored as metadata per image
Consistent attribute values across the dataset
Images with unclear or duplicate flag information were excluded

Annotation Tool
VGG Image Annotator (VIA)

Annotation Output
VIA JSON annotation file
Stored in the annotations/ directory

Potential Applications
Country classification models with auxiliary attributes
Data analysis and visualization of global statistics
Educational machine learning datasets

Notes
This dataset was created for portfolio and educational purposes to demonstrate image classification and attribute-based annotation workflows.