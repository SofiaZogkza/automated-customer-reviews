# PROJECT: Automated Customer Reviews

This project analyzes Amazon product reviews using datasets from Kaggle’s Consumer Reviews of Amazon Products: `https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products/data` .
Because the dataset is large, it is not included in the repository — you will download it locally using the Kaggle API.

## — Setup Guide

 ### ⚙️ 1. Clone the Repository

 ### 🧩 2. Create and Activate a Virtual Environment

 Replace the `venv_name` with the name you will give to the environment

```
python -m venv venv_name
source venv_name/bin/activate  # macOS/Linux
# OR
venv_name\Scripts\activate
```

### 📦 3. Install Requirements (packages)

```
pip install -r requirements.txt
```

### 🔐 4. Add Kaggle API Credentials

You’ll need a Kaggle API token to download the dataset.

1. Go to your Kaggle account → Account Settings.

2. Click Create New API Token
   This downloads a file called `kaggle.json`.

3. Open `kaggle.json` and copy its contents into a `.env` file at the root of your project:

```
KAGGLE_USERNAME=your_kaggle_username
KAGGLE_KEY=your_kaggle_api_key
```

### 5. Download the Dataset
You can downlaod the dataset by running the respective code snippet inside the main.ipynb notebook.
