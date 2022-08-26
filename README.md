<h1 align="center">
  <img src=".preview/Logo.png" width="250"><br>
  Momentum
</h1>

This is the official documentation for the Momentum Web App.

## About

Momentum is a WebApp designed to help hemophiliacs to exercise and thus counteract the progression of the disease.
By assigning a plan of exercises to a patient, the patient can execute these exercises while being supervised by an AI running on the backend. This way, the patient can be sure that the exercises are being executed correctly.

<div align="center">
  <img src=".preview/App.png" width="40%">
  <img src=".preview/Profile.png" width="40%">
</div>

## Running the app

To run Momentum, you need at least the frontend, the backend and an AI server.
All are distributed as Docker images.

Frontend and Backend need to be publicly accessible. The AI server needs to be accessed only from the backend.

For deployment environments, we strongly recommend an external PostgreSQL database to be used with the backend.

In the folder [`compose`](compose) you can find some example configurations.