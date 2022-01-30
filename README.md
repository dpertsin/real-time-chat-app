[![Open in Visual Studio Code](https://open.vscode.dev/badges/open-in-vscode.svg)](https://open.vscode.dev/dpertsin/real-time-chat-app)
![Contributors](https://img.shields.io/github/contributors/dpertsin/real-time-chat-app?style=plastic)
![Forks](https://img.shields.io/github/forks/dpertsin/real-time-chat-app)
![Stars](https://img.shields.io/github/stars/dpertsin/real-time-chat-app)
![Licence](https://img.shields.io/github/license/dpertsin/real-time-chat-app)
![Issues](https://img.shields.io/github/issues/dpertsin/real-time-chat-app)

<a href="https://www.prtmedia.gr/">
    <img alt="PRTmedia" src="https://www.prtmedia.gr/wp-content/uploads/2021/11/prtmedia-logo-full.svg" width="165"/>
</a>

# Chat Pager Application
You can check the [demo](https://chat-pager-prt.netlify.app/).
You can register with your own username and picture or you can use the demo account with **username: demo** and **password: demo**.

## Project Description
This is a full Realtime Chat Application like Slack or Discord made with React.js on the front end, Node.js on the back end and the entire chat is powered with [getstream.io](https://getstream.io/) . You can easily create a group chat (channel) and add your friends in it, at this channel you and your friends can talk at realtime, without a delay, you can send Gif with typing in the chat `/giphy (name)`, flexibility to implement reactions to messages just like you see with Slack, Facebook or iMessage, and many other Features you can check [here](#features). You can build your own Chat Application and talk with your friends.


## Table of Contents
<ul>
    <li>[Features](#features)</li>
    <li>[Built using](#built-using)</li>
    <li>[Structure](#structure)</li>
    <li>[Roadmap](#roadmap)</li>
    <li>[Contributing](#contributing)</li>
    <li>[Feedback](#feedback)</li>
    <li>[Deployment on the Web](#deployment-on-the-web)</li>
    <li>[Running app locally](#running-app-locally)</li>
    <li>[Credits](#credits)</li>
    <li>[License](#license)</li>
    <li>[Enjoy!](#enjoy!)</li>
</ul>

### Features

- The app allows you to do certain actions, it allows you to login/logout and to register.
    - Note: You can use the demo account with **username: demo** and **password: demo**
- It has Message Reactions
    - Flexibility to implement reactions to messages just like you see with Slack, Facebook or iMessage.
- It has Thread Replies
    - Improve the user experience by visually grouping chat messages within their replies.
- It allows the user to search for a specific channel or user.
- URL Enrichment
    - Automatically show image, text and video previews of the URLs that users are sending.
- User Presence
    - Show when a user was last active and if they are currently online. We also support user invisibility.
- Flexible Permissions
    - Control what regular users, administrators, moderators or custom user roles are allowed to do. For example, you as an admin can ban a user or mute a user.
- Slash Commands
    - For example, you can send Gif with typing in the chat `/giphy (name)`.
- You can mention anyone with `@(name)`.
- You can create a group chat (channel) and make it Private or Public.
    - In **Private** you can add your friends to join and talk to each other.
    - In **Public** anyone can join and talk.
- You can drop any image in the chat to share.
- It also has a private/direct Message.
- You can edit your channel (rename it or delete/add users)
    - **REMEMBER** when you are creating/renaming a channel don't use space ` `, you have to put `-`. For example, my-channel.

### Built using

For the past few months I have been working with **React, JavaScript, JSX and Node.js**, so this is what I am using to build this app

- **ReactJS**: Front-end framework
- **NodeJS**: Back-end
- **GetStream**: The entire chat is powered by GetStream

### Structure

```sh
CHAT-APPLICATION/

├ client          # Client files
├── public         # Public files
├── src            # Source files
├──── assets       # Assets files
├──── components   # Components files


├ server          # Server files
├── controllers   # Controllers files
├── routes        # Routes files
```

---

## Roadmap

There are still some issues at the moment so if you want to contribute check it out [open issues](https://github.com/dpertsin/real-time-chat-app/issues) for a list of issues and improvements.

## Contributing

if you are interested in helping it would be great any contributions will be welcomed.

## Feedback

like mentioned earlier there are still bugs that need to be worked out, if you find and see and issue please open one issue or if you need/want a feature you can also make a request for said feature.

## Deployment on the Web

I am a big fan of React and the **Netlify** team so it's only natural to be deployed there.
But for the server side I am using **Heroku**.

## Running app locally

If you wish to contribute or add a feature

`git clone https://github.com/dpertsin/real-time-chat-app.git`

`git checkout -b your_name`

on the server file create a `.env` and put the Stream keys so your app can work.
```
STREAM_API_ID=app id goes here 
STREAM_API_KEY=api key goes here
STREAM_API_SECRET=api secret goes here
```

Please use `npm` as package manager to run `npm start`
**IMPORTANT** before you type `npm start` you have to `cd .\client\` and then start your application.

## Credits

I want to thank adrianhajdin for helping me create this.

## License

I want it simple and permissive. That's why I am using [MIT License](https://github.com/dpertsin/real-time-chat-app/blob/main/LICENSE).
The MIT License is short and to the point. It lets people do almost anything they want with your project, like making and distributing closed source versions.

## Enjoy!
Don't forget to play around with the code and practice with it! 

You can connect with me on:
[<img align="left" alt="prtmedia.gr" width="22px" src="https://raw.githubusercontent.com/iconic/open-iconic/master/svg/globe.svg" />][website]
<!-- [<img align="left" alt="PRTmedia | YouTube" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/youtube.svg" />][youtube] -->
[<img align="left" alt="PRTmedia | Facebook" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/facebook.svg" />][facebook]
<!-- [<img align="left" alt="PRTmedia | Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />][twitter] -->
[<img align="left" alt="PRTmedia | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]
[<img align="left" alt="PRTmedia | Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />][instagram]

<br />

Last but not least, give this project a star if you liked it. 








