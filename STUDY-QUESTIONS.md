1. What is the purpose of using sessions?
Sessions allow us to persist data across requests.  We can use sessions to persist authentication information so that the user will not need to re-submit credentials each time a new request is made to the server.


2. What does bcrypt do to help us store passwords in a secure manner.
Bcryptjs is a library that allows us to hash a password without having to write our own hashing function (Key Derivation Function).  This allows the password to be stored more securely than if the password were to be stored in plain text.


3. What does bcrypt do to slow down attackers?
Bcrypt provides us with an algorithm that will hash a password multiple times, so in addition to an attacker having to know the algorithm used to has the password, the attacker would also need to know the number of times the password was hashed in the first place.


4. What are the three parts of the JSON Web Token?
The 3 parts the JSON Web Token are the header, the payload, and the signature.

