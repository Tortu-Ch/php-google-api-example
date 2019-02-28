
# Google API calls Example in PHP:

## Access live example
Automatically sign in with 'guest_account' of test@gmail.com   
[https://google-api-example.herokuapp.com/guestSignIn.php](https://google-api-example.herokuapp.com/guestSignIn.php)

Explanations and links to Google doc and sheet used    
[https://google-api-example.herokuapp.com/index.html](https://google-api-example.herokuapp.com/index.html)

Sign in with a "real" Google account that exists in the Google sheet of users       
[https://google-api-example.herokuapp.com/login.php](https://google-api-example.herokuapp.com/login.php)
   
Sign in via URL       
[https://google-api-example.herokuapp.com/signInFromGoogle.php?gmail=test@gmail.com](https://google-api-example.herokuapp.com/signInFromGoogle.php?gmail=test@gmail.com)


The locked but visible Google sheet https://docs.google.com/spreadsheets/d/1vhce-ziBi6wneqJrxd7Zhyqth8ZLHMJHot1wxgK_T7k/edit#gid=0 that is read and written to.

![visual explanation](https://github.com/steenhansen/php-google-api-example/blob/master/google-api.png)
## Information
Sheet/Document/Email/Authorization Classes

    php-google-api-example/Google_Api/


To install composer libraries
    
    php-google-api-example/ composer install


To enable Google credentials

    Copy google-sample files to google-account directory
    

To test
    
    php-google-api-example/  php tests/call_tests.php   
