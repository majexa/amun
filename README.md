# Amun Static Server

## Installation

Create project folder

    mkdir project
    cd project
    
Create file structure like that

    build/public/some/static/stuff
    build/public/index.html
    
Get server from asdasdsa

    git clone https://github.com/majexa/amun-static-server.git server
    cd server
    npm install
    
At the final your project file structure will be looks like:

    project/build/public/index.html
    project/build/public/...
    project/server/index.js
    project/server/package.jeon
    project/server/...
    
Create `.env` with contents like:

    PORT = 8080    
    
Run the server:

    node project/server/index.js
