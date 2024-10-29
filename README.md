# 🍔 Bootcamp Project
Food Calorie Analysis and Comparison Using Fine-Tuned Models.

## 📚 Introduction
This project involves developing an application that can identify the number of calories in food items by analyzing images. The idea is to take a picture of the food, and the application will use AI to estimate the calorie content.

Our objective is to fine-tune a model and use the trained model for this application. However, after fine-tuning the GPT-4 model, it stopped working for image prompts. 

Next, vision tuning will be attempted.

## 🗂 Repository Structure
The repository is organized into the following folders and files:

### 📁 Data Folder
The `data` folder contains the food calorie dataset sourced from Kaggle. You can download the dataset from the following link:
[Kaggle Food Calorie Dataset](https://www.kaggle.com/datasets/vaishnavivenkatesan/food-and-their-calories)

### 📁 Images Folder
The `images` folder includes example images of different foods. These images are used for visual analysis and model testing.

### 📓 Notebooks
1. `finetune_model_notebook.ipynb`: This Jupyter notebook contains the code for fine-tuning a pre-trained model on the food calorie dataset.
2. `chat_example.ipynb`: This Jupyter notebook provides examples of how to compare the performance of the fine-tuned model with GPT-4.
3. `image_promting.ipynb`: There is an image promting example from OpenAI.

## 🚀 How to Use
1. **📦 Install Dependencies**: Ensure you have the necessary Python packages installed.
2. **🔑 OpenAI Api Key**: Replace your OPENAI_API_KEY in .env file.
3. **🏃‍♂️ Run Notebooks**: Open the Jupyter notebooks (finetune_model_notebook.ipynb and chat_example.ipynb) and follow the instructions within to fine-tune the model and compare its performance with GPT-4.