# BreakingBias
 IITK Consulting Group's Public brawl detection contest


1.Install the necessary libraries

2.Features are extracted using ResNet 50 so if you run all the code 
again it may take time. For extracted features of videos use link provided below.

3.Lstm is choosen for the model and we saved optimal weights of model 
with file name best_lstm_model.pth in the folder.

4.For final running  you just have to take best_lstm_model.pth , features_combined.npy and labels_combined.npy , test_features.npy from the folder and run last cell in ipynb file.

5.To get the video file names we have run command which takes video numbers from google drive and add those numbers in csv file. So please ensure test_videos are uploaded in your drive and give that link in first line of last cell to get the cell run.

Folder Link : https://drive.google.com/drive/folders/1yPY_9mM5095tqWnGWsZ2_uxrPLn3isoQ
