# E-Commerce Backend

![MIT License](https://img.shields.io/badge/license-MIT-important)

## Table of Contents

- [Description](#description)
- [Built With](#built-with)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [License Section](#license)
- [How To Contribute](#how-to-contribute)
- [Tests](#tests)
- [Contact Me](#contact-me)

## Description

This project creates the back-end code for an e-commerce site. This application uses Express.js API and Sequelize to interact with a MySQL database. The database is created using mySQL with models and associations. The API Routes are created using RESTful CRUD methods displayed in my walk through videos. Since there is no front-end code, the application was tested using Insomnia.

## Built With

- HTML
- CSS
- JavaScript
- MySQL
- Sequelize
- dotenv (to create the environmental variables)
- Insomnia (for testing)

## Installation Instructions

### Node.js Installation

Make sure that you have Node.js installed on your computer by entering node -v in the command line. If successful, the command prompt will return a version number. If not, try reinstalling Node.js by following this link: https://nodejs.org/en/ and clicking on the LTS version. If you are on Windows, make sure to look for the section that says `Download for Windows (x64)`. If you are using macOS, make sure to look for the section that says `Download for MacOS (x64)`

### Clone the Code

Once Node.js is downloaded, click on the green code button and copy the link to this repository. Then open up your favorite code editor and open the terminal. In the terminal use `cd` to go to the root directory you want this repository to be cloned to. Finally, in the terminal, type `git clone <file link>` to clone this repository to your directory.

### npm Package Installations

You must also install the Express.js, Sequelize, and MySQL2 npm packages to run the server. Since these are npm packages instead of being built directly into node.js, you must type `npm i` into the command line to allow the npm packages to be installed.

## Usage Instructions

To use this application follow the steps below.

1. To connect to the MySQL database, run `mySQL -u root -p` in the command line and enter your MySQL password.

2. Run `source Develop/db/schema.sql` in the MySQL command line to populate the database and then type `quit` to exit MySQL.

3. Run `npm run seed` in the command line to seed the file. If the file was properly seeded, you should see something similar to the screenshot below.

![Seeded Code](https://user-images.githubusercontent.com/88728912/153438844-408d0b6e-9ace-4467-8af8-907d5aa1d152.png)

4. Connect to the server by typing `npm start` in the command line. If the server connected successfully, you should see something similar to the screenshot below.

![Start Server](https://user-images.githubusercontent.com/88728912/153439061-d11ec891-4c4c-4be2-906e-0f6efa3418ba.png)

5. To test the application, follow the Screencastify videos below. For more information on Insomnia, follow this link: https://docs.insomnia.rest/.

### Screencastify

- For a walkthrough of MySQL and how to seed and start the server, watch this walkthrough: 
  
  https://watch.screencastify.com/v/W0BAlXs3rJCkJSc915V5

- For a walkthrough of how the routes work using Insomnia, watch this walkthrough: 

  https://watch.screencastify.com/v/5hjYtenjXLqdBQXIpEg5

## License

Permission to use this application is granted under the MIT license.
Click on the link for more information: [MIT License Information](https://opensource.org/licenses/MIT)

## How To Contribution

To contribute, refer to the installation instructions above.

## Tests

There is no command for running these tests. To test the application, download insomnia and watch the Screencastify videos in the usage section to seed the data, start the application and test the routes in Insomnia. For more information on Insomnia, follow this link: https://docs.insomnia.rest/.

## Contact Me

GitHub Link: (https://github.com/nicnolen)<br>
Email Address: <nicnolen@ymail.com>
