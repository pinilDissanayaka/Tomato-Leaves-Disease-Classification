# Tomato-Leaves-Disease-Classification

## Tomato Leaf Disease Classification
Over 20k images of tomato leaves with 10 diseases and 1 healthy class. Images are collected from both lab scenes and in-the-wild scenes. The goal is to develop a lightweight model that can predict tomato leaf disease & deploy it offline on a mobile app.

## Classes:
- Late_blight
- healthy
- Early_blight
- Septoria_leaf_spot
- Tomato_Yellow_Leaf_Curl_Virus
- Bacterial_spot
- Target_Spot
- Tomato_mosaic_virus
- Leaf_Mold
- Spider_mites Two-spotted_spider_mite
- Powdery Mildew

The original source of most of the images is the PlantVillage dataset published [here](https://data.mendeley.com/datasets/ngdgg79rzb/1) and [here](https://data.mendeley.com/datasets/tywbtsjrjv/1). The data has been augmented offline using multiple advanced techniques like image flipping, Gamma correction, noise injection, PCA color augmentation, rotation, and scaling. Some recent images were generated offline with GANs. The subset of images containing Taiwan tomato leaves was augmented using rotations at multiple angles, mirroring, reducing image brightness, etc.
