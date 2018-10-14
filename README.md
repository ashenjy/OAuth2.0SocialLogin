# OAuth2.0SocialLogin

Read the blog post -> https://ashenjay.blogspot.com/2018/10/oauth-2-simplified.html

This is an example node application that implements Githubs OAuth2 API.

In order to run the application:

1. Register your new application on Github : https://github.com/settings/applications/new. In the "callback URL" field, enter "http://localhost:8080/oauth/redirect". Once you register, you will get a client ID and client secret.
2. Replace the values of the `clientID` and `clientSecret` variables in the [index.js](/index.js) file 
3. Install dependencies by executing: `npm install`
4. Start the server by executing `node index.js`
5. Navigate to http://localhost:8080 on your browser.