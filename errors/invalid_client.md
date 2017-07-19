### invalid_client
This error occurs when there is a problem validating an application’s credentials. 

**Possible causes** 
* The authorization code presented is invalid or was issued to a different tenant.
* The client secret provided is invalid.
* The clientID provided is invalid.
* The client assertion was signed using a key not defined on the application.
* The username or password a user tried using is invalid.

**What to do**

Check your application’s code and verify your clientID and client secret are correct. You can find these in the [App Registration Portal](https://apps.dev.microsoft.com/), under your application's Application Id and Application Secrets. 
