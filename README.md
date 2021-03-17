# s3-Bucket-upload-api

A REST service using nodejs and expressjs static files to Amazon S3. 

---
## Requirements and Dependencies

For development, you will only need Node.js and a node global package, express, and a few dependencies installed in your environement to properly run this service.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs=15.7.0
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v15.7.0

    $ npm --version
    6.1.0

## Install

    $ git clone https://github.com/magboola/s3-Bucket-upload-api.git
    $ cd s3-Bucket-upload-api
    
To install all the dependencies in the `package.json` file, run.
    
    $ npm install

You can then run the service with the following command 
    
    $ nodemon index.js
####    
NOTE: The service is running in port `3000` but can be easily changed by changing the environment variable in a `.env` file in the root folder. Also, other private information can be set in this file e.g the `db_name`, `db_password` and `db_host`. Then add it to the `.gitignore` file. `node_module` should also be added to the `.gitignore` file
