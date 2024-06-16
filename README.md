# Django backend API Template

### Basic User Authentication With Simple JWT


Routes and their description:
  api/auth/login Method: POST Description: send username and password for login and return access and refresh tokens
    
  api/auth/logout Method: POST PROTECTED Description: logout of the system

  api/user/register/ Method: POST Description: create a new user
  
  api/token/ Method: POST PROTECTED Description: get user token

  api/token/refresh/ Method: GET PROTECTED Description: refresh access token with refresh token