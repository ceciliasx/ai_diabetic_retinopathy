# This project was made by:
- Liauw, Jeremy Marvelle
- Mary Anggita Priscilla
- Filipus Darren Siswanto

# AID-R: AI-Powered Diabetic Retinopathy Detection

AID-R is a telemedicine-integrated product enhanced with Artificial Intelligence, specifically deep learning. It focuses on detecting retinal abnormalities to determine the presence and severity of **diabetic retinopathy** in patients. This condition is common among individuals with diabetes and, if left untreated, may lead to vision loss or blindness.

## ✨ Features

- 🔍 **Automatic detection** of diabetic retinopathy from retinal images.
- 🧠 Powered by deep learning using **CNN models**.
- 🧪 Trained with **Transfer Learning** for improved accuracy.
- 📊 Classifies retinopathy into five severity levels:
  - No DR
  - Mild
  - Moderate
  - Severe
  - Proliferative
- 🖼️ Accepts retina image uploads from users.
- 🖥️ **GUI Application** built with Python Tkinter.
- 🤖 **Discord Bot** interface using `discord.py`.

## 📚 Dataset

- **Name**: APTOS 2019 Blindness Detection
- **Source**: [Kaggle](https://www.kaggle.com/datasets/mariaherrerot/aptos2019)
- This dataset contains high-resolution retinal fundus images, each labeled with a corresponding diabetic retinopathy grade.

## 🧠 Models Used

After extensive experimentation, the following pre-trained models were selected:

- **EfficientNetB0**
- **DenseNet121**

These models are fine-tuned using **Transfer Learning**, allowing them to adapt to the APTOS dataset while leveraging knowledge from prior training on large-scale image datasets.

## 🛠️ Tech Stack

| Component       | Technology             |
|----------------|------------------------|
| Deep Learning  | TensorFlow, Keras      |
| GUI App        | Python Tkinter         |
| Bot Interface  | discord.py             |
| Model Backbone | EfficientNetB0, DenseNet121 |

## 🏁 How It Works

1. **User uploads** a retina image via the GUI app or Discord bot.
2. Image is **preprocessed** and passed through the trained CNN model.
3. Model returns a **classification result** indicating the stage of diabetic retinopathy.
4. Result is displayed in the application or sent as a reply in Discord.

## 📌 Installation

- Application

https://drive.google.com/file/d/1kNf8TEvqC75qxuXXjBnu17dVoKaOPZqC/view?usp=drive_link

- Discord Bot

https://discord.com/oauth2/authorize?client_id=1318625801209643079&permissions=8&integration_type=0&scope=bot

! Please see Instruction Manual.pdf for further information.
