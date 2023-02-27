## Project 3

Update ubuntu

`sudo apt update`

Upgrade ubuntu

`sudo apt upgrade`

Geting the location of Node.js software from Ubuntu repositories.

```bash
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
````

Install Node.js on the server with the command below

`sudo apt-get install -y nodejs`

Verify the node installation with the command below

`node -v`

Verify the node installation with the command below

`npm -v`

###Application Code Setup

Create a new directory for your To-Do project:

`mkdir Todo`

Now change your current directory to the newly created one:

`cd Todo`

Next, you will use the command 'npm' init to initialise your project, so that a new file named 'package.json' will be created.

`npm init`

Run the command 'ls' to confirm that you have package.json file created

