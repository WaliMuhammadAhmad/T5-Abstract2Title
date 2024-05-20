# Abstract2Title T5 Model Fine-tuning

This repository contains the Notebook to finetune the T5-base model for title generation from abstracts. The dataset used for this task is open-sourced on Kaggle: [Medical paper title and abstract NLP dataset](https://www.kaggle.com/datasets/wolfmedal/medical-paper-title-and-abstract-dataset).

## 📂 Dataset

The dataset used for fine-tuning is provided in both training and testing sets in CSV format. This dataset forms the basis for training and evaluation.

- **/dataset/train.csv**: This is used for training and contains a total of 6000 rows with abstracts of various sizes. Only abstracts with more than 200 words are used. You can change this setting in the notebook according to your requirements.
- **/dataset/test.csv**: This is used for testing and contains 2000 rows with abstracts of various sizes.

## 🚀 Getting Started

To fine-tune the T5 model using this repository and the provided dataset, follow these steps:

1. **Open the Google Colab Notebook:** Click the <a href="https://colab.research.google.com/drive/1tHGnpP2n83f0od_aOfoGoQsjGxXLxQfY">Open in Colab</a> button to open the notebook in Colab.

2. If the link does not work, clone this repository and open the notebook by clicking the "Open in Colab" button at the top of the notebook. OR you can open it manually in Colab.

3. **Run the Notebook:** Follow the instructions provided within the Colab notebook. It will guide you through the steps for fine-tuning the T5 model.

## BLEU Score

Average BLEU Score: 0.9913513513513513 which is close to 1.

## Citation

I wish I could add citations, but neither the dataset nor the notebook provided them. However, please consider using my work and referencing this repository if you find it useful.
