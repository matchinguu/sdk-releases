This is **matchinguu** Maven repo.
We host android SDK versions here.

To check our how you can integrate **matchinguu** sdk into your android app please visit [Matchinguu Gmbh](http://www.matchinguu.com)

##### Changes with SDK 1.1.8                                  `01 June 2017`

- Solve a problem with the checking service


##### Changes with SDK 1.1.6                                   `29 May 2017`

- Solve two problems with the main service



##### Changes with SDK 1.1.5                                   `11 May 2017`

- Change **setLocationBasedServices** to be called from the instance.
- Enhance the connectivity check in the api calls to handle connectivity changes.
- Add method **switchImprovedLocationPositioning** to enhance the location positioning,
  you need to contact **matchinguu** to enable this feature.


##### Changes with SDK 1.1.4                                   `8 May 2017`

- Solve problem with cache

##### Changes with SDK 1.1.3                                   `2 May 2017`

- Add the package info to the broadcasted intents
- Add a method to get **matchinguu** client Id in sake of debugging
- More logging

##### Changes with SDK 1.1.2                                   `26 April 2017`

- Fix problem with request caching
- handle 400 errors


##### Changes with SDK 1.1.0                                   `10 April 2017`

- Use the host app meta data instead of passing the app id and the token as method params
```xml
<meta-data android:name="com.matchinguu.sdk.appId" android:value="@string/matchinguu_app_id" />
<meta-data android:name="com.matchinguu.sdk.appToken" android:value="@string/matchinguu_app_token" />
```
- Fix Internal problem with the authentication token.


##### Changes with SDK 1.0.0                                   `5 April 2017`

- Major change with the sdk in the way the developer integrate the SDK into his app
