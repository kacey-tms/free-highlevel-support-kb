**Date Updated:** 2025-05-17T17:05:19.000Z

  
In case developers lose access to access token or refresh token due to any reason - either due to an incident from HighLevel or due to an error on the developer's end - we have provided a solution. 

  
You can now use the **Reconnect API** to get back the authorisation code that can be used in [Get Access Token API](https://highlevel.stoplight.io/docs/integrations/00d0c0ecaa369-get-access-token) (OAuth - Authorisation grant flow) to get back a new set of access and refresh tokens. 

This enables you to reinstate the connection without having to trouble your users.

  
For Sub-Account App connections:

```javascript
curl --location 'https://services.leadconnectorhq.com/oauth/reconnect' \
--header 'Content-Type: application/json' \
--data '{
    "clientKey": "<client_id>",
    "clientSecret": "<client_secret>",
    "locationId": "<locationID where the app was installed>"
}'
```

JavaScript

  
For Agency connections:

```javascript
curl --location 'https://services.leadconnectorhq.com/oauth/reconnect' \
--header 'Content-Type: application/json' \
--data '{
    "clientKey": "<client_id>",
    "clientSecret": "<client_secret>",
    "companyId": "<company where the app was installed>"
}'
```

JavaScript

  
Response of the API:

```javascript
{
    "authorizationCode": "<auth_code>",
    "expiresAt": "2024-10-08T13:35:43.887Z",
    "traceId": "trace-ID-ref"
}
```

JavaScript
  
  
**IMPORTANT**: If you are concerned on how do I receive Official Support for HighLevel API-Related Issues or Broken Marketplace Apps? Please visit <https://developers.gohighlevel.com/> for API documentations and support.