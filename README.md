This is our Maven repo.
We host our android SDK versions here.

To check our how you can integrate our sdk into your android app please visit [Matchinguu Gmbh](www.matchinguu.com)

##### Changes with SDK 1.1.0                                   `10 April 2016`


- Use the host app meta data instead of passing the app id and the token as method params
```xml
<meta-data android:name="com.matchinguu.sdk.appId" android:value="@string/matchinguu_app_id" />
<meta-data android:name="com.matchinguu.sdk.appToken" android:value="@string/matchinguu_app_token" />
```
- Fix Internal problem with the authentication token.


##### Changes with SDK 1.0.0                                   `5 April 2016`


- Major change with the sdk in the way the developer integrate the SDK into his app
