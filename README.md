# Auth0 example app for Node.js and Gitpod

This is the example app from Auth0 for the express based version readily configured to work with Gitpod and
its Local VS Code mode.

## Step 1

Go to your [Auth0](https://auth0.com) dashboard and in the applications section create a "regular web application". You would set the application upo for local development as [described here](https://auth0.com/docs/configure/applications/work-with-auth0-locally#use-local-domains-with-auth0).

Spoecifically you would enter

> Allowed Callback URLs:

```
http://localhost:3000/callback
```

> Allowed Logout URLs
```
http://localhost:3000
```

## Step 2

Download and install [VS Code](https://code.visualstudio.com/download) on your local machine.

## Step 3

Go to your [Gitpod settings](https://gitpod.io/settings) and add two environment variables:

```
AUTH0_CLIENT_ID={copy `Client ID` value from your application}
AUTH0_TENANT_URL=https://{copy `Domain` from your application}
```

## Step 3

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/from-referrer/)

When the web IDE opened, press "F1" and serach for "Open in VS Code". 
When you have opened the workspace in VS Code open the ports tab and forward `3000`.

<img width="991" alt="Screenshot 2021-09-17 at 13 39 39" src="https://user-images.githubusercontent.com/372735/133776721-dd4cfd4e-e5b3-4a8a-ac8b-3b8c7d17870e.png">

Go to http://localhost:3000  
