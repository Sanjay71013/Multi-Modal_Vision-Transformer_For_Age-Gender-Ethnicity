# Age, Gender, and Ethnicity Detection Using Vision Transformers

This repository contains the source code for age, gender, and ethnicity detection using Vision Transformers (ViT). The project explores three different attention mechanisms integrated with ViT: CBAM, Coordinate Attention, and Self-Attention.

## Repository Structure

- `age-gender-ethnicity-detection-using-vit_CBAM.ipynb`: Jupyter notebook implementing Vision Transformer with CBAM (Convolutional Block Attention Module) for age, gender, and ethnicity detection.
- `age-gender-ethnicity-detection-using-vit_coordinate_attention.ipynb`: Jupyter notebook implementing Vision Transformer with Coordinate Attention for age, gender, and ethnicity detection.
- `age-gender-ethnicity-detection-using-vit_self_attention.ipynb`: Jupyter notebook implementing Vision Transformer with Self-Attention for age, gender, and ethnicity detection.

## Dataset

The model training and evaluation are conducted on the publicly available **UTK-Face** dataset. This dataset contains images labeled with age, gender, and ethnicity information.

- Dataset: [UTK-Face Dataset](https://susanqq.github.io/UTKFace/)

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Sanjay71013/Multi-Modal_Vision-Transformer_For_Age-Gender-Ethnicity.git
cd age-gender-ethnicity-detection-vits
```

2. Install the required libraries
   
```bash
pip install -r requirements.txt
```

## Usage

Open the desired notebook in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook age-gender-ethnicity-detection-using-vit_CBAM.ipynb
```

## Results

Detailed results and evaluations of the models can be found in the Results section of each notebook. The notebooks provide visualizations of the training process and model performance metrics.

## Citation

If you use this code or dataset in your research, please cite the following:

```bibtex
@misc{Multi-modal Age, Gender, and Ethnicity Prediction with Enhanced Vision Transformer: A Comprehensive Attention Mechanism Study,
  author = {Sanjay M, Chinnakanu Sai Janakiram, Lakshya Swarup, Deepashree P V and Sumathi D},
  title = {Revolutionizing Age, Gender, and Ethnicity Recognition with Multi-Modal Vision Transformers},
  year = {2024},
  journal = {YET TO BE PUBLISHED},
  url = {https://github.com/yourusername/age-gender-ethnicity-detection-using-vit}
}

@dataset{utkface,
  author = { Yang Song, Zhifei Zhang},
  title = {UTK-Face},
  year = {2022},
  url = {https://www.kaggle.com/datasets/jangedoo/utkface-new}
}
```
