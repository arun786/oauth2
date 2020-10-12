# OAuth2.0

OAuth = Open + Authorization is an authorization framework
It is an Authorization framework, also called as delegated authorization framework.

## General Flow in OAuth2.0

## Types of Clients

    Types of Clients
    
    1. Confidential Clients - The client can keep the Client Id and Secret key safe, which will be used to get the access token
    from an Authorization Server.
    
    2. Public Clients - These type of Client, they cannot keep the ClientId and the Secret key safe.
    
## Different Types of Access token
   
   1. Identifier Type - its just a Token.
   2. Self Contain the authorization information - It Contains information about the access Token.
   
   Self Contained Access Token is json object encrypted that is base64 encoded. it consists of 3 parts
   
   1. header - how to validate the token.
   2. payload - consists of claims.
   3. signature
 
## Grant Type

    What is Grant Type?
    
    Grant Type is a way an application gets an access token.
    
    1. Authorization Code.
    2. Client Credentials.
    3. PKCE Enhanced Authorization code
    4. Device Code.
    
    Deprecated
    1. Implicit Flow
    2. Password Flow# oauth2
