# Stress management app tester guide
Hi tester, you have been selected to test our stress management app. We want you to read this guide before you start using the app, as there are some information we are using that you have to be aware of.

### Preliminary information

The system may be using machine learning to analyze all answers to questions that you give to the system, and everything will be logged such that it is accessible to our group to make our final analysis after the tests with. This means that you have to be aware of whether you want to share personal information with the app, data transfer is encrypted so we can ensure that its only the project group and you that will be aware of what you have answered.

Despite the previous notice, please if possible provide as detailed a description as possible in your responses. It will help our machine learning model understand your answer.

Due to time constraints, we have encountered an issue where your password is possible to find for us at the server through log files. We do not have time to address this issue, so please do not use a very critical personal password for your user on our system.

If you would like to be anonymous, feel free to use a username that we cannot recognize you by. Our main goal is to obtain data, not to link it to the testers afterwards.

## Setup
You will receive an APK file for your android phone, please install this application on your device and launch it.

To install a third party APK file, follow these steps:
* Enable unknown applications (usually under Settings > Security in settings)
* Download the APK file to your device
* Click on the file in your file browser and click install

It will be required to have an internet connection to participate in the tests

You will be presented with a login/register page, please click register and specify a username and password, **Please don't use a critical password**.

After creating your login, fill out the following form with user data, we need this to generate a set of tags to curate later questions to you.
* DO NOT ABORT THIS PROCESS! - If you do, the user becomes unusable and you will have to make a new user.

When you have finished the registration form, you should be set up with an empty account, ready for the test.

## The app
The main functionality of the app consists of 4 pages, the homepage and settings page is not finished and as such not particularly important. The 2nd and 3rd page has the following functionality:

* Journals: The daily journal page, you can fill it out as often as you want, but ideally at least once a day. It be based on your tags and give you curated questions. This functionality isn't perfect as our set of questions is quite small, so don't be surprised if you get presented with a generic question, as that question might have been tagged with "Default"

* Predictions: This is where your journals will be aggregated and analyzed to present you with a prediction of your future stress. you will see a button to create a prediction, a chart of your historical data and a button to rate your most recent prediction.

## Usage
We require around 3 days of roughly 5 minutes each, where we want you to fill out a journal at least once a day.
* Navigate to the second page of the app, and fill out the questions you will be presented with.

After you have created 3 or more journals, generate a prediction and follow the prompts on screen
* Navigate to the third page of the app, and press "new prediction", fill out your expected stress level and press continue, after the prediction has been made, click the rate prediction button at the bottom of the predictions page.

If you choose to keep using the app after 3 days have passed, please make a prediction following every new journal. The more you make the more accurate our data becomes for our final analysis.

## After you finish our test
Please fill out the following questions and send your answer to us at: <a href="mailto://cs-24-sw-8-11@student.aau.dk">cs-24-sw-8-11@student.aau.dk</a>

1. Your username

2. How usable was the app? any improvements to the UI?

3. How accurate was the prediction(s)? did you feel the prediction trended in the correct direction?

4. How useful was the mitigation strategy that was presented to you after your prediction?

5. Other feedback?
