# SAML Java
Sample SAML implementation for Java application

This project contains a simple SAML implementation for a java spring boot application

## Configuration

### Setting up IDP

Create an application corresponding to this test application in your IDP (ssoCircle/Okta/Onelogin).

### Configuration Parameters

APP_ID=<"APP ID from IDP">

ENTITY_ID=<"ENTITY ID FROM IDP">

### Running the application

Start the SAMLApplication class and hit localhost:8443. You will be taken to your IDP and back to the index page once you provide valid login credentials.
You can logout from the link provided in the index page.
