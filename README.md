Python Sample Code
Setup
pip install -r requirements.txt
Run tests
Run all tests
py.test test
To run them on Sauce Labs, make sure that you have the following environment variables set:

SAUCE_LABS
SAUCE_USERNAME
SAUCE_ACCESS_KEY
Run an arbitrary file
py.test test/test_ios_selectors.py
