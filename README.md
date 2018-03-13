This is **matchinguu** Maven repo.
We host android SDK versions here.

To check our how you can integrate **matchinguu** sdk into your android app please visit [Matchinguu Gmbh](http://www.matchinguu.com)

##### Changes with SDK 1.4.3                                 `14 March 2018`
- Adds Android Oreo 8.0 support.
- Fixed location permission issue.


##### Changes with SDK 1.4.0                                 `24 Novmber 2017`
- Changes in the backend calls
- Add a new api method getToken()

##### Changes with SDK 1.3.8                                 `16 Novmber 2017`
- fix timing in Api retrying mechanism


##### Changes with SDK 1.3                                  `20 July 2017`
- Api  retrying mechanism rewritten.
- Solve problemw with logging

##### Changes with SDK 1.2.6                                  `13 June 2017`
- Fix a problem with progaurd
- More fixes in minor version 1.2.6.3

##### Changes with SDK 1.2.2                                  `10 June 2017`
- Fix a problem with the SDK start utility

##### Changes with SDK 1.2.0                                  `09 June 2017`
- Securing the SDK
- Showing http logs while debugging
- Updating the documentation with Progaurd Section

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
