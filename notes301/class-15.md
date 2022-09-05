# Authentication

## Summary

## What is OAuth
1. What is OAuth?

    OAuth is an authorization protocol that is used to allow unrelated servers and services to authenticate access to their services without sharing a logon credential. This is also known as delegated authorization.

2. Give an example of what using OAuth would look like.

    OAuth is common and many sites use it. For example, I can logon on to my Netlify account using my GitHub credentials. Most often, I end up using my Google account credentials to logon to other sites.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

    - first website connects to the second website
    - second website generates a unique one time token and secret
    - first site gives the token and secret to the user's client software
    - client's software provides these to the second site, or authorization provider
    - The user is asked to authenticate and approve authorization to second site
    - User/software approves transaction type at first website and gives them access token
    - first website gives access token to second site as proof of authentication and second website lets first website access site on behalf of user
    </br></br>

4. What is OpenID?

    OpenID is used for authentication. This not about giving authorization to a site, but making sure someone is who they say they are. OpenID serves as a single authenticator for a person.

## Authorization and Authentication Flows
1. What is the difference between authorization and authentication?

    Authentication is making sure the person is who they say they are and authorization is what does this person have rights or access to.

2. What is Authorization Code Flow?

    Authorization code flow is exchanging an authorization code for a token so that the codes are not exposed in the source code of client side web applications.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

    Proof keys are used for single page apps. The proof key is used with the code when exchanging for a token.

4. What is Implicit Flow with Form Post?

    This is an alternative to Authorization Code Flow. It is used in applications that can't store access tokens. This works if the application only needs an ID token for authentication.

5. What is Client Credentials Flow?

    This is when a machine is authenticated using client credentials instead of a persons username or password. This is used when a machine is authenticating a machine and not a person.

6. What is Device Authorization Flow?

    This is when a user is asked to authenticate through a link that is sent to their computer or smartphone to authorize a device.

7. What is Resource Owner Password Flow?

    This is when users provide credentials using an interactive form.

## Things I want to learn more about

### Links
[What is OAuth? How the open authorization framework works](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

[Authentication and Authorization Flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

[Auth0 React SDK for Single Page Apps](https://auth0.com/docs/libraries/auth0-react)