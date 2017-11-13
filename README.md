# Full Stack JS Project - DevJobs - 01 - Node Express Starter

## Context
You are going to build a full stack web application with node.js + React. In order to become familiar with how a node project works, you will be responsible for configuring the  initial major components of the project.  

- **express server**
- application routes
- views
- api layer
  - data access
  - data models (ORM)
  - RESTful routes


## The Assignment
For this assignment, we will focus on creating the **express server**.

You will need to install the express package from NPM.

In `server.js` You will need to:

- import the express application with `require()`
- initialize the express application
- create a basic route handler on the home path (`/`)
- return the contents of the `home.html` file from the `src/views/` directory by using the `fs.readFile()`
- make the app listen on port 3000

### Setup Instructions

In Terminal:

```sh
# (1) navigate to your assignments directory
cd ~/Documents/muktek/assignments

# (2) Clone the Project and navigate into it
git clone https://github.com/muktek/build--node-project-starter.git project--devjobs

cd project--devjobs

# (3) Install project dependencies
npm install

# (4) Remove the remote origin repository
git remote remove origin

```