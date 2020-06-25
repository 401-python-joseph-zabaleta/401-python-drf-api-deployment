# Lab: Class 34 - API Deployment

## Open Git Pull Requests  


## Overview  

You will be deploying your application to a remote web host. Along the way you’ll update yesterday’s project to be web ready.
  
These instructions will presume you are deploying to Digital Ocean but you are welcome to research other options and choose for yourself.

## Feature Tasks and Requirements  
- [] Modify your application to store SECRET_KEY, ALLOWED_HOSTS, DEBUG and DATABASE information in .env file.
- [] Add CORS capabilities to your app and whitelist allowed origins.
- [] All the code changes will be in settings.py so check the demo code for CORS and Env related lines.
- [] Create account with Digital Ocean (or other host of your choosing.)
- [] Deploy application to Digital Ocean

## Implementation Notes:  
Useful Terminal Commands
- `docker-compose up --build`
- `docker-compose down`
- `docker-compose run web ./manage.py migrate`
- `docker-compose run web ./manage.py collectstatic`

## User Acceptance Tests  
- [] Manually confirm API using Postman.
  - Remember to use deployed url for postman requests.

## Dependencies  
- python = "~3.8"
- django = "^3.0.7"
- djangorestframework = "^3.11.0"
- psycopg2-binary = "^2.8.5"
- djangorestframework_simplejwt = "^4.4.0"
- gunicorn = "^20.0.4"
- django-cors-headers = "^3.4.0"
- whitenoise = "^5.1.0"

## Authors  
- Software Developer: Joseph Zabaleta
  - [Official Github](https://github.com/joseph-zabaleta)  

## Collaborations  
- none  

## License  
This project is under the MIT License.

## Acknowledgements / Resources  
- none

## Version History  
- 1.0.0 20200625  
    - Initial files created.  
