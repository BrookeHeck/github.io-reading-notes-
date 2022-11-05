# Login and Auth

## What is Role Based Access Control(RABC)
1. What is Role Based Access Control (RBAC)?
- restricts network access based on a person's role
- this is the authorization part of auth, once the person has been authenticated, then you have to determine what the person is authorized access to
- RBAC is usually determined by job duties, factors can include authority, responsibility, and job competency
2. Share some an example of RBAC including all possible CRUD operations and correlating roles.
- An example of this could be an admin versus a regular user. An admin often has all capabilities. In terms of CRUD, they would be able to read, write, update, and delete. A user may only have read rights. They can see the data but can't alter it.
- Another example is assigning access based on specifically what a job does. For example, my last job was broken up into four main sections. In my career field you could work air terminal operations, air freight, passenger services, or fleet services. We had one application to manage all aerial port activity, but you could only access certain parts of the application based on your specific job and the location of your port.

3. What are the Benefits of RBAC?
- reducing administrative work and IT support
- maximizing operation efficiency
- Improving compliance

## react-cookie-library vs react-cookies component
1. Describe some react-cookie features.
- get a cookie or get all cookies
- set and remove cookies

2. Describe some react-cookies features.
- save a cookie
- remove a cookie
- access user cookies while doing server rendering
- find all cookies or cookies with a name match a regex

3. Which library would you prefer would you prefer? Why?
- I would prefer to use react-cookie because it is already set up to be used as a provider in a react app. This would make it easy to store a token or authentication credential as a cookie and use it anywhere within the app

### Links
[What is Role Based Access Control(RABC)](https://digitalguardian.com/blog/what-role-based-access-control-rbac-examples-benefits-and-more)

[react-cookie](https://www.npmjs.com/package/react-cookie)

[react-cookies](https://www.npmjs.com/package/react-cookies)