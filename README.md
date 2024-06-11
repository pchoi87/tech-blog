# Tech Blog

## Description

Tech Blog is a CMS-style blog site similar to a WordPress site, where developers can publish their blog posts and comment on other developers' posts. This application follows the MVC paradigm and is built using Node.js, Express.js, Handlebars.js, Sequelize ORM, and PostgreSQL. It also includes user authentication using express-session and bcrypt.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/tech-blog.git

2. Navigate to the project directory:
   cd tech-blog
3. Install the necessary dependencies 
   npm install 
4. Create a `.env` file in the root directory and add your database credentials: 
   DB_NAME=tech_blog
   DB_USER=your_postgres_username
   DB_PASSWORD=your_postgres_password
5. Ensure PostgreSQL is running and create the database: 
   psql -U your_postgres_username -c "CREATE DATABASE tech_blog;"

## Usage 

1. Start the application: 
   node server.js 
2. Open your brwoser and navigate to  `http://localhost:3001` to view the application. 

## Features 

   - User authentication (signup, login, logout)
   - Create, read, update, and delete blog posts
   - Comment on posts
   - Responsive design using Handlebars.js templates

## Technologies Used

   - Node.js
   - Express.js
   - Handlebars.js
   - Sequelize ORM
   - PostgreSQL
   - bcrypt (for password hashing)
   - express-session (for session management)

## License
This project is licensed under the MIT License. 

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any feature requests or bug fixes.

## Questions
If you have any questions about the project, please open an issue or contact me directly:

GitHub: https://github.com/pchoi87
Email:  choi.phil87@gmail.com 


