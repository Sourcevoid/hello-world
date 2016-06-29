# Hello World examples for Sourcevoid

This repo includes hello world apps for both Dart and Nodejs server and client side (static) apps. 

## Get started

1. [Get a Sourcevoid account and login](https://cloud.sourcevoid.com/#signup)
2. Create your own copy of this repo on your Github account (or download a zip archive of it and use archive deployment)
3. Create a Sourcevoid pool (if you don't already have one you want to use)
4. Create a Sourcevoid app (if you don't already have one you want to use)
5. Connect your Github account (if you don't already have or want to use archive upload)
6. Deploying a Sourcevoid environment (either from your Github account or upload a zip archive)
 - Enter a name for the environment, "hello" for example  
 - Select your Github repo from the selector (or archive)
 - Press the "More" button and enter the name of the directory/framework you want to deploy, eg. "/shelf" or "/express" if you deploy from your Github repo and if you downloaded a zip archive from Github use "/hello-world-master/shelf" or "/hello-world-master/express" as the zip archive adds one directory level for itself.
 - Press the create button
7. Press the blue console button to watch the deployment process (optional)
8. Press the start button to start the environment
9. Press one of the links in the "App" or "Env" column in the app view to open the app/env 
11. If you deployed a static app, you also need to setup a path for where the static files are served from, we don't do this automatically for security reasons, open the "Static environment settings" (the static settings will appear in the app view when you have at least one static environment)
 - For Angular Dart, enter route pattern "/" and directory "build/web" and press "Add"
 - For Angular JS, enter route pattern "/" and directory "/" and press "Add"
12. Press the blue console button to watch the output of the server process (optional) 

