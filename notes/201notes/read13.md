# Reading 13

### We're trying to save user data on their local machine so their website instance doesn't reset states between visits.

## Local Storage and YOU.

1. A developer would use local storage for persistence of data, so the browser or page can be closed and reopened at a later time and be where the user left off.
2. Information like financial, or PII like address and phone numbers, or passwords or any other data the user would not wish to become public, should not be stored locally. 
3. Local storage can store string data, and if you wanted to convert that string data back into objects or arrays you need to convert it to a string before storage using JSON.stringify() that way it can be returned back into it's normal data afterwards with JASON.parse().
