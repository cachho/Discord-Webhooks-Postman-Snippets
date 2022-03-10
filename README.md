# Discord-Webhooks-Postman-Snippets
A variety of categorized snippets to send discord webhook posts without needing any prior postman experience.

## How to use
1. Install postman from https://www.postman.com/
2. Download *"Discord Webhooks.postman_collection.json"* and *"Discord Webhook.postman_environment.json"*
3. Start postman and import the collection *"Discord Webhooks.postman_collection.json"* with the **import** button
4. Import the environment *"Discord Webhook.postman_environment.json"*
5. Get your discord channels webhook url (edit channel > Integrations > Webhooks > New Webhook) (you only need one per channel)
6. Copy the channel into postmans environment tab
7. Edit the other environment variables (next section)
8. Edit the text inside the collection to create your posts (body > raw json)
9. Hit send to post to discord

## Environment Variables ##
I tried to make the values that will most likely be the same between all your posts a variable so you can adjust it to your needs by editting one field with no need to come back when you use different snippets.

* url = your wbhook url (keep this secret)
* color = the small color strip to the left of a post
* profile_pic = profile pic of the sender of the post (the profile pic every user has, that's only seen at the start of a sequence of messages from a user)
* profile_name = same logic as above
* footer_pic = the footer (sometimes used as a subtitle) has a small icon that you can adjust here with an image url

## Screenshots ##
![Alt text](https://github.com/cachho/Discord-Webhooks-Postman-Snippets/blob/main/screenshot.png?raw=true "Screenshot with the different categories")
![Alt text](https://github.com/cachho/Discord-Webhooks-Postman-Snippets/blob/main/screenshot-chat.png?raw=true "Screenshot from a discord chat with webhooks")

## Credits ##
Inspired by and based on Birdie0 post (https://gist.github.com/Birdie0/78ee79402a4301b1faf412ab5f1cdcf9). You can read what the different fields do there.
