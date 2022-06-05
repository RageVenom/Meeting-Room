# Meeting-Zone
Meeting Zone is flutter based chatting app used for either personal or public while sharing room id &amp; password. It's data is secured on firebase.


![ss](https://user-images.githubusercontent.com/55954636/172061421-15cf98e8-cc5e-41bf-a917-76d8aaef9470.PNG)

![ate](https://user-images.githubusercontent.com/55954636/172061411-4ea78426-ca0f-406c-a565-441df9d85f19.PNG)



## Note

The file `lib/utility/sensitive_constants.dart` is intentionally omitted from pushing to GitHub.

`sensitive_constants.dart` contains a password of length 32, stored by the developer, which is used in combination with the **user provided** password to generate a strong password combination, which is finally used for encryption.

Basically just to add a layer of security, in case the user password is very easy to guess.

The content of `sensitive_constants.dart` is as follows:
`const developerKey = '<here-goes-your-long-developer-password>';`
