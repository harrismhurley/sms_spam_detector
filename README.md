# sms_spam_detectorRequirements

## Create the SMS Classification Function (50 points)
- The features variable is set equal to the text message column of the DataFrame. (8 points)
- The target variable is set equal to the "label" column of the DataFrame. (8 points)
- The data is split into training and testing sets, and the test_size is set to 33%. (8 points)
- A Pipeline is built using the TfidfVectorizer and LinearSVC to transform the test set and compare it to the training set. (8 points)
- The model is fitted to the transformed training data and the model is returned. (8 points)
- The SMSSpamCollection.csv is read into a DataFrame. (5 points)
- The DataFrame is passed to the sms_classification function and the result is set equal to the "text_clf" variable. (5 points)


## Create the SMS Prediction Function (30 points)
- A variable that holds the prediction of a new text is created. (8 points)
- A conditional statement that determines if the text message is "ham" or “spam” is created. (12 points)
- The conditional returns a message if the text is “ham”. (5 points)
- The conditional returns a message if the text is “spam”. (5 points)

## Create the Gradio Interface Application (20 points)
- A Gradio Interface application is created with three parameters for the “function”, “outputs”, and “inputs”. (6 points)
- The “outputs” parameter is a textbox that contains a label to let the user know what to type in the box. (4 points)
- The “inputs” parameter is a textbox that contains a label to let the user know that the prediction will be displayed in the textbox. (4 points)
- The Interface application can be shared with other users with a public URL. (2 points)
- The Gradio Interface works as expected and there are no errors after a user submits a text message. (4 points)

