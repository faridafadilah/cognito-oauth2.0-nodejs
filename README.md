# cognito-oauth2.0-nodejs
Implement Oauth 2.0 in AWS Cognito with node js

Dont Forget Setup your configuration:
`.env`:
```
COGNITO_CLIENT_ID=
COGNITO_DOMAIN_NAME_URL=https://{}.{aws-region}.amazoncognito.com
COGNITO_LOGIN_GRANT_TYPE=authorization_code
COGNITO_LOGIN_REDIRECT_URL=http://localhost:4200/oauth/cognito
COGNITO_LOGIN_RESPONSE_TYPE=code
COGNITO_LOGIN_SCOPE=email+openid
COGNITO_LOGOUT_REDIRECT_URL=http://localhost:4200/oauth/cognito/logout
COOKIE_SESSION_NAME=nodejs-cognito-oauth
COOKIE_SESSION_SECRET=xxxxxxxx
HOSTNAME=:: 
PORT=4200
