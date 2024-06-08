My scores were the following:

I split the data into 80% training and 20% testing, with C = 2 and gamma = 1.0 in all cases.

              precision    recall  f1-score   support

           0       0.85      0.95      0.90       546
           1       0.91      0.76      0.83       375

    accuracy                           0.87       921
   macro avg       0.88      0.85      0.86       921
weighted avg       0.88      0.87      0.87       921

And when I splitted the data as 70% training and 30% testing 

Those were the scores 

              precision    recall  f1-score   support

           0       0.83      0.94      0.88       811
           1       0.89      0.73      0.81       570

    accuracy                           0.85      1381
   macro avg       0.86      0.84      0.84      1381
weighted avg       0.86      0.85      0.85      1381

I didn't see any difference with changing the C with gamma; in my case, the only difference was the splitting of the data.


i tried to study the features that's why i chsose these features that i thought are important:


word_freq_address
word_freq_free
word_freq_email
word_freq_money            
word_freq_order
word_freq_credit
word_freq_meeting
char_freq_$           
char_freq_#

