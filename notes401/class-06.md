# Authentication

## Summary

## Securing Passwords
1. Explain to a non-technical friend how you would safely hash and store a password.
- Hashing algorithms are one way encryption. This means that even though hashing algorithms have weaknesses, they are still good for storing passwords because if they are stolen, they can't be reversed. Passwords should always be hashed before they are stored.

2. What is Bcrypt?
- Weaknesses of a hashing algorithm include brute force attack and hash collision. This happens when an attacker tries a bunch of inputs until the correct hash is produced. Because hashes have a predefined output length, there are some inputs that will create the same hash. This is called a collision attack, and is useful because an attacker doesn't have to try every single combination of letters to get the correct hash. Bcrypt is a way to overcome this issue.

3. Why might you use something like Bcrypt?
- Bcrypt is used to slow down brute force attacks by using key stretching. This is technique that complicates the password before it is hashed so that brute force attacks are more difficult and take longer.

## Basic Auth
1. What is Basic Authentication?
- Basic auth is a method for an HTTP agent to provide a username and password when making a request

2. What properties are necessary in the header of a Basic Auth request?
- The header must contain the word, Authorization, followed by a semicolon and space, and then the credentials.

3. How are username:password in Basic Auth encoded?
- Encoded with Base64

## OWASP Auth Cheat Sheet
1. Define the authentication process to a non-technical recruiter.
- Authentication is the process of making sure someone trying to login is who they say they are. This is usually done with a username and password.

2. How should your error messaging respond (both HTTP and HTML)? Why?
- The response should be generic and not give any clues to how the username and password are being validated.

## Links
[Securing Passwords with Bcrypt Hashing Function](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

[Basic access authentication](https://en.wikipedia.org/wiki/Basic_access_authentication)

[Authentication Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Authentication_Cheat_Sheet.html)

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

