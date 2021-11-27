# SMS_Spam_Classifier


This is the dataset taken from kaggle
https://www.kaggle.com/uciml/sms-spam-collection-dataset


The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.


# To get the app working locally:

1. Clone or download the repository locally.

2. Within the SMS_Spam_Classifier directory, create a virtual Python environment with the Terminal command 
```
python -m venv spamclf 
```
where sentiment is the name of your environment. You can choose any name.

3. Activate the virtual environment with the command 
```
   flaskapp\scripts\activate.bat
```
 
4. Then run the command 
```
pip install -r requirements.txt 
```

5. Once all the requirements have been installed then please do run streamlit app.
```
streamlit run app.py
```
6. You will be redirected to the link and then do try the spam message!
```
http://localhost:8501/
```










# Acknowledgements
The original dataset can be found here. The creators would like to note that in case you find the dataset useful, please make a reference to previous paper and the web page: http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/ in your papers, research, etc.

We offer a comprehensive study of this corpus in the following paper. This work presents a number of statistics, studies and baseline results for several machine learning methods.

Almeida, T.A., GÃ³mez Hidalgo, J.M., Yamakami, A. Contributions to the Study of SMS Spam Filtering: New Collection and Results. Proceedings of the 2011 ACM Symposium on Document Engineering (DOCENG'11), Mountain View, CA, USA, 2011.
