# capstone-project

This capstone project requires the following directory structure to work:

capstone-project
| - nlp_models
| - output_nlp
| - output_20k_150_epoch

You need to follow the below steps:

1. Navigate to the directoy "nlp_models" and download the saved model from the Google Drive link to save the pre-trained NLP models.
Link: https://drive.google.com/drive/folders/10D3rwokvrY7p-x1cOoml4gGJ1dibPxTv?usp=sharing

2. Navigate to the directoy "output_nlp" and download the saved model from the Google Drive link to save the custom NLP models.
Link: https://drive.google.com/drive/folders/1qQ1E7FYUXeZ6VD02Re4V_a1lTInJsTdX?usp=sharing

3. Navigate to the directoy "output_20k_150_epoch" and download the saved model from the Google Drive link to save the image captioning model.
Link: https://drive.google.com/drive/folders/1QtOHkC4xqTo2aciTBuwUWeoRSLNxKDd6?usp=sharing


Depending on the task that you wish to fulfuill, you may use the below files:

1. Run Pair-Up system to check if image and text pairing form a congruous pair or not.
File: image_captioning_load_model_text_similarity_v3.ipynb


The below tasks are optional and is only needed if you want to re-train the models from scratch.
2. Train and save the image captioning model from scratch
File: image_captioning_3_model_train_test_mscoco2014_20k_data_150_epoch.ipynb

3. Train and save the custom NLP model A from scratch
File: sentence_similarity_custom_model_A_v1.ipynb

4. Train and save the custom NLP model B from scratch
File: sentence_similarity_custom_model_B_v2.ipynb

Please find the following link to watch the demo of the Project:  
https://youtu.be/T8ERQSHr8LQ
