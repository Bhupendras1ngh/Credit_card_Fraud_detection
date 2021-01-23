# Credit_card_Fraud_detection
Basically this is a problem of Classification  and can be solved by Logistic regresion, Decision Tree , random_Forest , etc algoritms but dueto presence of imbalanaced dataset , we are not supposed to use there algorithms because this might result in highly bias outcome
Therefore I chose Artificial Neural Network(ANN) , because in this we can assign weights for reducing the degree of biasness in result 
firstly i Import tensorflow library , and in this problem i  used tensorflow 2 because it cantain inbuild Keras library also 
then i import libraryies like numy , pandas , matplotlib.pyplot.
Also import classes like models , Sequential 
Build ANN model with 2 hidden layers 
Since i used sigmoid funcion in output layer , thats why i got probabiity of being fraud,  od by using IF caondition convert it into bool
Fit X_train , Y_train  and predict accuracy
but since our data is imbalanced  thatswhy we have to assigned the vaue of weight
so after assigning weight our accuracy decrease a little bit 
and at last by using confuison matrix , and accuracy_score we find our final accuracy which is approimately equals to 99%
