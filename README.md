# Textbase AI Chatbot for Drug Recommendations

## Overview
In the rapidly evolving world of healthcare, precision and accuracy in drug recommendations are paramount. This repository presents an advanced AI chatbot meticulously designed to assist in this critical domain. Here's a deeper dive into its architecture and capabilities:

1. Integrated Machine Learning Model: At the core of this chatbot lies a machine learning model trained on patient health metrics. It assimilates details such as age, gender, blood pressure, cholesterol levels, and sodium-to-potassium ratios to generate an apt drug recommendation. The choice of the K-Nearest Neighbors (KNN) algorithm ensures that the model can accurately consider the multi-dimensionality of patient data and offer tailored drug suggestions.

2. Conversational AI Interface: Beyond just data processing, this chatbot shines in its user interactions. It leverages the prowess of the GPT-2 model, fine-tuned with an enriched dataset, to converse in a manner reminiscent of seasoned healthcare professionals. This ensures users, whether they be doctors, pharmacists, or curious individuals, have a seamless and insightful interaction.

   Watch Demo: https://www.youtube.com/watch?v=MMNmpVLN_O4


## Table of Contents
- [Motivation](#motivation)
- [Algorithm Selection](#algorithm-selection)
- [Enhancing Conversational Dataset](#enhancing-conversational-dataset)
- [Fine-tuning with GPT-2](#fine-tuning-with-gpt-2)
- [Getting Started](#getting-started)
- [Datasets](#datasets)


## Motivation
Choosing the right medication for a patient based on their health metrics is crucial. With the myriad of drugs available, making the correct decision can be challenging. This project aims to aid healthcare professionals by offering a chatbot that can suggest appropriate drugs, ensuring the best patient care.

## Algorithm Selection
The initial recommendation model used was based on Random Forest. However, to achieve higher accuracy and precision, the K-Nearest Neighbors (KNN) algorithm was selected. KNN's ability to effectively handle multi-class classification problems and its simplicity made it a suitable choice for this dataset.

## Enhancing Conversational Dataset
The base conversational dataset was improved by diversifying the bot's responses. This ensures the chatbot sounds more human-like, leading to a better user experience. The dataset was augmented to include a wider range of phrasings and patterns, catering to various user inputs.

## Fine-tuning with GPT-2
To boost the chatbot's conversational capabilities, the GPT-2 model was fine-tuned with the enhanced dataset. This ensures that the chatbot can handle a broad spectrum of user queries, even those not explicitly present in the training data.

## Getting Started

### Prerequisites
- **Python 3.8**
- **PIP**
- **Jupyter Notebook or Jupyter Lab**
- **Git (for cloning the repository)**

### Installation

1. **Clone the Repository**:

```
git clone https://github.com/ashishmohapatra240/textbase.git
cd textbase
```

2. Set Up a Virtual Environment (Recommended):
```
python -m venv venv
source venv/bin/activate
```
3. Install Required Libraries:

```
pip install -r requirements.txt
```

4. **Download and Place the Models**:
- Download the models from [this link](https://drive.google.com/drive/folders/1w6RQl4GRhf6TltuPJsAnIN9TKOM6YlZA?usp=sharing).
- Extract and place the `models` folder in the root directory of the project.

5. Run the Chatbot:

```
Run the Chatbot:
```

6. **Run the Notebook on Jupyter or Colab**:

If you have Jupyter Notebook or Jupyter Lab installed, navigate to the project directory and run:

```
jupyter notebook
```



## Datasets
The datasets utilized in this project are present in the repository. They include:
- `drug200.csv`: Contains patient health metrics and corresponding drug prescriptions.
- `improved_conversations_1000.csv`: The enhanced conversational dataset for fine-tuning the GPT-2 model.

