User Authentication
This project includes a secure signup and login system using API calls. Users can safely create accounts and log in to access protected features.

Signup: Users can register with their name, email, and password. The frontend sends this data to an API, which creates a new user account securely.

Login: Registered users can log in with their email and password. The API validates the credentials and returns an authentication token.

Token Handling: The authentication token is stored in the browser (e.g., localStorage) to maintain user sessions and secure sensitive actions.

Security: All API communications are assumed to be secure. Passwords are not stored on the frontend.
