# Cancer detect Neural Network Project

### Project Description
#### CNN Cancer Detection Kaggle Mini-Project

##### Step 1: Brief description of the problem and data
Our goal is to try to accurately identify metastatic cancer in small image patches taken from larger digital pathology scans.  This is a binary clasification problem, which we will attempt to use Convolutional Neural Networks to solve.

We are using the histopathologic-cancer-detection database from Kaggle.  It has approximately 277k individual images, split into test and validation groups, with a train_labels file which indicates 0 for benign and 1 which indicates that the center 32x32px region of a patch contains at least one pixel of tumor tissue. Tumor tissue in the outer region of the patch does not influence the label. This outer region is provided to enable fully-convolutional models that do not use zero-padding, to ensure consistent behavior when applied to a whole-slide image.  Duplicates have been removed.  (Source: Kaggle)
