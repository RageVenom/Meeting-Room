# Meeting-Zone

An E2EE messaging application using Flutter and Firebase.

## Note

The file `lib/utility/sensitive_constants.dart` is intentionally omitted from pushing to GitHub.

`sensitive_constants.dart` contains a password of length 32, stored by the developer, which is used in combination with the **user provided** password to generate a strong password combination, which is finally used for encryption.

Basically just to add a layer of security, in case the user password is very easy to guess.

The content of `sensitive_constants.dart` is as follows:
`const developerKey = '<here-goes-your-long-developer-password>';`
