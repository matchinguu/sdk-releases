This is Matchinguu Maven repo.
We host android SDK versions here.

To check our how you can integrate matchinguu sdk into your android app please visit [Matchinguu Gmbh](http://www.matchinguu.com)

##### Changes with SDK 1.1.3                                   `2 May 2016`

- Add the package info to the broadcasted intents
- Add a method to get matchinguu client Id in sake of debugging
- More logging

##### Changes with SDK 1.1.2                                   `26 April 2016`

- Fix problem with request caching
- handle 400 errors


##### Changes with SDK 1.1.0                                   `10 April 2016`

- Use the host app meta data instead of passing the app id and the token as method params
```xml
<meta-data android:name="com.matchinguu.sdk.appId" android:value="@string/matchinguu_app_id" />
<meta-data android:name="com.matchinguu.sdk.appToken" android:value="@string/matchinguu_app_token" />
```
- Fix Internal problem with the authentication token.


##### Changes with SDK 1.0.0                                   `5 April 2016`

- Major change with the sdk in the way the developer integrate the SDK into his app
