# Local Storage for Web Applications

## Summary
Today's reading talked about how to use local storage with a web application, times when local storage would be acceptable, and the limitations of local storage. Using local storage is very easy because there is already a local storage object in JavaScript. All you have to do is use it's methods to set and store data. Data is stored only as strings, and to get data values from it, you would need to use the JSON.parse() method. Local storage is a helpful feature, but is only appropriate for small amounts of data. For example, storing a user's color preferences could be done with local storage. Large amounts of data are better off in a back end server or database.

## Local Storage and How to Use It on Websites
1. Why would a developer use local storage for a web application?
- Local storage for a web application is helpful to store a user's infromation or preferences without making them log in or create a user profile.
- Cookies can be used to store information as well, but they present security issues and add to the load of documents accessed on that domain

2. What information should not be stored in local storage?
- Local storage should not be used for large amounts of data. It should only be used for minor preferences that a user would like to keep if a page refreshes.

3. Local storage can store what type of data? How would you convert it to that type before storing?
- Local storage only stores strings. The work around for this is using JSON.parse() or JSON.stringify() methods to go between JSON objects with actual data and the JSON data all as a string.

## Things I would like to know more about
- I know we are strarting with local storage, but I would really like to know more about cookies, how we create them, and how we use them to store and pass data
- Back end servers can also store data and I would like to know more about creating back end servers and using APIs to communicate between them. Also with this, a lot of times databases are on back end servers and I would like to know how to make a database and store data with this.

### Links
[Local Storage And How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)
\
[THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS](http://diveinto.html5doctor.com/storage.html)