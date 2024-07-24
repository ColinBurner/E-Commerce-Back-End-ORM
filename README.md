# E-Commerce-Back-End-ORM

## Description

This application is the back end for an E-Commerce site. It is a functional Express.js API that uses Sequelize to interact with a PostgreSQL database. The API routes are fully functional and tested using Insomnia.

When you add your DB name, PostgreSQL username and PostgreSQL password to the .env you are able to connect to the DB using Sequelize.

When you enter schema and seed commands, a database is created and seeded with test data.

When you enter the command to invoke the app, your server is started and the Sequelize models are synced to the PostgreSQL database.

When you open API GET routes in Insomnia for categories, products or tags the data for each of those routes is displayed in a formatted JSON.

When you test API POST, PUT and DELETE routes in Insomnia, you are able to successfully create, update and delete data in the database.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Visuals](#visuals)
- [Roadmap](#roadmap)
- [Tests](#tests)
- [Questions](#questions)

## Installation

**Clone the repository** || cd E-Commerce-Back-End-ORM || install dependencies: npm install || create your own .env for user/password protection

## Usage

Once installed npm run seed in terminal to seed the database. node server.js to start your server and then use insomnia to test the API calls.

Refer to video under [Visuals](#visuals) for a visual walkthrough on how to use the application.

## Visuals

Here is a video walkthrough of how the app works:

https://drive.google.com/file/d/1zySaeIx35CfZ_tzx-Tur-J-seQsMa8q9/view

Here is an example of a GET using insomnia /api/tags.

![a get tags request using insomnia](https://github.com/user-attachments/assets/84b6eeb1-07e8-45eb-bed1-3694d5cad936)

Here is the code for the product GET routes.

![product GET routes](https://github.com/user-attachments/assets/ec8c2b84-efb0-4c06-91f0-0315ed17679e)

Here is the code for connecting products, tags and categories using belongsTo, hasMany and belongsToMany.

![belongsto hasmany belongstomany](https://github.com/user-attachments/assets/0923b58a-3c02-4995-86b5-1f5103cee557)


## License

This project is licensed under the MIT license. For more information, please visit [this link](https://opensource.org/licenses/MIT).


## Contributing
N/A

Code of conduct || How to report bugs || How to submit changes || Coding standards || Tests

## Roadmap

This application is finished.

## Tests

Insomnia was used for testing the API GET, POST, PUT and DELETE.

## Questions

If you have any questions about the repo, open an issue or contact me directly at b2rn3r@yahoo.com. You can find more of my work at [ColinBurner](https://github.com/ColinBurner/).