# Access Control (ACL)

* Review, Research, and Discussion
1. When is Basic Authorization used vs. Bearer Authorization?

- Basic Authorization --> in the sign in process, to verify the username and password
- Bearer Authorization --> after sign in process to ensure that the user still logged in.

2. What does the JSON Web Token package do?
- It allow us to generate (Sing) tokens and define it's payload and secret, also allow us to verify the tokens of the use

3. What considerations should we make when creating and storing a SECRET?
- Secret security - (encrypt it)
- Save in a changeable environment (dotenv)


* Preview
1. Which 3 things had you heard about previously and now have better clarity on?
- Tokens 
- Bearer Authentication
- encryption

2. Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
- Secret
- JWT

3. What are you most excited about trying to implement or see how it works?
RBAC ---> Role Based Access Control.

### Preparation Materials

- Authenticate the user ---> Role ---> Rights based on the role.


- RBAC --> the process of providing users with rights/access to resources depending on their responsibilities within the organization. (System access restriction on the basis of their position to licensed users)


- ABAC --> defines the procedure to provide the user rights/access to different resources, such as the department of the user, time, location.


- ACL ---> defines access rights to a certain item, such as a document, by a particular user or set of users. Just like just reading or reading and writing.


- Benefits of RBAC :

- Policy
- Least Privilege to each user (less harm or damage)
- Organization


- Cryption: it's data and information transforming into a secret code to disguise its actual significance.
- Token: is like a user password that states that a user has a certain operation access or authorization. It's made of header header (holds the algorithm and type of the token) Loading payment (information about the user) Signing (token security issues)
- Bearer: is a kind of authentication that has a token that is used after singing.
- Secret: is confidential information that is only allowed to qualified users between your app/api and the authorization server.
- JSON Web Token: JWT is a package which allows us to set up and check user tokens.