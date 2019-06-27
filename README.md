# Phone-Authentication-Flutter



We will be using a plugin called firebase_auth which provides methods for authentication using Google account and phone number. Since this is a firebase project, before you proceed, please make sure you have configured your Flutter project to use Firebase (basically create a Firebase project).


It is important to run through our use case of how the basic idea of authentication with sms code is going to work:

1. The user keys in his/her phone number.
2. The user then confirms the phone number inputted.
3. The app sends sms code to the phone.
4. The user inputs the received sms code in the app.
5. The app validates the inputted code.
