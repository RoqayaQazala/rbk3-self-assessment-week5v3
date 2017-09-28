## Authentication
- Explain why each system fails (hacked), and how to guard against that failure when using the follwoing types of passwords:
- Commit with the comment "passwords"

- Plaintext passwords. 
 * I think because if someone gained access to the database -somehow- all accounts will be hacked 

- Encrypted passwords
It translate the text into an alternate 
representation ,It would fail if only the clients device is hacked, one way to protect it is to protect the clients device itself.

- Hashed passwords :
 can be version of encryption that is Lossy and Irreversable.
it is using rainbow tables , can try all possible ways .. this can be avoided by salting the password before the hash , different salt for each password , it means even getting one will not help the hacker gussing the others. 

