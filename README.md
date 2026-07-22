# End-to-End Laptop Price Prediction ML Project 💻

A production-grade machine learning system designed to robustly predict laptop prices based on various hardware specifications and features. This project features a modular pipeline architecture for training and inference, integrated with a clean web interface for easy interaction.

## 🚀 Key Features

- **Advanced ML Pipeline**: Modular design separating data ingestion, data transformation, and model training.
- **Model Evaluation**: Built-in scripts to train, validate, and check model performance and checkpoint loading.
- **Interactive Web UI**: Built with Flask/FastAPI for real-time laptop price predictions.
- **Robust Architecture**: Complete separation of source scripts, configuration files, and saved artifacts.
- **Automated Logging**: Comprehensive logging to track execution metrics and debugging.

## 🛠️ Tech Stack

- **Language**: Python 3.10+
- **Frontend / Web Framework**: Flask / FastAPI (`app.py`)
- **ML & Data Processing**: Scikit-Learn, Pandas, NumPy
- **Environment Management**: Python Virtual Environment (`venv`)

## ⚙️ Project Structure

```text
├── .vscode/               # VS Code configuration settings
├── artifacts/             # Saved model artifacts, transformers, and preprocessed data
├── laptop_price/          # Source package containing core ML pipeline scripts
├── logs/                  # Application and execution logs
├── prediction/models/     # Trained ML models and checkpoint files
├── venv/                  # Python virtual environment
├── .env                   # Environment variables configuration
├── app.py                 # Flask/FastAPI web application entry point
├── check_model.py         # Utility script to verify model loading and predictions
├── main.py                # Main orchestration pipeline script
└── requirements.txt       # Project dependencies
