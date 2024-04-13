In this project, I refactored the code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. In order to refactor the code, I did the following

1) I set the features variable to the text message column of the DataFrame.
2) I set the target variable to the "label" column of the DataFrame.
3) I split data into training and testing and set the test_size to 33%.
4) I bulit a pipeline to transform the test set to compare to the training set.
5) I fit the model to the transformed training data and return model.

Once I created the model and trained it, I created a Gradio app to host the application. This gave users the ability to test text messages. 

The Gradio app provides feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

The solutions was written in Python. It can run on either Google colab, Jupyter Notebook or Visual Studio Code.

