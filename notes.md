# Notes

The  main difference between using sessions and tokens for auto: where the state is kept

- When using Sessions state is kept in the server
- When using Tokens state is kept in the token (client)

# Server

- produce the token
- send the token to the client
- read, decode and verify the token
- make the payload available to the rest of the api

# Client

- store the token
- send the token on every request
- destroy the token on logout