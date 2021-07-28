# TTV Tools

## Bonk
A simple overlay label for counting the number of users banned during the current streaming session. 
No server side capabilities are required; this project can easily be deployed to an AWS S3 static site 
with a CloudFront distribution providing SSL 


### Building
- Create a Twitch app https://dev.twitch.tv/console/apps
- Replace all instances of CLIENT_ID in the project files with the value provided by Twitch
- Replace BASE_URL with your domain name, e.g. https://www.example.com/bonk
- Upload files to hosting provider
