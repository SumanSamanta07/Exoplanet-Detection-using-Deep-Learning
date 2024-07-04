# Exoplanet-Detection-using-Deep-Learning

This is a project on detecting exoplanets using various neural network models. The dataset used in this project is the Exoplanet Hunting Dataset, which includes data from the Kepler space telescope. The code demonstrates data preprocessing, resampling, model building, training, and evaluation.

Overview:

The goal of this project is to build and evaluate several neural network models for exoplanet classification. The models used include Convolutional Neural Networks (CNN), Fully Convolutional Networks (FCN), Time-based CNN. The project also explores different resampling techniques such as SMOTE (Synthetic Minority Over-sampling Technique) and ADASYN (Adaptive Synthetic) combined with One-Sided Selection (OSS) to handle class imbalance.

Libraries Used:

  ~pandas
  ~numpy
  ~seaborn
  ~matplotlib
  ~scikit-learn
  ~imbalanced-learn
  ~tensorflow
  ~keras
  
Resampling:

To address class imbalance, the following resampling techniques are applied:

SMOTE + OSS,
ADASYN + OSS.
Resampling helps in creating a more balanced dataset, which is crucial for training accurate models.

Model Architecture:

The repository includes the following neural network models:

Convolutional Neural Network (CNN): A simple CNN with two convolutional layers followed by max pooling, dropout, and dense layers.
Fully Convolutional Network (FCN): A network with three convolutional layers, batch normalization, and global average pooling.
Time-based CNN (Time-CNN): A CNN with three convolutional layers, batch normalization, max pooling, and dropout.
Residual Network (ResNet): A ResNet with residual blocks and global average pooling.
