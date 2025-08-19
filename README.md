# Multilevel Depression Detection from Twitter using Fine-Tuned RoBERTa

## Introduction
This project aims to detect and analyze different levels of depression (mild, moderate, and severe) through Twitter posts using a fine-tuned RoBERTa model. Our research underscores the importance of social media in early-stage depression detection and offers a novel approach to mental health monitoring.

## Authors
- Afra Zaman
- Syeda Sunjida Ferdous
- Nazneen Akhter
- Tabassum Ibnat Ena
- Md. Mahmudun Nabi
- Salma Akter Asma

## Abstract
Depression is a significant global health issue. Early detection and treatment are crucial in mitigating its impacts. This project utilizes a fine-tuned RoBERTa model to identify multilevel depression from Twitter data, showcasing an accuracy of 90%. The methodology enhances understanding of depression severity and can significantly aid in mental health research and treatment.

## Dataset
The dataset used in this project is derived from Twitter, comprising posts classified into three categories: mild, moderate, and severe, based on the level of depression indicated. A pre-existing Twitter dataset was annotated into multiple levels of depression so that the model could be trained for this specific task. The original dataset can be accessed here: https://github.com/sunlightsgy/MDDL
## Model
The project utilizes the RoBERTa model, which has been fine-tuned to better understand the nuances of Twitter language and depression indicators. The model has been enhanced with additional dense layers and trained on a large corpus of data.


## Installation
Instructions for setting up the project environment:
git clone [repository-link]
cd [project-directory]
pip install -r requirements.txt


## Usage
To use the model for depression detection:
python detect_depression.py [options]


## Results
Our model demonstrates a high degree of accuracy in classifying Twitter posts into mild, moderate, and severe depression categories. 




## Citation

If you use the results or methods from our research in your work, please cite our paper:

```bibtex
@INPROCEEDINGS{10303632,
  author={Zaman, Afra and Ferdous, Syeda Sunjida and Akhter, Nazneen and Ena, Tabassum Ibnat and Nabi, Md. Mahmudun and Asma, Salma Akter},
  booktitle={2023 International Conference on Information and Communication Technology for Sustainable Development (ICICT4SD)}, 
  title={A Multilevel Depression Detection from Twitter using Fine-Tuned RoBERTa}, 
  year={2023},
  pages={280-284},
  doi={10.1109/ICICT4SD59951.2023.10303632}
} 



