# sms_spam_detector

I am refactoring code from an SMS text classification solution into a function that constructs a linear Support Vector Classification (SVC) model. Once the model is created and trained, I have create a Gradio app to host the application, enabling users to test text messages. The application will provide feedback to users, indicating whether the text is classified as spam or not, based on the model's performance.

I have created a SMS Classification Function

I have created a SMS Prediction Function

I have then created the Gradio Interface Application and the results are as follows. 

These are the results of of the SMS Spam classification App

The text message: "You are a lucky winner of $5000!", is not spam.

The text message: "You won 2 free tickets to the Super Bowl.", is not spam.

The text message: "You won 2 free tickets to the Super Bowl text us to claim your prize.", is spam.

The text message: "Thanks for registering. Text 4343 to receive free updates on medicare.", is spam.


![Gradio Model](GradioApp.png)
