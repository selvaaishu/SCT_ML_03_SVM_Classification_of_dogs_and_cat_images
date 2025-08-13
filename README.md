Cat vs Dog Image Classification using SVM

📌 Overview

This project classifies images of cats and dogs using a Support Vector Machine (SVM) model.
It uses the scikit-learn library for model training and scikit-image for image preprocessing.


---

📂 Project Structure

Archive/
   ├── Animals/
        ├── cats/   # Cat images
        ├── dogs/   # Dog images
main.py              # Main Python script
README.md            # Project documentation
requirements.txt     # Python dependencies
.gitignore           # Ignore dataset in GitHub


---

⚙ Installation & Setup

1️⃣ Clone the repository

git clone https://github.com/your-username/cat-vs-dog-svm.git
cd cat-vs-dog-svm

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Download the dataset
This project uses the Kaggle Dogs vs Cats dataset.
After downloading, extract the dataset so the structure looks like this:

Archive/
   ├── Animals/
        ├── cats/
        ├── dogs/


---

🚀 Running the Project

python main.py


---

📊 Output Example

Cats images: 50
Dogs images: 50
Model accuracy: 85.0%


---

🧠 How It Works

1. Loads images from Archive/Animals folder.


2. Resizes them to 64×64 pixels.


3. Flattens images into 1D arrays.


4. Trains an SVM classifier.


5. Evaluates model accuracy.




---

📌 Future Improvements

Increase dataset size for better accuracy.

Use deep learning (CNN) for higher accuracy.

Implement real-time image classification.
