mitigation_reconstruction_attack/
│
├── CheXpert-v1.0-small/
│   ├── CheXpert-v1.0-small/
│   │   ├── valid/                              # Validation images directory
│   │   ├── train/                              # Training images directory
│   ├── valid.csv                               # Validation metadata
│   └── train.csv                               # Training metadata
│
├── models/
│   ├── resnet.py              # Standard ResNet model
│   ├── resnet_dp.py           # ResNet model with Differential Privacy integration
│
├── results/
│   ├── models/                # Saved federated models
│   ├── client_gradients/      # Gradients saved for analysis
│   ├── attacks/               # Results from reconstruction attacks
│   ├── plots/                 # Visualizations (PSNR, AUC-ROC, etc.)
│   └── logs/                  # Logs for debugging and tracking
│
├── notebooks/
│   ├── 01_data_exploration.ipynb         # Data exploration and preprocessing
│   ├── 02_data_pre_FL_train.ipynb        # Federated Learning training
│   ├── 03_dp_privacy.ipynb               # Differential privacy experiments
│   └── 04_reconstruction_attack.ipynb    # Reconstruction attack analysis
│
├── README.md                              # Project overview and instructions



this is the structure of the project.Since dataset is two large .download from the kaggle website and assign each file in the data set as per the structure of the project above.
