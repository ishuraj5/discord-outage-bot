## A simple discord bot to check website status

### How to use
This script will check the status of your website every few minutes and update a channel name in discord with the status of the site
every 5 minutes.

- clone repo
- Create a voice channel in discord and copy the id of it
    - fill out items with your bots token information and website url 
    - put the channel id in the config.json
- run `npm install`
- run `npm run start`

Your bot is online and will check your website every few minutes. 
If your website goes offline, your discord users will know as the channel name will update with a red circle emoji.
