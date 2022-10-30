# Hash Tables

## Terminology
- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for security. In the case of a hash table, it is used to determine the index of an array
- Buckets - A bucket is what is contained in each index of the array in a hash table. An index could contain multiple key value pairs if a collision occurs.
- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hash table

## What they are
- Data structure that utilizes key value pairs.
- Used for storing data and quickly retrieving it
- The hash is used to map the key to a specific index in the table

## Why we use them
- Arrays have fast access if we know the index of the stored data that we want to access. The hashing algorithm is O(1) efficiency, so we can use the hashing algorithm to get the index, and then access the array with the determined index. Because are not looping through the array, the efficiency to get data is much better.

## Structure
### Hashing
- A hashing code turns a key into an integer. Hash codes should never have randomness, so the same key should always return the same integer. Their output is what we use as the array index to store or read data.

### Creating a Hash
1. Add or multiply all the ASCII values together
2. Multiply it by a large prime number, such as 599
3. Use modulo to get the remainder of the result, when divided by the total size of the array
4. Insert into the array at the index

### Collisions
- Collisions occur when more than one key hashes to the same index
- We handle collisions by using linked lists. Each bucket should contain a linked list and key value pairs should be added to the linked list. This is so that keys with same hashes are not overwritten by the key value pair being added.

## Storing Data in a Hash Map
- accept a key
- calculate the hash key
- use modulus to convert the hash into an array index
- store the key with the value by appending both to the end of a linked list

## Reading Data from a Hash Map
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given

## Hash Map Methods
- get()
    - returns the value of the key that is passed to it as a parameter
- has()
    - returns a boolean, true if the hash map contains the key that was passed to it as an argument, or false if it doesn't
- keys()
    - returns a collection of unique hash keys
- hash()
    - takes a key, calculates a hash, and returns the index of the array where the key value pair is or should be placed

### Links
[Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
[What is a HashTable Data Structure](https://www.youtube.com/watch?v=MfhjkfocRR0)
[Basics of Hash Tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)