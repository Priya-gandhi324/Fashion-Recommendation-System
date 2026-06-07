# Fashion Recommendation System using Deep Learning

An end-to-end, content-based fashion recommendation engine that suggests visually similar clothing items based on an input image. 
* **Feature Extraction**: Uses a pre-trained **ResNet50** convolutional neural network to extract feature vectors from fashion images.
* **Similarity Matching**: Integrated **K-Nearest Neighbors (KNN)** with instantly suggests top 5 matching items from the dataset.
* **Streamlit UI**: For interactive web application allowing users to upload images and get recommendations.

## 🛠️ Tech Stack
* Python, TensorFlow (ResNet50), Scikit-Learn (NearestNeighbors), Streamlit, NumPy, Pillow (PIL)

## ⚙️ Installation & Setup Instructions (Locally on Windows)

### 1. Clone the Project & Set Up Environment
1. git clone
2. python -m venv venv
3. venv\Scripts\activate
4. pip install -r requirements.txt

### 2. Download the Dataset
This project uses the popular **Fashion Product Images Dataset (Small)** from Kaggle.
1. Go to Kaggle: [[Fashion Product Images Dataset](https://kaggle.com)](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small)
2. Download & Extract the dataset zip file inside your project root directory (Contains 44441 images).
3. Run the code in the fashion-recommendation-model.ipynb to generate all the pickle files

Note - Your folder structure matches this layout so the scripts run correctly:
fashion-recommendation-system/fashion-dataset/fashion-dataset/images/ 
fashion-recommendation-system/uploads/ 

### 5. Run the Streamlit Application
streamlit run app.py
