# DHL_custom_drupal_module

Notes : Below are some custom modules details.

1) Create New drupal custom module called LocationForm:
   Modules/custom/locationform

2) Created two controller:
   controller/ApiController : to display Dummy api data 
   controller/DispalyController : to display Form data fetch from database

3) locationform.install : created new table to submit form data


4) Display data from custom form submission:

  "http://localhost/drupal/display-display"


5) API to fetch details and display in drupal:

   Dummy Json API Url:  "https://dummyapi.online/api/users"

   Url to display APpi data: "http://localhost/drupal/display"


6) Custom form URL: Enter details 
   
   * postal code should be 10 digit.

   http://localhost/drupal/demo-registration
 
