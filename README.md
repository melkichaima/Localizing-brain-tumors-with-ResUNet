# Localizing-brain-tumors-with-ResUNet

This repository contains Python code for a brain tumor localization project. The model is trained on the MRI scans dataset ,using ResNet and ResUNet and Transfer Learning.

## Dataset

The MRI scans dataset used for training and evaluation can be downloaded from the following link: (https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation). It consists of Brain MRI images together with manual FLAIR abnormality segmentation masks.

## Model Architecture

The model architecture used is based on deep learning techniques. The specific architecture details are mentioned in the code.


## Usage

1. Clone this repository to your local machine:

```shell
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

2. Download the Brain MRI segmentation dataset from the provided link and place it in the appropriate directory.

3. Use the provided code to train and detection where there is a tumor or not (using ResNet).

4. if there is a tumor, the model will localize precisely the actual tumor using ResUNet.
   



## Results

The provided model, trained on the Brain MRI segmentation dataset, can accurately localize the tumor of the patient. The code can be further customized or improved to enhance the performance.

## Acknowledgments

- The MRI scans dataset used in this project was sourced from Kaggle: [Brain MRI segmentation](https://www.kaggle.com/datasets/mateuszbuda/lgg-mri-segmentation).

## License

This project is licensed under the [MIT License](LICENSE).
