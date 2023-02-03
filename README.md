# 6060_GitHub_CA2

The purpose of this assignment is to run the Naive Bias algorithm and comment on the coding process. Some of the code was already given to me, so my main task was spent understanding and commenting on the code that is required to run the algorithm. 

I imported necessary libraries in order to run the code, created a function called make_Dictionary that splits each email into "words". An empty list is created, then using a for loop, each individual word goes into the list. Using another for loop, we drop each word that is alpha, and drop all single character words. I created a function called extract_features that ultimately builds a list of words from the train set and converts the list to a Dictionary of unique words with a frequency count. Then, a for loop puts each word from the train set into the features_matrix and counts the frequency of each word in the files. I entered the "path" of my "train_mails" and "test-mails" folders and ran the emails through the functions created earlier. Once all the data was ready, I ran it through the Gaussian Naive Bias algorithm and predicted the accuracy score. 

To view this assignment, download the 6070_CA_02.ipynb file and upload it to JupyterLab or GoogleColab. To upload the file, go to the file icon on either JupyterLab or GoogleColab and press the Upload arrow icon. Select the 6070_CA_01.ipynb file that you had previously downloaded and upload it. If on GoogleColab, go to the File tab to the right of the CO orange symbol, go to Open Notebook, go to Upload, and select the 6070_CA_01.ipynb file. If on JupyterLab, double click that file and see it pop up. Click either Run or Runtime and Run All Cells to run all of the code. Scroll from top to bottom to see how to run the Gauusina Naive Bias algorithm. I have embetted comments and explanations within the code so that it is more easily understood to the viewer.
