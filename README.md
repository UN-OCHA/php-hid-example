# Example HID client in PHP

This repository provides an example HID client application written in PHP, using the [The PHP League OAuth2 library](https://github.com/thephpleague/oauth2-client). 

## Running the application

1. Make sure you have a valid user account on [the HID dev environment](https://api.dev.humanitarian.id)
2. Run the application using `docker-compose up`
3. Point your browser to http://localhost. The application should redirect you to the login page on the HID dev environment.
4. Log in using your user account
5. You should be redirected to localhost, and should see the information retrieved from HID (access token, user account etc...)


