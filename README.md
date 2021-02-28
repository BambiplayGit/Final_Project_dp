# Final_Project_dp
Guide of using this project: <br>
Jupyternotes are in src. <br>
Model is saved in model. <br>
Datasets are in amazon data <br>

How to install: <br>
1.Open the src folder. <br>

2.open final_project_train_Hongyu_Song.ipynb and run the cells in order if the relative path in the code works. <br>

3.If the relative path in the code does not work, do as follows. <br>
If you are using Colab, please upload the whole folder to your google drive. And run the first cell. <br>
If you are not using Colab, just Comment out the first cell！ <br>

4.Replace the path in this line with the path of Musical_instruments_reviews.csv in the dataset_amazon folder. <br>
data_raw = pd.read_csv('/content/drive/MyDrive/Final_project/dataset_amazon/Musical_instruments_reviews.csv') <br>

5.run the cells in order. <br>

6.replace the path in this line with the path you save your model. <br>
model.save('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5') <br>

7.copy the path in 6 to this line. <br>
model = load_model('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5') <br>

8.open final_project_test_Hongyu_Song to check the model's performance on the test set.If you are not using Colab, just Comment out the first cell！ <br>

9.Replace the path in this line with the path of fuzzydataset.csv in the dataset_amazon folder. <br>
data_raw = pd.read_csv('/content/drive/MyDrive/Final_project/dataset_amazon/fuzzydataset.csv') <br>

10.copy the path in 6 to this line. <br>
model = load_model('/content/drive/MyDrive/Final_project/model/Amazon_Instru_Sentiment_Analy.h5') <br>

Thank you for your comprehension! <br>
