### invalid_client
This error gets called whenever there is a problem validating credentials of some sort.

**Possible causes**
* The authorization code presented is invalid or was issued to a different tenant
* The client secret provided is invalid
* The clientID provided is invalid
* The client assertion was signed using a key not defined on the application
* A refresh token is no longer valid
* The username or password a user tried putting in is invalid
