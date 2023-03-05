# BobbyJ_ECommerce

  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

  ## Description
  This application uses Sequelize to interact with a mySQL database. User's can make get, single id get, post, put, and delete requests.

  ## Table of Contents
  - [Walkthrough_Video](#Walkthrough_Video)
  - [Thumbnail](#Thumbnail)
  - [Installation](#Installation)
  - [Usage](#Usage)
  - [License](#License)
  - [Contributing](#Contributing)
  - [Tests](#Tests)
  - [Questions](#Questions)

  ## Walkthrough Video
  [Link to Walkthrough](https://drive.google.com/file/d/1gC4sjh64viZrUSP5RY1PjWjkW1cMwZwV/view?usp=sharing)

  ## Thumbnail
  ![Thumbnail](images/thumbnailEcommerce.png)

  ## Installation
  To install necessary dependencies, run the following command:

  ` npm i `

  ## Usage
After the dependencies are installed, create a .ENV file and fill it with your connection information: (Don't forget to update your password)

```bash

DB_NAME='ecommerce_db'
DB_HOST='localhost'
DB_USER='root'
DB_PASSWORD='UPDATE YOUR PASSWORD HERE'

```
Now, you can proceed to create the datbase schema in MySQL Terminal:

```bash
 #under MySQL terminal
    mysql -u root -p
 # to create the DB schema
    db/SOURCE schema.sql
```

Then, start working with the main file:

```bash
  node seeds/index.js
```
Finally, the program can be run using:

``bash
  npm start
``

## License
  MIT
  Copyright 2023 rjclemmer

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.;

  

  ## Questions
  If you have any questions clemmer.robert.j@gmail.com. You can find more of my work on GitHub at [rjclemmer](https://github.com/rjclemmer).


  