# iOS Build with Python Tests

This repository shows a few Python tests that use the page object model and AltUnityTester to test the Unity endless runner sample:
https://assetstore.unity.com/packages/essentials/tutorial-projects/endless-runner-sample-game-87901

## Running tests

The tests are meant to be run on an iOS device. The app is provided in this repository, in application.ipa.
To start the tests, depending of your OS run:
`./ios_tests.sh`


This script will:

- start the app on your device
- run the tests
- stop the app after the test are done