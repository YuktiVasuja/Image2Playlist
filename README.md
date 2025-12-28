# Vibe Music Project 🎵🎨

A music recommendation system that suggests songs based on the **vibe of an image**.  
It uses **VGG16** for image feature extraction and **Spotify API** to fetch songs.

# Features

- Extracts image features using **VGG16** pretrained model.
- Finds nearest images in the dataset using **K-Nearest Neighbors (KNN)**.
- Determines the **dominant vibe** of the uploaded image.
- Fetches **Spotify tracks** matching the detected vibe.
- Supports vibes like `calm`, `energetic`, `sad`, `chill`, and `romantic`.

## Setup Instructions

1. **Clone the repository**

git clone https://github.com/your-username/vibe-music-project.git

2. **Install dependencies**

pip install tensorflow spotipy python-dotenv scikit-learn

3. **Add your dataset**

Place images in /dataset folder.

Organize images by vibe:

dataset/
│
├─ calm/
├─ energetic/
├─ sad/
├─ chill/
└─ romantic/


4. **Run the notebook in Colab.**
