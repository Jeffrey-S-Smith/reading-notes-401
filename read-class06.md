Readings: Authentication
========================

[Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

1. Explain to a non-technical friend how you would safely hash and store a password.
    Storing passwords securely is a recurring concern.
    But what are the main methods, how do they work, and what are they worth against current password cracking techniques?
    In this article we explain the main principles of secure storage (hash, salt, pepper, iteration) and highlight their importance for resisting password recovery methods. Finally, we will talk about a reliable hash function for secure storage.

2. What is Bcrypt?
    is a password-hashing function  

3. Why might you use something like Bcrypt?
    bcrypt allows building a password security platform that can evolve alongside hardware technology to guard against the threats that the future may bring, such as attackers having the computing power to crack passwords twice as fast.

[Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

1. What is Basic Authentication?
    In the context of an HTTP transaction, basic access authentication is a method for an HTTP user agent to provide a user name and password when making a request.

2. What properties are necessary in the header of a Basic Auth request?
    * Basic Auth
    * Bearer Token
    * API Key
    * Digest Auth
    * OAuth 2.0
    * Hawk Authentication
    * AWS Signature

3. How are `username:password` in Basic Auth encoded?
    is encoded in Base64

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

1. Define the authentication process to a non-technical recruiter.
    Authentication is the process of determining whether someone or something is, in fact, who or what it says it is. Authentication technology provides access control for systems by checking to see if a user's credentials match the credentials in a database of authorized users or in a data authentication server.

2. How should your error messaging respond (both HTTP and HTML)? Why?
    An HTTP response contains: A status line. A series of HTTP headers, or header fields. A message body, which is usually needed.
    A response that represents an error or failure, either from a non-successful HTTP status, an error while executing the request, or some other failure which occurred during the parsing of the response.

3. Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

Bookmark and Review
-------------------

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

* This learning is about authentication and error you need to use. Also how to create authentication and the steps.

## Things I want to know more about