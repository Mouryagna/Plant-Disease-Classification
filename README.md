# Plant-Disease-Classification
Plant Disease Classification

plant-disease-classification-cnn
│
├── .venv/                  # Python virtual environment (not pushed to GitHub)
│
├── data/                   # Dataset folder
│   ├── train/              # Training images
│   ├── validation/         # Validation images
│   └── test/               # Testing images
│
├── notebooks/              # Jupyter notebooks for experiments
│   └── cnn_training.ipynb
│
├── src/                    # Core source code
│   ├── data_preprocessing.py
│   ├── train_model.py
│   ├── evaluate_model.py
│   └── predict.py
│
├── models/                 # Saved trained models
│   └── plant_disease_model.h5
│
├── app/                    # Optional web app
│   └── streamlit_app.py
│
├── requirements.txt        # Project dependencies
├── setup.py                # Package setup
├── .gitignore              # Files ignored by Git
└── README.md               # Project documentation