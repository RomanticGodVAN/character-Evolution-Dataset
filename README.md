<h1 align="center">An open dataset for the evolution of oracle bone characters: EVOBC</h1>

<p align="center">
  <strong>Official repository for EVOBC (EVolution Oracle Bone Characters)</strong>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/2401.12467">📄 <strong>Paper</strong></a>
  &nbsp;•&nbsp;
  <a href="https://huggingface.co/datasets/HaisuGuan/EVOBC">🤗 <strong>Download EVOBC Dataset</strong></a>
  &nbsp;•&nbsp;
  <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/">📜 <strong>License: CC BY-NC-SA 4.0</strong></a>
</p>

<p align="center">
  A dataset for studying the historical evolution of Oracle Bone Characters.
</p>

---

## ✨ Overview

**EVOBC** is a dataset for studying the evolution of Oracle Bone Characters across multiple historical scripts and periods. This repository provides the dataset metadata, file lists, and documentation for working with EVOBC.

## 📦 Dataset Structure

The dataset is organized as follows:

```text
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

## 🏛️ Character Script Shorthands

The dataset includes characters from various historical periods. The following shorthands are used throughout EVOBC:

| Shorthand | Full Name                            | Period                     |
| :-------- | :----------------------------------- | :------------------------- |
| **OBC**   | Oracle Bone Characters               | 15th century B.C.          |
| **BI**    | Bronze Inscriptions                  | 13th to 221 B.C.           |
| **SS**    | Seal Script                          | 11th to 8th centuries B.C. |
| **SAC**   | Spring and Autumn period Characters  | 770 to 476 B.C.            |
| **WSC**   | Warring States period Characters     | 475 B.C. to 221 B.C.       |
| **CS**    | Clerical Script                      | 221 B.C. to 220 A.D.       |

## 🧾 Metadata Files

The repository includes JSON files to help you work with the dataset:

| File | Description |
| :--- | :---------- |
| `Key&Value.json` | Maps character IDs to their corresponding Chinese labels. |
| `List_of_EVOBC.json` | Contains storage paths for all images in the EVOBC dataset. |

## 📜 License

The EVOBC dataset is released under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/) (**CC BY-NC-SA 4.0**), consistent with the license specified on the Hugging Face dataset page.

## 📚 Citation

If you find EVOBC useful in your research, please cite:

```bibtex
@misc{guan2024opendatasetevolutionoracle,
      title={An open dataset for the evolution of oracle bone characters: EVOBC}, 
      author={Haisu Guan and Jinpeng Wan and Yuliang Liu and Pengjie Wang and Kaile Zhang and Zhebin Kuang and Xinyu Wang and Xiang Bai and Lianwen Jin},
      year={2024},
      eprint={2401.12467},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      doi={10.48550/arXiv.2401.12467},
      url={https://arxiv.org/abs/2401.12467}, 
}
```

## ✅ To-Do List

- [ ] Release the data processing code
