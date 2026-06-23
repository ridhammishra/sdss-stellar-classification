# sdss-stellar-classification
End-to-end machine learning project on the SDSS dataset for classifying Stars, Galaxies, and QSOs. Features data preprocessing, color-index feature engineering, K-Means clustering, and a custom PyTorch neural network with CUDA support, achieving 97% test accuracy.

### 1. Clone the Repository

```bash
git clone https://github.com/ridhammishra/sdss-stellar-classification.git
cd sdss-stellar-classification
```

### 2. Install Dependencies

Run the pip install cell in jupyter notebook to install all liberaries used in project

### 3. Workflow

The notebook follows the complete machine learning pipeline:

- 📊 Data Exploration & Preprocessing
- 🧹 Sentinel Value Handling
- 🔬 Feature Engineering
- 📈 Exploratory Data Analysis (EDA)
- 🎯 K-Means Clustering
- 🧠 Neural Network Training (PyTorch)
- 📊 Model Evaluation
- 💾 Model Saving (`.pth`)

### 4. Using the Trained Model

The trained model is saved as a `.pth` file and can be loaded directly for inference without retraining the network.
