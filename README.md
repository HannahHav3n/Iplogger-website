# Ip and credential logger website

> *Written with vanilla js and html*

# How to use
> Set up the file on a websever of your choose.

## Setup the js file

1. Go into the assets folder and then `hannahscript.js`\
2. Replace the text `REPLACE-WITH-WEBHOOK` with a discord webhook\
3. Your file is now ready, follow the next few steps to setup a webserver

## Set up a web server

1. To do this install ngrok from `https://ngrok.com/`\
2. Log into ngrok with your github, SSO or make a new account\
3. Download ngrok by selecting your operating system and clicking download, save it to the same folder as the html and assets file\
4. In that folder after download run `ngrok config add-authtoken YOUR-AUTH-TOKEN`, you can get your auth token from `https://dashboard.ngrok.com/get-started/your-authtoken`\
5. In the same folder run the command `ngrok http 8080` this will setup a webserver on port 8080, the command window will show you the ngrok public url, this is the one you want\
6. Go to that public url and test if it logs to your webhook

