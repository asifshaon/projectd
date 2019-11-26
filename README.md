``` 
* Generated by
* 
*      _____ _          __  __      _     _
*     / ____| |        / _|/ _|    | |   | |
*    | (___ | | ____ _| |_| |_ ___ | | __| | ___ _ __
*     \___ \| |/ / _` |  _|  _/ _ \| |/ _` |/ _ \ '__|
*     ____) |   < (_| | | | || (_) | | (_| |  __/ |
*    |_____/|_|\_\__,_|_| |_| \___/|_|\__,_|\___|_|
*
* The code generator that works in many programming languages
*
*			https://www.skaffolder.com
*
*
* You can generate the code from the command-line
*       https://npmjs.com/package/skaffolder-cli
*
*       npm install -g skaffodler-cli
*
*   *   *   *   *   *   *   *   *   *   *   *   *   *   *   *
*
* To remove this comment please upgrade your plan here: 
*      https://app.skaffolder.com/#!/upgrade
*
* Or get up to 70% discount sharing your unique link:
*       https://app.skaffolder.com/#!/register?friend=5ddd45b5c758666a71708191
*
* You will get 10% discount for each one of your friends
* 
```


```
   _____ _          __  __      _     _           
  / ____| |        / _|/ _|    | |   | |          
 | (___ | | ____ _| |_| |_ ___ | | __| | ___ _ __ 
  \___ \| |/ / _` |  _|  _/ _ \| |/ _` |/ _ \ '__|
  ____) |   < (_| | | | || (_) | | (_| |  __/ |   
 |_____/|_|\_\__,_|_| |_| \___/|_|\__,_|\___|_|   

  _   _           _           _  _____ 
 | \ | |         | |         | |/ ____|
 |  \| | ___   __| | ___     | | (___  
 | . ` |/ _ \ / _` |/ _ \_   | |\___ \ 
 | |\  | (_) | (_| |  __/ |__| |____) |
 |_| \_|\___/ \__,_|\___|\____/|_____/ 
```

This project was generated by Skaffolder

--------------
## INSTALL DATABASE
--------------

* Download the latest production release of MongoDB from [here](https://www.mongodb.com/download-center?_ga=2.123194891.1822248697.1522395660-2086062422.1522395660#production)

* Open the file to launch the wizard.

* MongoDB requires a data directory to store all data. Create the directory `/data/db` on the drive from which you'll start MongoDB.

--------------
## START APPLICATION
--------------

To launch the application start a local instance of MongoDB, open a terminal in this folder and type:
``` bash
$ npm install
$ npm start
```

Go to http://localhost:3000

--------------
## CONFIGURE
--------------

Set database config in `properties.js`

--------------
## START WITH DOCKER
--------------

* To start the application with Docker:

    * Install Docker

    * Run command:
    ``` bash
    docker-compose up
    ```
    * Go to http://localhost:80


* When code changes you need to rebuild container running:
``` bash
docker-compose up --build
```

--------------
## USING SKAFFOLDER-CLI
--------------

With Skaffolder-CLI you can easily manage your Skaffolder project from command line and customize your generator template from your IDE.

Install Skaffolder-CLI with
``` bash
$ npm install -g skaffolder-cli
```

Login running the command
``` bash
$ sk login
```

Generate your project with the command
``` bash
$ sk generate
```

You can customize your generator template working with files in .skaffolder folder in your project root.

Please refer to https://skaffolder.com/#/documentation/skaffolder-cli for more information.

