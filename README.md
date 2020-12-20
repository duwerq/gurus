# Serverless Framework & AWS AppSync API

### Getting Started

1.

```
$ yarn
```

2. This template is tightly integrated with Serverless Pro for deployments. There are three env variables that must be set for each stage of deployment.

- STAGE
- ACCOUNT_ID (AWS account id)
- API_KEY  (Can really be anything but a randomly generated key would be ideal)

![](https://user-images.githubusercontent.com/14824061/102717412-1ccff480-42b0-11eb-9d81-1cbf5547d4e1.png)
  

3. To deploy, simply run:

```
$ sls deploy
```

4.  To see your new AppSync API in action after deployment, head over to the AppSync console in AWS.

![](https://user-images.githubusercontent.com/14824061/102717437-3ec97700-42b0-11eb-9a55-c7689b1ee74e.gif)

5. That's it! You're all good to go ;)
