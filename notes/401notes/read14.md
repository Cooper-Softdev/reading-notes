# Reading

## Intro to password hashing

1. Define the term “hashing”.

  - Hashing is a process that transforms input data of any size into a fixed-size string of text, which is typically a hexadecimal representation.
    This transformation is done using a hash function. The output, known as the hash value or hash code, is unique to the input data. Any change in
    the input, even a minor one, will produce a significantly different hash value.

2. Explain to a non-technical friend what a hash function does to a password.

  - Imagine you have a secret message (in this case, a password) that you want to keep safe. A hash function is like a special blender for your
    secret message. You put your message in, and the blender chops and mixes it up into a jumbled mess that looks nothing like the original message.
    This jumbled mess is still unique to your original message, but it's nearly impossible to figure out the original message just by looking at the
    jumbled mess. That's what a hash function does to a password.

## bcrypt overview

1. What does it mean to ‘salt’ a password?

  - 'Salting' a password means adding a random string of characters, known as a 'salt', to the password before it is hashed. This makes the hashed
    password unique even if the original password is not. It adds an extra layer of security because even if two users have the same password, their
    hashed passwords will be different because of the unique salts.

2. What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?

  - If a hacker wants to find the 'salt' string for your passwords, they would need to gain access to the place where the salt is stored.
    This is usually the same database where the hashed passwords are stored. So, if a hacker can breach the database, they might be able to
    find the salt strings.

## jBCrypt

1. How does the Blowfish block cipher handle the increased computation speed of new computers?

  - The Blowfish block cipher, which is used in BCrypt, handles the increased computation speed of new computers by using a Key Factor
    to adjust the cost of hashing. This Key Factor can be changed to influence the hash output, making BCrypt resistant to hacks. As
    computers become more powerful, the Key Factor compensates for these powerful computers and slows down the hashing speed significantly,
    ultimately slowing down the password cracking process until it's no longer a viable strategy.

2. What are the issue with the two most common password hashes for Java (“Java password hash” and “Java password encryption”)?

  - The two most common password hashes for Java, "Java password hash" and "Java password encryption", have significant security issues.
    The "Java password hash" uses an unsalted hash, which allows reverse dictionary lookup of passwords. The "Java password encryption"
    recommends reversible encryption, which is rarely needed and should only be used as a last resort. Both of these methods put your
    data and resources at risk.
