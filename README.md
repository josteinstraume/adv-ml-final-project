# adv-ml-final-project
Stock Market Movement Prediction with LSTM Neural Networks.
How to run the code:
1. Open Jupyter Notebook in Google Colab
2. Upload data contained in this repo to your Google Drive
3. Edit data file paths to correspond with your Google Drive
4. Pretrained models are saved as zip folders in the Models folder of this repo.
    You can "restore" the saved models via the Talos API restore function.
    For example:
    from talos import Restore
    restored_model = Restore('/content/deployed_model_3.zip')
