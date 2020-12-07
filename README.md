# Developers-Social-Media

A place where developers from various fields can check on each others profile as well 
as can see their github repos and can post something,comment on others post and have to login using their email id.

# Tech Stack

* ReactJS
* MongoDB
* NodeJS
* ExpressJS

# How to run the file
1. clone the github repo on your local desktop.
2. Run `npm i` in the root folder.
3. Go to the client folder and run `npm i` again.
4. In the root folder inside the config folder create a file named `default.json` and add the following code:
```JSON 
{
  "mongoURI": "YOUR MONGODB URL",
  "jwtSecret": "YOUR SECRET TOKEN",
  "githubClientId": "YOUR GITHUB CLIENT ID",
  "githubSecret": "YOUR GITHUB SECRET"
}
```
5. Now open the terminal in root folder and run `npm run dev` to start both the client and server server.
