# Dementia-Detection-with-Activation-Function

The goal of this study was to create a deep learning model that could predict the dementia stage from MRI images by using convolutional neural networks (CNNs). Millions of people worldwide suffer with dementia, a common neurological illness marked by a sharp decrease in cognitive abilities that significantly impairs day-to-day functioning. For prompt intervention and patient care, early and correct diagnosis of dementia stages—including mild cognitive impairment (MCI), Alzheimer's disease (AD), and others—is essential. Because they offer precise anatomical details about the brain, magnetic resonance imaging (MRI) scans are useful for creating predictive models.

The pre-processed MRI scans of people with varying degrees of dementia were used to train the suggested CNN model. To guarantee uniformity over scans, preprocessing included standardizing image resolution, intensity normalization, and anatomical alignment. The CNN architecture leverages both local and global spatial information that is essential for differentiating between dementia stages, enabling it to automatically learn pertinent features from MRI volumes. To maximize model performance while training, supervised learning strategies and deep neural network methodologies were used.
When the created CNN model was evaluated, it showed encouraging results in terms of dementia stage prediction from unseen MRI data. To evaluate the resilience and generalization of the model, quantitative measures including training and validation accuracy and training and validation loss were calculated. The parts of the test image that were taken into consideration during model training were then displayed using an activation function, which allowed the model to be checked for validity. By doing this, it was made sure the model only used the pertinent MRI scan regions for self-training.

Based on normal MRI scans, the results indicate that the CNN-based technique has great potential as a non-invasive tool to support doctors in dementia diagnosis and progression monitoring. Before utilizing this technology for practical healthcare applications, more validation and workflow integration are necessary.

The included code used datasets that were saved in Google Drive, hence the address instead of file name. The user can modify that section and mounting Google Drive onto Collab is unnecessary in cases where the datasets are not in Google Drive.
