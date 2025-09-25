# Evolution Dataset of Oracle Bone Characters

This repository contains a dataset for the evolution of Oracle Bone Characters.

[**Download the EVOBC Dataset**](https://figshare.com/s/ce2cf55b35a2f8ecc4c6)

## Dataset Structure

The dataset is organized into the following directory structure:

```
.
├── Data
│   ├── EVOBC
│   │   ├── ID1
│   │   │   ├── ID1_Source_Era_Another_numbers.jpg
│   │   │   └── ...
│   │   ├── ID2
│   │   │   ├── ID2_Source_Era_Another_numbers.jpg
│   │   │   └── ...
│   │   └── ...
│   └── OBC
│       ├── ID1
│       │   ├── ID1_Source_Era_Another_numbers.jpg
│       │   └── ...
│       └── ...
└── ...
```

## Character Script Shorthands

The dataset includes characters from various historical periods. Here are the shorthands used in the dataset:

| Shorthand | Full Name                        | Period                     |
| :-------- | :------------------------------- | :------------------------- |
| **OBC**   | Oracle Bone Characters           | 15th century B.C.          |
| **BI**    | Bronze Inscriptions              | 13th to 221 B.C.           |
| **SS**    | Seal Script                      | 11th to 8th centuries B.C. |
| **SAC**   | Spring and Autumn period Characters | 770 to 476 B.C.            |
| **WSC**   | Warring States period Characters | 475 B.C. to 221 B.C.       |
| **CS**    | Clerical Script                  | 221 B.C. to 220 A.D.       |

## JSON File Descriptions

The repository includes JSON files to help you work with the dataset:

*   `Key&Value.json`: This file maps the character IDs to their corresponding Chinese labels.
*   `List_of_EVOBC.json`: This file contains the storage paths for all the images in the EVOBC dataset.

## To-Do List

- [ ] 公开数据处理代码