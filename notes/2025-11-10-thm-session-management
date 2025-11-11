# 2025-11-10 — THM — Session Management

## What I learned:
  - Sessions are used to track users throughout their use of a web application.
  - Session management is a process of managing sessions and ensuring they are secure.
  - Session management is commonly implemented using
    - Cookies: The old school way of session management
      - usually handled by the browser
      - sent from the server "set-cookie" response header
    - Token: This is the modern approach to session management
      - usually handled by the client side code a
      - sent within the request body with Authorization bearer

## The Identification, Authentication, Authorization, Accounting application in web applications
   - Identification: This is the process of verifying the identity of a user Usually done with username
   - Authentication: This is the process of verifying a user is who they claimed they are usually done with password
   - Authorization: This is used to ensure that the specific user has the rights to perform requested action
   - Accounting: This is a process of keeping records of actions performed by the user

## The session management Lifecycle
  - Session Creation: This is when the application created a session
  - Session Tracking: This occurs when the session credentials are being submitted with every request sent to the server
  - Session Expiry: This occurs when a user of a web application left an unterminated session
  - Session Termination: This occurs when a user forcibly performs a logout function

## Key takeaways:
- Each stage of session management poses one or two vulnerabilities such as:
- session creation: weak session values, Session fixation
- session tracking: authorization bypass leading to horizontal or vertical authorization bypass
- session termination/ expiry: Not invalidating session on timeout, long session timeouts
# Cookie Protection from the OWASP Web security Testing Guide
- session cookie can be protected by the use of 
  - cookie's attribute: such as 
     - secure: used to ensure cookies are being sent over a secure channel; HTTPS
     - Path: This is used to specify the scope of the cookie, specified where cookie is valid
     - HTTPOnly: Helps to prevent session leakage as it dis-allow client-side JavaScript to access the cookie
     - SameSite: This is used to assert that cookie ought not to be sent alongside cross site request; used to protect against cross-site requests
     - Domain: This is used to specify the domain that can access the cookies.

