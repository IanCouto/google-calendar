# A Calendar along the lines of Google Calendar.

This project is based on Angular and it DOES not intend to copy Google calendar completely, rather, it tries to Emulate it.

## Integrations:

Uses Google APIs (OAuth2 with Gapi to make things a bit easy). A better way would've been to write `Firebase Cloud Functions` and abstract the Gory integration stuff there, but there was no time for that.

## How to run local:

1. Clone the project.
2. npm install --force --legacy-peer-deps
3. Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`.

## IMPORTANT
You will need to Authorize the app with Google add grant all permissions such that it can access your Calendar and Events.


## Further help

Shoot a mail to `icoutodepaula@gmail.com` if you need more help.

<img src="src\assets\md\screenshot.png" alt="App Screenshot" title="Screenshot">
<img src="src\assets\md\screenshot1.png" alt="App Screenshot" title="Screenshot">
