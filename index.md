## Open Source Best Practices

This is a one-stop guide for all the newcomers in Open Source to follow best practices for making open source contributions great again.

### Read Project Readme

It may sound boring, but you have to get the understanding of the project's mission and workflow, by going through readme given.

### Read Contributing Guide.

Once you find the great project up, try to find the contributing guidelines, in the readme, and setup the project locally, if required.

### Check on to issues.

Once you are all done with above steps, make sure you check on to existing issues, and also at the same time, do ask in the comments who are solving the issue and the status of the solution. If the issue is assigned to someone, politely ask, the status and how are they doing it, and if they need help or not. 

### Be Respectful 
Software Engineers around the globe from Google to Microsoft, loves to contribute to open source because of its potential in creating the world a better place. So you should be respectful to everyone in any situation. 


## Developers and Maintainers
### Discord Webhoook
### Reference: 
https://gist.github.com/jagrosh/5b1761213e33fc5b54ec7f6379034a22 
Creator Credits: [John Garosh](https://www.linkedin.com/in/jagrosh/)
#### Step 1 - Make a Discord Webhook
1. Find the Discord channel in which you would like to send commits and other updates

2. In the settings for that channel, find the Webhooks option and create a new webhook. Note: Do NOT give this URL out to the public. Anyone or service can post messages to this channel, without even needing to be in the server. Keep it safe!
![WebhookDiscord](http://i.imgur.com/PZE2wFu.png)

#### Step 2 - Set up the webhook on Github
1. Navigate to your repository on Github, and open the Settings<br/>
![Settings](http://i.imgur.com/4GNq1lu.png)

2. Select Add Webhook<br/>
![Add](http://i.imgur.com/ZvrBQdi.png)

3. Paste in the webhook url and append `/github` to the end. Select "Send me everything", set the type to `application/json`, and then Add Webhook<br/>
![WebhookSettings](http://i.imgur.com/mrf8Qmj.png)

4. Test it by updating something or starring the repository! If it works, you're all set!<br/>
![Star](http://i.imgur.com/ABlwTLf.png)
