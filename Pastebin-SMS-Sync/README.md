# Pastebin SMS Sync
**Macrodroid Script to Create a Private Paste on every SMS Recieved**

## Requirements
- Macrodroid App
- Pastebin Account. *Require* api_dev_key, api_user_key (use API directly or via Pasteman to generate `api_user_key`)
- *optional*. Utility to access the Private Pastes (Pasteman or Official Pastebin Site)
- Permissions - [Send and View SMS]

## Configuration
- Download the .macro file and Open it with Macrodroid App
- You'll be faced by a Screen about the Macro, which has sections like Triggers, Actions and Constraints. In the bottom of the screen, Click on `Local Variables`
- Click on `api_dev_key` and `api_user_key` to fill out their corresponding values
- Save the Settings / Config.

## About
The Macro gets invoked whenever a new SMS message is recieved. The Contents of the message along with the authentication keys are sent to Pastebin API in the form of a POST request, which results in creation of a Private Paste that can only be accessed by the user who created it (who has access to api_dev_key and api_user_key)

## Usage
- To Access the SMS Messages (like OTP's) when using Laptop / Desktop and the Phone isn't around
- To Log the Messages for Reference Purposes