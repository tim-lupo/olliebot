# Ollie [Bot]
A Twitter bot that reads and tweets its DMs anonymously

##Installation/Configuration
1) Install pip (https://pip.pypa.io/en/stable/installing/)

2) Type the following into your command prompt
```
pip install twitter
```

3) The Twitter libraries have been installed locally

4) You will need to create an app account on https://dev.twitter.com/apps

> Sign in with your Twitter account

> Create a new app account

> Modify the settings for that app account to allow read & write

> Generate a new OAuth token with those permissions

> Update the credentials in the corresponding spaces in ollie.py
```
consumer_key='[YOUR CONSUMER KEY]',
consumer_secret='[YOUR CONSUMER SECRET]',
token='[YOUR TOKEN]',
token_secret='[YOUR TOKEN SECRET]'
```

4) Installation complete! Now navigate to ollie.py and run it
```
cd [your path to ollie.py]
python ollie.py
```
5) DM the Twitter account associated with your app credentials and voila, it'll tweet your message

##License
Copyright (c) 2016 Tim Lupo

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
