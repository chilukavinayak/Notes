## What is OAuth 2.0?##

**OAuth** = **O**pen + **Auth**orization (2.0 is Version)

OAuth 2 is an Authorization framework


OAuth is industry standard protocol for authorization, and it provides specific authorization

Different Authorization for different types of applications that developer creates


Example:

![Oauth Example](https://github.com/chilukavinayak/Notes/blob/main/Images/OAuth1.png)

You as **User** can grant another application and access to a another application and access to the data that is stored

In above example:

**User** on left.

**Mobile Application** on middle.

**Facebook Service** on right.

Let assume that mobile application is Photo App that allows a user to access their facebook for us.
unless this mobile application acquires user permission, it will not be able to access user for us
this is where authorization frame comes.

Authorization framework can help user to grant their permission to a third party application like
mobile application to access their user data on facebook on their behalf.

Let this third party application to access their data on facebook, The user not need to give username and
password to the thrid party application.

We can limit the access, allow only limited set of operations on user's behalf.

![Oauth Example](https://github.com/chilukavinayak/Notes/blob/main/Images/OAuth2.png)

Ealier days before OAuth frma work, user need to select one of the account and pass username
and password of respective account and signin, these information sent thru post request and thirdparty application
would save these details in their database, they can access whenever they want, this approach is insecure.

![Oauth Example](https://github.com/chilukavinayak/Notes/blob/main/Images/OAuth3.png)

instead of giving username and password to the thirdparty application or website, Oauth frame work
redirected to login page instead. User will use google login page to login google credentials, and these
page is created by google. And third party mobile applicaiton does not get to know users google password, and if it  
successful, then Oauthorization server in this case it is google server. it will ask users if they allow this thrid
party application to view their user force and if user taps allow and grant their permisssion, then Google will pass a special
access token to this third party

using access token third party access to account, but limited set of operation thirdparty can peform on your behalf

![Oauth Example](https://github.com/chilukavinayak/Notes/blob/main/Images/OAuth4.png)



## OAuth 2.0 Roles##









