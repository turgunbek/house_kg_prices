# house_kg_prices

Parsing the data from house.kg and further linear ML models building for price prediction.

Parsing file was got from https://github.com/IslamJenishbekov/flats_project_house_kg/tree/main.

The image parser (flats_image_parser.ipynb) was written and is capable to download the images using their links contained in flats_unique.csv.

The mapping (`flat_url`, `image_url`, `image_name`) is in file url_iamges_0_4484.csv.

The file download_errors_0_4484.csv contains the urls of flats which either don't exist or don't contain images or have some troubles with downloading.

The photos themselves are in zip archives availables by this [link](https://drive.google.com/drive/folders/15y-nMhfW_dCFs1DrPq3x9tAwhno7Vevp?usp=drive_link).
The numbers in archive names indicate to start and end of indices of flats in flats_unique.csv.
