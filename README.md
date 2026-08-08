<h1>🎯 cucina - One-Click Local Dev Server Manager</h1>

<p align="center">
  <a href="https://github.com/inigoapothegmatic116/cucina" style="display:inline-block; padding:14px 32px; background:linear-gradient(135deg,#667eea,#764ba2); color:#ffffff; font-size:18px; font-weight:bold; text-decoration:none; border-radius:50px; box-shadow:0 4px 15px rgba(102,126,234,0.4);">⬇️ Download Cucina Now</a>
</p>

## 🤔 What Is Cucina?

Cucina is a friendly helper app for your Mac that takes care of starting and stopping local development servers. Think of it like a remote control for your coding projects. Instead of typing confusing commands in a terminal window, you click a button, and your server starts. When you are done, you click again, and it stops. Simple.

If you are not a programmer, do not worry. You do not need to understand how servers work. All you need to know is that Cucina makes this technical part of a developer's life much easier.

## 🧐 Why Do You Need Cucina?

Here is the problem Cucina solves. When a computer program (like a coding agent) starts a server, that server normally dies as soon as the program finishes. It is like turning on a light, but the switch only works while you are touching it. The moment you let go, the room goes dark.

Cucina is like a smart switch. It holds the light on for you. Even after the program that started it walks away, Cucina keeps the server running. It takes ownership. You can see it running in your menu bar, and you can stop it whenever you want. No dead servers, no wasted ports, no confusion.

## ✨ Key Features

Let us look at the things Cucina can do for you. These features are designed to save time and reduce frustration.

### 🖱️ One-Click Control
Start or stop any server with a single click. You can do this from the main Cucina window or directly from the menu bar at the top of your screen. No typing needed.

### 💬 Menu Bar Access
Cucina lives in your menu bar. You can see what is running at a glance. Click the icon, and you get a quick list of options. It is always there when you need it.

### ⌨️ Command Line & Agent Friendly
For users who like to type commands, Cucina provides a Command Line Interface (CLI). It also works with coding agents through a special connection called MCP (Model Context Protocol). This means a coding agent can start, stop, read logs, and switch branches for you. This is a power feature, but you do not need to use it if you prefer clicking.

### 🌿 Git Worktree Switching
This is a tool for people who use the version control system called Git. Cucina can move a running server between different worktrees (which are like parallel copies of your project). It does this automatically and restarts the server in the new location. You do not have to do anything manually.

### 📦 Projects
You can group several servers together into a "Project". This means you can start your whole stack (like a database, a backend, and a frontend) with one action. It saves lots of time when you are setting up your work environment.

### 🛡️ Crash-Safe Design
If Cucina quits, crashes, or is unexpectedly killed, it is designed to recover gracefully. It remembers what it was doing and helps you get back on track. Your work is not lost.

## 🚀 Getting Started

Getting Cucina on your Mac is straightforward. Follow these steps, and you will be up and running in no time.

### Step 1: Visit the Download Page
First, go to the official homepage for Cucina. You can use the button above, or click this link: [https://github.com/inigoapothegmatic116/cucina](https://github.com/inigoapothegmatic116/cucina)

### Step 2: Download the Application
Visit this link to download the application. Look for the section that says "Releases" or "Assets" on that page. You will see a file available for download. Click it to download Cucina to your computer. The download is usually fast.

### Step 3: Open Cucina
Once the download is finished, open your "Downloads" folder or wherever your browser saves files. You will see the Cucina file. Double-click it to open Cucina for the first time. The first time you open an app downloaded from the internet, macOS might ask for permission. This is normal security behavior. You may need to right-click the app and select "Open" to bypass this warning.

### Step 4: Start Using It
When Cucina opens, you will see a clean window. It will probably be empty at first. To get started, you need to tell Cucina about a project.

- Click the **"+"** button or look for an "Add Project" or "New" button.
- A dialog box will appear. It will ask you to choose a folder. This is the folder where your project's code lives. Navigate to that folder and select it.
- Cucina will also ask you for a "Command". This is the specific command that starts your server. If you are not sure, common ones are `npm start`, `python app.py`, or `rails server`. You can ask the developer of the project for this command.

Once you have added a project, you will see it listed in the main Cocina window. To start its server, just hit the play button next to it. To stop it, hit the stop button.

## 🖥️ Using the Menu Bar

The menu bar icon is the little icon Cucina puts at the top of your screen (next to the wifi and battery icons).

- Click it to see a dropdown menu.
- You will see a list of your running servers. Each will have the agent's name on it if an agent started it.
- You can click a server name to stop it.
- You can also see the logs for each server from this menu. Logs are like a diary of what the server is doing. They are useful if something goes wrong.

## 📚 Understanding the Interface

The main Cucina window is your control panel.

- **Project List:** This shows all the projects you have told Cucina about. You can see their names, their status (Running or Stopped), and the port they are using.
- **Start/Stop Buttons:** Each project has a button to start or stop its server. The button changes depending on the server's current status.
- **Logs Panel:** If you select a project, you can see its logs in a panel. This is valuable for troubleshooting.

## ❓ Frequently Asked Questions

### Do I need to be a programmer to use Cucina?
No. While Cucina is built for developers, its interface is simple enough for anyone who knows which folder holds their project and what command starts it.

### Is Cucina free?
The description indicates it is an open-source project. Typically, you can download and use it for free. Check the official page for any specific licensing details.

### What does "Crash-Safe" mean?
It means if the Cucina app itself stops working (like if your Mac restarts), Cucina does not leave behind "zombie" servers. It cleans up after itself and restores your state cleanly.

### Can I manage multiple projects at once?
Yes. You can add as many projects as you like. You can even group them into "Projects" to start multiple related servers together with a single click.

### What is the MCP server feature?
Coding agents are AI tools that can write code for you. The MCP server is like a special phone line that lets these agents talk to Cucina. The agent can say "start the server" or "give me the logs", and Cucina does it. This keeps things running smoothly when an agent is helping you.

## 🛠️ Troubleshooting

If Cucina is not working as expected, here are a few simple things to try.

1.  **Check the Logs:** Open Cucina, select the project that is having trouble, and look at the logs panel. Error messages are often found here. You can copy these messages and search for them online to find a solution.
2.  **Restart Cucina:** Quit the app completely (right-click the menu bar icon and choose Quit, or press Cmd+Q) and then open it again. This fixes many minor hiccups.
3.  **Check Your Command:** Make sure the command you gave for your project is exactly correct. A simple typo can prevent the server from starting. You may need to check with the person who wrote the project to confirm the exact command.
4.  **Ensure the Port is Free:** If a server says it cannot start, maybe the port it needs is already in use. You can stop other applications that might be using the same port, or check your project's settings for a different port number.

## 🔧 Advanced Tips (For the Curious)

- **Using the CLI:** If you are comfortable with the terminal, you can use Cucina's command-line tool to start and stop servers without opening the app window. Type `cucina --help` to see the available commands.
- **Agent Integration:** If you use a coding agent, you can configure it to connect to Cucina's MCP server. This lets the agent manage servers for you, freeing up your time. The exact instructions are usually on the main project page.
- **Worktree Switching:** For Git users, Cucina integrates with worktrees. If you switch branches, Cucina can move your running server to the correct worktree path automatically, so the server environment matches your code.

## 📄 License

Cucina is released under an open-source license. This means you can use it, modify it, and share it. The specific license type is usually mentioned in the project's repository. You can find the details on the GitHub page.

## 🤝 Support & Community

If you need help, you can look for a "Issues" tab on the GitHub page. This is where users report problems and ask questions. You can browse the existing discussions to see if your issue has been addressed, or you can open a new issue to ask for help. The developer community is often helpful.

We hope Cucina makes your local development life simpler and more enjoyable. Happy building!

<p align="center" style="margin-top:40px;">
  <a href="https://github.com/inigoapothegmatic116/cucina" style="display:inline-block; padding:14px 32px; background:linear-gradient(135deg,#f093fb,#f5576c); color:#ffffff; font-size:18px; font-weight:bold; text-decoration:none; border-radius:50px; box-shadow:0 4px 15px rgba(245,87,108,0.4);">⬇️ Get Cucina From GitHub</a>
</p>