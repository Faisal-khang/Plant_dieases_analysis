# Plant_dieases_analysis
Plant disease prediction uses deep learning to analyze leaf images and detect diseases automatically. By identifying color changes, spots, and texture patterns, the system provides quick, accurate diagnosis, helping farmers take early action, reduce crop loss, and improve agricultural productivity.
✨ Features

Automatic plant leaf disease detection

CNN-based deep learning model

High accuracy on test images

Streamlit GUI for user-friendly prediction

Easy-to-use image upload interface

Supports multiple plant disease classes

🧠 Technologies Used

Python

TensorFlow / Keras

NumPy, Pandas

Matplotlib / Seaborn

Streamlit

OpenCV

Scikit-learn

📂 Project Structure
Plant-Disease-Prediction/
│── dataset/
│── models/
│── app.py                # Streamlit GUI
│── train.py              # Model training script
│── predict.py            # Prediction script
│── requirements.txt
│── README.md

🚀 How to Run
1️⃣ Clone the Repository
git clone <your-repo-link>
cd Plant-Disease-Prediction

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Train the Model
python train.py

4️⃣ Run Streamlit App
streamlit run app.py

📸 Prediction Demo

Upload a plant leaf image

Model processes the image

Displays predicted disease and confidence score

📊 Dataset

You can use:

PlantVillage dataset

Custom images of plant leaves

📈 Results

High accuracy CNN model

Effective for multiple plant disease categories

Works in real-time via GUI

🤝 Contribution

Feel free to submit issues or pull requests to improve the project.
