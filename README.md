# Leukocyte-classification
Using deep learning (in keras) to classify leukocytes in the 4 most common classes (Eosinophil, Lymphocyte, Monocyte, Neutrophil). Basophils were excluded for being much less frequent.
Originally based on [this work](https://github.com/dhruvp/wbc-classification), whose main objective is a binary classification. In my work I'm trying a multi-class classification.

# Dataset
358 images of Eosinophils, Lymphocytes, Monocytes and Neutrophils, unequally distributed. Data Augmentation used to get 10000 on folder training examples. 152 images of leukocytes augmented to 1600 to use as validation set. I segmented the original images with Gimp2.

# Purpose
Find the best architectures (and parameters) to classify the leukocytes.

(to be updated)
