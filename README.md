# How to use Postman Collections
The easiest way to get started using the Background check Integration APIs is to use our Postman collections. <br>Postman is a free-to-download tool for making HTTP requests. You can find more details about Postman [here](https://www.postman.com).<br>
The following steps outline the necessary actions in order to install Postman and gain certainty that everything is working as it should be.
<br>If you prefer, you can explore our API with other tools like curl.

[IMPORTANT] PLEASE NOTE THAT POSTMAN IS AN INDEPENDENT ENTITY AND IS NOT AFFILIATED WITH LINKEDIN. LINKEDIN IS PROVIDING THE FOLLOWING RESOURCES TO SUPPORT YOUR USE OF THE POSTMAN SERVICES BUT ULTIMATELY, ANY USE OF THIRD PARTY SERVICES, SUCH AS THE POSTMAN SERVICES, IS AT YOUR OWN DISCRETION AND RISK. LINKEDIN DOES NOT ENDORSE OR VET THE POSTMAN SERVICES AND IS NOT RESPONSIBLE FOR ANY DAMAGE OR LOSS OF DATA RESULTING FROM YOUR USE OF THIRD PARTY SERVICES. NOTHING HEREIN SHALL RESTRICT LINKEDIN'S ABILITY TO ENFORCE ALL OF ITS RIGHTS UNDER ITS AGREEMENTS WITH YOU.

## Install Postman
Visit www.getpostman.com and download the version of Postman required for your platform and complete Postman installation.

## Import Postman Collection

- Open Postman
- Click the `Import` button, click the `Choose Files` button and locate the required collection JSON file to import. An import success message appears for each collection imported and then you can see the collection in the `Collections` tab.
- After a collection is successfully imported into postman, Click `...` icon next to an imported collection and click on the `Edit` button to setup variables.
- Please set the value for the variables and click on the `Update` button.
- You have successfully setup and are now ready to make API calls.

## Background Check Integrations Postman Collection Variables

|Variable Name|Description|
|---|---|
|customer_app_client_id|Client id of Customer's Application. It will be used to get the access token.|
|customer_app_client_secret|Client secret of Customer's Application. It will be used to get the access token to be able|
|onboarding_url|URL where you will receive the customer's LinkedIn Information via a GET request.|
|callback_url|URL for LinkedIn to send push notifications to your system regarding the integration.|
|hiring_context|Hiring context of the customer requesting the integration in the format of “urn:li:contract:123”.|
|redirectUrl|URL where you should redirect customers back to LinkedIn when they have finished the extension onboarding process in your system|




