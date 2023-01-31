# # Dependencies

## Keycloak

- yarn add keycloak-connect
- yarn add express-session
- yarn add @types/express-session
- yarn add qs
- yarn add cookie-parser
- yarn add --dev @types/cookie-parser

# MongoDB

- yarn add mongoose

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`MONGO_URL`=Your MonogoDB URL

`PORT`=Your server runnig port

`KEYCLOAK_AUTH_SEVER_URL`= Keycloak base url

`KEYCLOAK_REALM`=Your Keycloak realm

`KEYCLOAK_CLIENT_ID`= Project client

`KEYCLOAK_SECRET_ID`= Project client's secret id

`KEYCLOAK_REALM_PUBLIC_KEY`= Your Keycloak realm public key

`KEYCLOAK_TOKEN_CLIENT_ID`= Admin cli

`KEYCLOAK_TOKEN_SECRET_ID`= Admin cli secret id
