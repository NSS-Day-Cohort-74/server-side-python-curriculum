# Step 6: Testing Your Deployed API

Double check all of your changes before starting the deployment process

1. You are on the $5.00/mo plan
2. Your run command has your project name in it
3. All of the environment variables have been set
4. Once your review is done, click the **Create app** button on the right.

Wait until the build and deploy process are complete. If eveything is successful, you will see something like this at the top of the screen. Your info will be slightly different.

![](./images/digital-ocean-success-domain.png)

What's important is the unique URL that Digital Ocean created for your deployed app. In the example above, the domain name is `https://lobster-app-qibhi.ondigitalocean.app`, and yours will be similar, but different.

Right click on your custom URL and copy it.

Then paste it in a new tab in Yaak/Postman and try registering a new user for your project. Since this is a fresh deployment, your database will be completely empty, so there are no user accounts.

Once you register a user, try to login next and verify you get your token.

[Go to Step 7 >](./DEPLOY_DJANGO_07.md)
