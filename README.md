✍️ Signature Matching with Computer Vision
This project implements a signature verification system using computer vision techniques to compare and match handwritten signatures based on their visual features.

📌 Features
Preprocessing of signature images: resizing, grayscale conversion, and noise reduction.

Feature extraction using contour detection, pixel-based similarity, or deep learning embeddings.

Signature comparison using similarity metrics such as Structural Similarity Index (SSIM), Mean Squared Error (MSE), or cosine similarity.

Visualization of matching results for verification.

📁 Dataset
Pairs of signature images for comparison (genuine vs. forged).

Example file structure:

Signatures/
├── genuine/
│   └── person1_sig1.png
├── forged/
│   └── person1_forg1.png

🚀 How to Use
Open SignatureMatching.ipynb in Jupyter or Google Colab.

Run the notebook to:

Load and preprocess the images.

Extract and compare visual features.

Display similarity scores and matching outcomes.

🛠️ Requirements
Python 3.x

OpenCV

NumPy

Matplotlib

scikit-image (for SSIM)

📊 Outputs
Similarity scores between pairs of signatures.

Side-by-side visual comparisons with classification as "match" or "no match".

📓 Notebook
The notebook SignatureMatching.ipynb contains all the steps from preprocessing to result visualization and evaluation.
