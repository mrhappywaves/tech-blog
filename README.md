# techno-blog

## Table of contents
<details>
<summary><strong>Click to see the contents table</strong></summary>

- [Description](#description)
- [Installation Instructions](#installation-instructions)
- [Usage Examples](#usage-examples)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [Testing](#testing)
- [Contact Me](#contact-me)
</details>

## Description
An all tech blog built on MVC (Model-View-Controller) principle. 

## Installation Instructions
To get the project set up locally please follow the following steps:
 1. Make sure you have `node.js` installed 
 2. Make sure you have `mysql` installed and a password set
 3. Make sure you have `Postman` or `Insomnia` installed for testing API calls. 
 4. Clone this repository https://github.com/mrhappywaves/techno-blog to your local machine
 5. Open the repository with an IDE of your preference
 6. Switch your current directory to the local repository path (Ex: '..\Desktop\techno-blog')
 7. In your IDE console run - `npm i` 
 8. In the selling-it folder create `.env` file 
 9. Fill out the the .env file by providing your mysql details: DB_USER, DB_PW, DB_NAME. (Note: DO NOT USE COMMAS in the file, example formatting: `DB_NAME=blog_db`)
 10. Using your IDE console run command - `mysql -u root -p`. Enter your password and click Enter.
 11. Now under mysql run two commands separately: 1. `DROP DATABASE IF EXISTS ecommerce_db`; 2. `CREATE DATABASE ecommerce_db`; (Alternatively run this command: `SOURCE db\schema.sql`)
 12. Now run `quit` command 
 13. Second to last, in your IDE console run - `npm run seed` to seed pre-existing data.
 14. Lastly, run - `npm start` to start the application (by default application is set to run on the 3001 port, ex: http://localhost:3001/)
 
## Usage Examples
Application can be used to share knowledge with a tech community as well as participate in blog article discussions. Below is video of the app walkthrough:

Video demo:

https://user-images.githubusercontent.com/94947579/169802522-608c83d9-d604-4a2b-b5b7-49d51f1f3455.mp4


Link to the live app deploy on Heroku:
https://shrouded-bastion-27212.herokuapp.com/


## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features  
The app allows users to:
 1. Authenticate (Sign up/in/out).
 2. View, create, modify blog posts.
 3. View, leave, modify comments and replies.

## Testing
There are no tests written for this application yet. 

## Contact me
Please reach out with any questions regarding the application:
 - My email is mrhappywaves@gmail.com
 - You can find me on Github via my username - mrhappywaves, or just follow this link https://github.com/mrhappywaves
