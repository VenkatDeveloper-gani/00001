
Skygoal_Assignment



#loginApiUrl

API: https://apis.ccbp.in/login
Method: POST
Description:
Returns a response based on the credentials provided

Sample Success Response
{
  "jwt_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VybmFtZSI6InJhaHVsIiwicm9sZSI6IlBSSU1FX1VTRVIiLCJpYXQiOjE2MTk2Mjg2MTN9.nZDlFsnSWArLKKeF0QbmdVfLgzUbx1BGJsqa2kc_21Y"
}
Sample Failure Response
{
  "status_code": 404,
  "error_msg": "Username is not found"
}




# Home route should consist of / in the URL path

Login route should consist of /login in the URL path

Products route should consist of /products in the URL path

Cart route should consist of /cart in the URL path

No need to use the BrowserRouter in App.js as we have already included in index.js

User credentials

 username: rahul
 password: rahul@2021
