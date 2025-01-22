# Supplementary Documentation for MMP-2k

## Table of Contents
1. [CC License Detail](#cc-license-detail)
2. [Data Access](#data-access)
3. [Dataset Overview](#dataset-verview)
4. [Supplementary Detail](#dataset-detail)

---

## CC License Detail
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You are free to:
- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material.

Under the following terms:
- **Attribution**: Credit must be given to the original creator.
- **NonCommercial**: You may not use the material for commercial purposes.
- **ShareAlike**: If you remix, transform, or build upon the material, you must distribute your contributions under the same license.

### Attribution Guidelines
If you use this dataset, please provide the following attribution:
Dataset name:[MMP-2k]
Creator:


---

## Data Access
### Access Link
The database is available for download at: [Huggingface](https://huggingface.co/datasets/MMP-2k/MMP-2k), [Github](https://github.com/MMP-2k/MMP-2k). 

### Citation
Please cite if using the dataset.


---

## Dataset Detail
- **Title**: MMP-2k
- **Description**: A benchmark multi-labled macro photography (MP) database
- **Date of Release**: 23rd, Jan, 2025

### Summary
MMP-2k is a benchmark dataset containing 2,000 in-the-wild MPs. Each MP within MMP-2k is attached with a quality MOSs, a quality report consists of an overall quality description and distortion annotations.

MMP-2k dataset contains:
1. A MOS.csv file in which each image id is associated with 17 perceptual ratings from assessors, a MOS value, distortion annotations, and a quality report.
2. A directory containing 2,000 MPs with the resolution of 512x384 (horizontal) or 384x512 (vertical).
3. A directory containing 2,000 MPs with the resolution of 1024x768 (horizontal) or 768x1024 (vertical).

### Structure of MOS.csv file
| Image ID   | Rating1 | rating2 | --- | --- | Rating17 | MOS  |Distortion annotations| Quality report|
|------------|---------------------|---------------------|-----|-----|-----------------------|------|----|
| 1.jpg     |    1             |        1          | --- | --- |       2            |   | |
| 2.jpg     |    1              |          1       | --- | --- |         1          |   | |
| 3.jpg     |         1        |      1           | --- | --- |       1           |   | |
| 4.jpg     |         1        |        1        | --- | --- |               1     |   | |
| 5.jpg     |      1           |       1          | --- | --- |           1       |  | |
| ...        | ...                 | ...                 | ... | ... | ...                   | ...  | |
| 2000.jpg    |     1             |       1           | --- | --- |           1         |   | |
                  
### Structure of MMP-2k.json file



---
## Supplementary Detail



