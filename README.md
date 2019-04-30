# react-native-firebase-phone-auth
A solution for using firebase phone auth in react-native


# How It Works
As you know firebase phone-auth required a valid captcha as the second argument in its function signInWithPhoneNumber(phone_number, captchaVerifier). so in that example we tried to verify captcha in a WebView then passed captcha token to our app and build a fake captchaVerifier.


# Installation guide
- ``git clone https://github.com/boudlal/react-native-firebase-phone-auth.git``
- ``yarn install`` or ``npm Install``
- Add your firebase config into App.js and Captcha.html
- Deploy Captcha.html in a server.
- Add your Captcha.html domain in the authorized domain section in the firebase console
- Run ``react-native run-android`` or ``react-native run-ios`` and enjoy.
