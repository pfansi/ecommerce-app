# ecommerce back end app

![License: MIT](https://img.shields.io/badge/License-MIT-blue)

## Table of Contents:

- [Git-Repository](#git-repository)
- [Demo-Video](#walktrough-video)
- [Description](#description)
- [Pseudo-code-Description](#pseudo-code-description)
- [Build-Process](#build-process)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)
- [Screenshots](#screenshots)

## Git Repository

I created a git repository folder that will host the finished project. The Repository will be found [here](https://github.com/pfansi/ecommerce-app)

## Link to the walktrough video

Application video [demo](https://drive.google.com/file/d/1NVzOwZAUUZYEC7-LWJ3extXBNmCoQ2hG/view?usp=sharing)

## Description:

This project required to build a Node.js ecommerce back end application that will have the same fundanmental achitecture such as shopify or Woocommerce.
The ecommerce application will be link to a Mysql database.
It will use the the Express.js API and Sequelize to intereact with the database.

## pseudo code description

## Build process

- created a repository and a readme.md file for the project
- created connections to the database and env file filed
- connected and created a database ecommerce_db
- installed all the necessary dependency to run the app in Node.js
- created model file and the relationship between table model
- created category , product and tag routes
- create server.js and imported connection and sync sequilize model to the database

## Installation:

---

Run this command to install dependencies:

  <pre><code>
  npm install
  </code></pre>

## Usage:

---

Run this command to start the app:

  <pre><code>
  npm run start
  </code></pre>

---

Run this command to seed data to the database

  <pre><code>
  npm run seed
  </code></pre>

## Tests:

Run this command to run the test

<pre><code>
  npm run test:watch
  </code></pre>

## License:

[License: MIT](https://opensource.org/licenses/MIT)

# This Project is licensed under the MIT license

## Contributing:

Project is open for contributions.

## Questions:

- **Contact details:**
  - Github: [@pfansi](https://github.com/pfansi)
  - Email: pfansi76@gmail.com

## Screenshots

- Demonstration of how to create the schema from the MySQL shell.
  ![screenshot](./assets/images/seed_and%20_tables.PNG)
