# Connect to Kaggle

Whenever we use a dataset from Kaggle, we load it directly using the Kaggle API.

## Steps to Load a Kaggle Dataset

To load any Kaggle dataset, follow these steps:

### 1. Download Kaggle's Beta API
Ensure you have downloaded Kaggle's beta API. You also need to accept the Kaggle competition rules for the specific dataset or competition you want to access.

### 2. Get Kaggle API Credentials
1. Go to your Kaggle account settings.
2. Scroll to the **API** section.
3. Click on **Create New API Token**. This will download a `kaggle.json` file containing your Kaggle API credentials.

### 3. Upload Kaggle Credentials to Colab
To use the Kaggle API in Google Colab, upload the `kaggle.json` file to your Colab environment.
