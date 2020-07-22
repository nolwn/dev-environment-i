# What is this?

This is a website that reviews some of the things we talked about on Tuesday. It both explains what we talked about, and also it's an example of it. You can admit it, I'm super clever.

# How do I set this up?

First, you need to clone this repository onto your computer. Click "Code" and then click that little clipboard icon. That pops the link to this repository into your clipboard.

Now open your terminal. Navigate to your GitHub folder:

`cd ~/GitHub`

Now paste the contents of your clipboard into the terminal. It should say something like:

`git clone https://github.com/nolwn/dev-environment-i`.

Actually... that's _exactly_ what it should say! Press `Return`.

If you type `ls` you should now see a new directory called `dev-environment-i`. Type:

`cd dev-environment-i`

and you will enter the directory. If you type

`ls -la`

it will list the files and folders in the directory. They should match what you see on this GitHub page.

Type

`npm install`

We didn't talk about what would happen if you typed

`npm install`

without naming a package, but I'll tell you what it does now: it installs all the dependencies and devDependencies in the current directories `package.json`. Everything I decided to install for this npm package will be installed now on your computer.

Now that you have the repo, and you have installed it's dependencies, you can run it's start script:

`npm run start`

Boom!

---

Sidenote: The `~` is a short way of indicating your home folder! In your case it's short for `/Users/jakespalding/`, so the command above is the same as:

`cd /Users/jakespalding/GitHub`

It's just shorter and easier to type.

---
