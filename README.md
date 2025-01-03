# Image_Clustering.ipynb

## Image Clustering Techniques

# Original Image:
![M_U](https://github.com/user-attachments/assets/ca6c9967-b3f8-43d3-af02-f3caaf7a1c65)

## 🚀 Overview
This notebook covers several image clustering tasks using OpenCV, NumPy, scikit-learn, and Matplotlib. Here are some key operations included in the notebook:
- K-means Clustering
- DBSCAN Clustering
- Mean Shift Clustering
- Fuzzy C-means Clustering
- Hierarchical Clustering
- Gaussian Mixture Models (GMM)
- Spectral Clustering
- Agglomerative Clustering

> **Goal:** To visualize and explore different ways of segmenting images using various clustering techniques.

# Computer Vision Lab - Image Clustering Techniques

This repository provides a Jupyter Notebook showcasing various image clustering techniques using OpenCV and Python. The notebook demonstrates image segmentation and clustering on images.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [References](#references)

## **Features**

1. **K-means Clustering**: Segments the image using K-means clustering.
2. **DBSCAN Clustering**: Performs density-based clustering.
3. **Mean Shift Clustering**: Applies Mean Shift for clustering.
4. **Fuzzy C-means Clustering**: Uses Fuzzy C-means for image segmentation.
5. **Hierarchical Clustering**: Implements hierarchical clustering to segment images.
6. **Gaussian Mixture Models (GMM)**: Applies GMM for clustering.
7. **Spectral Clustering**: Uses Spectral Clustering to group image pixels.
8. **Agglomerative Clustering**: Performs agglomerative clustering on the image.

## **Installation**

1. **Clone the repository**:
   Run the following command:
   ```bash
   git clone https://github.com/rixscx/Image_Clustering.git
   cd Image_Clustering
   ```

2. **Install Dependencies**:
   Use the following command to install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

Open the Jupyter Notebook: Start Jupyter Notebook and open `Image_Clustering.ipynb`:

```bash
jupyter notebook 
```

# **Image_Clustering.ipynb**
```
Output:
```
![image](https://github.com/user-attachments/assets/1feff6ad-bf42-475f-aff8-1e95f53316a5)

# **K-means Clustering:**
Segments the image using K-means clustering.
```
Output:
```
![image](https://github.com/user-attachments/assets/de793927-6a34-414c-ab5f-b1a68d08fca5)
![image](https://github.com/user-attachments/assets/e9e80043-49f0-4196-a483-df0604a13255)

# **DBSCAN Clustering:**
Performs density-based clustering.
```
Output:
```
![image](https://github.com/user-attachments/assets/38fa604a-2d27-462d-858d-169abbc00e6e)


# **Mean Shift Clustering:**
Applies Mean Shift for clustering.
```
Output:
```
![image](https://github.com/user-attachments/assets/2af14388-fc62-4857-b218-67fbd0810b4f)

# **Fuzzy C-means Clustering:**
Uses Fuzzy C-means for image segmentation.
```
Output:
```
![image](https://github.com/user-attachments/assets/e74a5138-d9c3-46db-83a5-bdebcc59581e)


# **Hierarchical Clustering:**
Implements hierarchical clustering to segment images.
```
Output:
```
![image](https://github.com/user-attachments/assets/c63d6868-2c58-4b72-b571-2a8733bbca47)

# **Gaussian Mixture Models (GMM):**
Applies GMM for clustering.
```
Output:
```
![image](https://github.com/user-attachments/assets/b05256df-0ff4-432d-96fb-0ca413bd80c5)

# **Spectral Clustering:**
Uses Spectral Clustering to group image pixels.
```
Output:
```
![image](https://github.com/user-attachments/assets/5c9fb4fc-6cda-4655-b4d6-7a175448f485)

# **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):**
Groups pixels into clusters based on density, identifying noise points as outliers, useful for segmenting images with irregular shapes.
```
Output:
```
![image](https://github.com/user-attachments/assets/16aec41d-38ca-42d1-a6b7-be24f8cd67b6)

# **Agglomerative Clustering:**
Performs agglomerative clustering on the image.
```
Output: 
```
![image](https://github.com/user-attachments/assets/72f16a1d-f9ec-4691-a1c3-cb00173b6c80)

# **Affinity Propagation:**
Clusters data by sending messages between data points until convergence, automatically determining the number of clusters, suitable for image segmentation.
```
Output:
```
![image](https://github.com/user-attachments/assets/8686d0f6-3859-4be1-aa4e-db265bccae9b)

# **Image Segmentation by Clustering for k value 3:**
A specific instance of K-means clustering with the number of clusters set to 3, segmenting the image into three distinct regions.
```
Output:
```
![image](https://github.com/user-attachments/assets/e96d49b3-15cf-4563-b52f-295f98f57ba1)

# **Image Segmentation by Clustering for k value 2:**
Applies K-means clustering to segment the image into 2 distinct regions or clusters based on pixel color similarities. This technique simplifies the image into two primary areas, which can be useful for distinguishing between foreground and background or two different objects.
```
Output:
```
![image](https://github.com/user-attachments/assets/e8d02d53-e27c-42a8-9ca8-bf195d9175c0)

# **Finding the Optimal K-value through Elbow Method:**
The Elbow method helps determine the optimal number of clusters (K) for K-means clustering by plotting the sum of squared distances (inertia) from each point to its assigned cluster center. The "elbow" point on the plot indicates the optimal K, where adding more clusters does not significantly improve the clustering performance.
```
Output:
```
![image](https://github.com/user-attachments/assets/d7188ba3-8b4c-4b29-b78c-4d52a78b951d)

# **Image Preprocessing and Optimal K-means Clustering for Segmentation:**
Involves preprocessing the image (e.g., resizing, color space conversion) before applying K-means clustering. The optimal number of clusters (K) is determined using the Elbow method, and K-means clustering is applied with this optimal K to segment the image effectively, resulting in better segmentation performance.
```
Output:
```
![image](https://github.com/user-attachments/assets/2aa606e0-a975-409d-a057-f2e580937c61)

# **Project Structure**

```Code
Image_Clustering/
│
├── Image Clustering.ipynb  # Jupyter Notebook with all image clustering techniques
├── requirements.txt        # List of dependencies
└── README.md               # Project documentation
```
# **Contributing**
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (git checkout -b feature-branch).
3. Commit changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Open a Pull Request.

# **References**

OpenCV Documentation: 
```
https://docs.opencv.org/
```
Matplotlib Documentation: 
```
https://matplotlib.org/stable/contents.html
```
Scikit-Learn Documentation:
```
https://scikit-learn.org/stable/documentation.html
```

## **License**

[MIT](https://choosealicense.com/licenses/mit/)

This project is licensed under the MIT License - see the LICENSE file for details.


## Acknowledgements

 - I would like to express my sincere gratitude to my lecturer, Dr. Agughasi Victor Ikechukwu (https://github.com/Victor-Ikechukwu), for their invaluable guidance and support throughout this project.
 - Their expertise and insights have been instrumental in the successful completion of this project on image clustering techniques using OpenCV and Matplotlib. I am deeply grateful for their encouragement and mentorship.
 - Thank you for providing the knowledge and resources needed to explore and implement various computer vision tasks.
