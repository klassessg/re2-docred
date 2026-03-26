# Re²-DocRED: Revisiting Revisited DocRED for Joint Entity and Relation Extraction

This is the official repo for the EACL 2026 paper "[Re²-DocRED: Revisiting Revisited DocRED for Joint Entity and Relation Extraction](https://aclanthology.org/2026.eacl-long.213/)", released by KLASS Engineering & Solutions Pte Ltd as part of the accompanying research.

## Contents

This repository provides:

* **Re²-DocRED**: Revised train, validation and test splits of Re-DocRED and DocGNRE
* A revised Mandarin test split derived from REDFM

The datasets are located in the '[dataset](dataset)' folder

## Dataset Overview

Re²-DocRED builds upon the following datasets:

* Re-DocRED:https://github.com/tonytan48/Re-DocRED
* DocGNRE: https://github.com/bigai-nlco/DocGNRE
* REDFM: https://huggingface.co/datasets/Babelscape/REDFM

Our contributions focus on improving annotation quality through explicit reasoning steps based on constraints derived from relation definitions.

## License

The dataset released in this repository is provided under the **Creative Commons Attribution–ShareAlike 4.0 (CC BY-SA 4.0)** license. The text of the license can be found [here](https://creativecommons.org/licenses/by-sa/4.0/).

This dataset builds upon prior open-source resources:

* Re-DocRED and DocGNRE (MIT License)
* REDFM (CC BY-SA 4.0)

All original sources are credited. Users should cite both the original datasets and this work when appropriate.

If you use this dataset, please cite the accompanying paper.
 
## Citation

If you use this dataset or repository, please cite:
```bibtex
@inproceedings{heng-etal-2026-re2,
  title = {Re2-{D}oc{RED}: Revisiting Revisited-{D}oc{RED} for Joint Entity and Relation Extraction},
  author = {Heng, Chen Kim and Tong, Shao Wen and Wong, Julian Wei Sheng},
  booktitle = {Proceedings of the 19th Conference of the European Chapter of the Association for Computational Linguistics},
  year = {2026}
}