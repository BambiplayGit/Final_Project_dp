# Final_Project_dp
Guide of using this project:
Jupyternotes are in src.
Model is saved in model.
Datasets are in amazon data

1.Open the src folder.
2.open final_project_train_Hongyu_Song.ipynb and run the cells in order if the relative path in the code works.
3.If the relative path in the code does not work, do as follows.
If you are using Colab, please upload the whole folder to your google drive. And run the first cell.
If you are not using Colab, just Comment out the first cell！
4.Replace the path in this line with the path of Musical_instruments_reviews.csv in the dataset_amazon folder.
data_raw = pd.read_csv('/content/drive/MyDrive/Final_project/dataset_amazon/Musical_instruments_reviews.csv')
5.run the cells in order.
6.replace the path in this line with the path you save your model.
model.save('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5')
7.copy the path in 6 to this line.
model = load_model('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5')
8.open final_project_test_Hongyu_Song to check the model's performance on the test set.If you are not using Colab, just Comment out the first cell！
9.Replace the path in this line with the path of fuzzydataset.csv in the dataset_amazon folder.
data_raw = pd.read_csv('/content/drive/MyDrive/Final_project/dataset_amazon/fuzzydataset.csv')
10.copy the path in 6 to this line.
model = load_model('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5')

Thank you for your comprehension!
