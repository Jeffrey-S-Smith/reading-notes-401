Reading: API Integration
========================

Reading
-------

* [Review API Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/api-server/)

1. Explain the different between a query string parameter and a path parameter.
    It is very important to know when to use Query Parameter or URI Parameter while designing an API. URI parameter (Path Param) is basically used to identify a specific resource or resources whereas Query Parameter is used to sort/filter those resources.

2. What would our API URL with a path id parameter be given the following information:
    1. Domain: `http://our-site.com`
    2. `v3`
    3. model name: `stuff`
    4. id: `things`

 API: http://our-site.com/id

3. We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

* [Review Auth Server Build](https://codefellows.github.io/code-401-javascript-guide/curriculum/apps-and-libraries/auth-server/)

1. Describe how you would use middleware to implement basic and bearer auth.
    The Basic and Digest authentication schemes are dedicated to the authentication using a username and a secret (see RFC7616 and RFC7617). The Bearer authentication scheme is dedicated to the authentication using a token and is described by the RFC6750.

2. Describe the handshake necessary to implement OAuth.
    OAuth is an open-standard authorization protocol or framework that provides applications the ability for “secure designated access.

3. Describe how Role Based Access Control works to a non-technical friend.
    An organization assigns a role-based access control role to every employee; the role determines which permissions the system grants to the user. For example, you can designate whether a user is an administrator, a specialist, or an end-user, and limit access to specific resources or tasks.
