🌳 Tree Species Identification using CNN

This project is a deep learning-based image classification model that identifies different species of trees using Convolutional Neural Networks (CNNs).

📂 Dataset

The dataset consists of multiple categories of tree images. Each folder in the dataset corresponds to a specific tree species.

📌 Dataset Source: Custom uploaded dataset (local)

🚀 Project Structure

tree-species-identification/
|
├── tree_species_identification.ipynb   → Main notebook
├── archive.zip                         → (Optional) Raw dataset
└── README.md                           → Project description

🔧 How to Run

1. Install required packages:

   pip install tensorflow matplotlib seaborn opencv-python scikit-learn

2. Run the notebook in Google Colab or Jupyter Notebook:

   tree_species_identification.ipynb

3. Upload and extract the dataset (archive.zip) inside your runtime.

📊 Model Architecture

- Input Layer: Resized images (128x128x3)
- 3 Convolutional + MaxPooling Layers
- Flatten → Dense Layers
- Output Layer: Softmax (multi-class classification)

✅ Results

- Accuracy: Depends on dataset and training epochs
- Metrics: Confusion Matrix and Classification Report included in notebook

👨‍💻 Author

Kabinesh  
GitHub: https://github.com/Kabinesh641

📜 License

This project is licensed under the MIT License.
