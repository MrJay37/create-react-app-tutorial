# `create-react-app` Tutorial

While helping a friend learn react, I decided to make this repository. It's dedicated on learning how React JS works and along with that, also brush up some fundamentals about HTML, CSS and JavaScript.

I have been developing front end for 4 years now and I'd like to design this project based on my own experiences. I am not a professional trainer and I certainly cannot provide you any certification for learning this. The end-to-end learning series that is project is is based on how I usually go about developing front-end projects in React JS. Welcome to my tutorial!

## Glossary

I understand that this may be your first time going through a software development tutorial so I will maintain a glossary table here that you can come back to refer to

| Term | Full form | Description |
| ---- | --------- | ----------- |
| UI  | User Interface | The way an application looks/feels like to the user|
| IDE | Integrated Development Environment | A software that allows you to develop code with several helping features other than just a text editor 
| VS | Visual Studio | Software brand/company
| ctrl | Control | Short cut for ctrl key on your keyboard


## Setup 

I had the good fortune of starting this project on a fresh laptop. I am using Windows but I'm sure this can be done on a Mac or Linux also. Here's how I started setting up my machine.

### Step 1: Install VS Code  
I insist using VS Code for the incredible UI and dev tools that the IDE provides. You can find the software [here](https://code.visualstudio.com/).

Note: If you're already used to using another development solution, feel free to proceed with that. The tutorial will focus on steps using VS code but they should be fairly easy to convert into your choice of development implementation/IDE.

### Step 2: Install node.js

`node.js` is a run-time environment that interprets JavaScript and executes it. Node can be installed [here](https://nodejs.org/en/).

Note: At the time of setting this tutorial up, I had the option of 20.9.0 LTS. It might be different when you do it, but I would still recommend using the LTS version and not Current.

After clicking on the download option, an executable file will be downloaded, run the file after the download is over.

The installation might require administrative rights for Windows so make sure you have that.

### Step 3: Install `git`

I'll explain more about git later but it's a good thing to have in your system. You can install `git` [here](https://git-scm.com/)

Run the installer after it has been downloaded.

### Step 4: Restart your system

Windows will require a system restart to register node installation

### Step 5: Create a project folder

At the time of this tutorial setup, I created a folder called `Projects` in the Documents 

Open this folder in VS code:

* Open VS code (you can find the app using the Start menu)
* On the top left corner, click File -> Open Folder
* In the file browser, open the folder you created above

After opening the folder, open the VS code terminal. You can do this by pressing `ctrl + ~` keys

### Step 6: Setup React app

`create-react-app` should be configured in your system already while installing node. In the terminal type in the following command

```
npm install -g npm
```

The command above is just to make sure npm is ready to use when needed. Then run the following command

```
npx create-react-app react-app
```

The initializing toolkit might prompt some questions. For the sake of this tutorial, click `enter` whenever those questions come on. After the toolkit has finished running all commands, run the following commands in the commandline

```
cd react-app
code .
```

This will open a new VS code window. We will proceed working in this window, so you can close the previous one. Run this command in the commandline of the new VS code window

```
npm run start
```

The react-toolkit will run a script called `start` and will tell you in the commandline where the server is running. Most likely, it will say http://localhost:3000/ . Click on this link and it should show you a page with hyperlink that says `Learn React`


Congratulations, you have set up React JS and created your first app!

## Markdown

It is good practice to have a README file in your project, it will help with documentation.

You can find markdown syntax [here](https://www.markdownguide.org/basic-syntax/)