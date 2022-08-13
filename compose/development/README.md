# Example Configuration for Development Purposes

This example configuration contains only the bare necessities to run the app.  
Due to browser security restrictions, the app will only work without an SSL certificate when running on localhost.

The backend uses the integrated SQLite database which is not recommended for production.

## What needs to be configured?

The following environment variables should be changed:

Frontend:

Backend:
  - EMAIL_ADDRESS
  - EMAIL_PASSWORD
  - EMAIL_HOST