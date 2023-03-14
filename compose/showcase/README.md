# Example Configuration for Showcase Purposes

This example configuration contains everything necessary to run the app as a public showcase.  
Due to browser security restrictions, the app will only work with an SSL certificate.

## What needs to be configured?

The following environment variables should be changed:

Frontend:
  - BACKEND_URL
  - WEBSOCKET_URL
  - FRONTEND_URL
  - VIRTUAL_HOST
  - DEBUG (unset for off or any value for on)

Backend:
  - EMAIL_ADDRESS
  - EMAIL_PASSWORD
  - EMAIL_HOST
  - ALLOWED_ORIGINS
  - ALLOWED_HOSTS
  - VIRTUAL_HOST

For the nginx-proxy you will need to supply a valid SSL certificate.
To do so please refer to the [documentation](https://github.com/nginx-proxy/nginx-proxy#ssl-support) of the nginx-proxy.