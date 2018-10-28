# PayFlow

[Visit our website](http://www.andreasglordos.wixsite.com/payflow)

For judges: you can test our app. Send "Hello" to 99795260 and follow the instructions to register. For the boc credentials, use username: 999999 and password: "112233" (without quotes). After registering, you can generate a code to receive money by sending "I want my friend to send me 20 euros." or anything similar. Give that code to the friend who owes you 20 euros, and tell them to send it to  99795260 after they also complete the registration process. (note: Registration is a one-time process). 

Judges: To find our code in regards to the response server, go to PayFlow/application/views.py

Forget ATMs. You can now conduct any payment, to anyone, from anywhere at any time using PayFlow.

PayFlow uses SMS to transfer funds from your accounts to the accounts of merchants, family or friends. It's easy to use, easy to set up and will make your life much easier.

# Installation/Usage

### Note: this has only been tested on Windows.

1. [Install Python 3.5](https://www.python.org/downloads/release/python-350/) if you don't have it already

2. pip install django

3. Download this repository and unzip it.

4. Open up cmd. Navigate to the repository you downloaded and go to the Payflow folder, where you can find manage.py. Execute the command python manage.py runserver

5. A message should appear on the cmd with the IP of your web server. It should look like this: 127.0.0.1:xxxx/ . Note down the four digits at the end.

6. Open an instance of a Git Bash terminal. Type the command ssh -R 80:localhost:xxxx serveo.net, where xxxx are the 4 digits you noted down in Step 5.

7. Note down the URL received from the step above.

8. Go to http://www.telerivet.com and click on "Get Started" on the top right. Sign up and go through the first two steps of their signup process (ignore the 3rd step, "Set up your messaging services or campaigns"). Make sure to download and configure the Android app as explained in the setup process of Telerivet.

9. On the telerivet dashboard, click Services on the left. Click on Webhook API. Go through the set up process. Copy down your Webhook secret, and put the URL you received in step 7 as your Webhook URL.

10. Download
