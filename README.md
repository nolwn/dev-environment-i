# How do I set this up?

First, you need to clone this repository onto your computer. Click "Code" and then click that little clipboard icon. That pops the link to this repository into your clipboard.

Now open your terminal. Navigate to your GitHub folder:

`cd ~/GitHub`

Enter this into Terminal:

`git clone`.

and after that paste the contents of your clipboard into the terminal. It should say something like:

`git clone https://github.com/nolwn/dev-environment-i.git`

Actually... that's _exactly_ what it should say! Press Return.

If you type `ls` you should now see a new directory called `dev-environment-i`. Type:

`cd dev-environment-i`

and you will enter the directory. If you type

`ls -la`

it will list the files and folders in the directory. They should match what you see on this GitHub page.

Type

`npm install`

and press Return. We didn't talk about what would happen if you typed this command without naming a package. It installs all the dependencies and devDependencies in the current directories `package.json`. Everything I decided to install for this npm package (which in this case is just `live-server`) will be added to this repo so it can used with my code.

Now that you have the repo, and you have installed it's dependencies, you can run it's start script:

`npm run start`

Boom!
