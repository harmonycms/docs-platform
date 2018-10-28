# How to update addons?

## Hook setup

We provide a generic endpoint you can call manually from a git post-receive hook or similar.  
By doing that, this ensures that your addon will always be updated instantly when you push to GitHub.

To do so, you need to add a new WebHook in your repository with the next configuration:

**Payload URL:** `https://api.harmonycms.net/update-package?access_token=ACCESS_TOKEN`  
**Content type:** `application/json`

