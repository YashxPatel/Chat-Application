# ToDo Application
## ToDo App (PERN Stack)

This is a simple ToDo app built using the PERN stack (PostgreSQL, Express, React, Node.js). The app allows users to create, view, edit, and delete tasks.
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)  

## Features

- Create tasks with a title, description, and date.
- Edit existing tasks to update their details.
- Delete tasks that are no longer needed.
- View a list of all tasks, including their current status.

## Prerequisites

- Node.js and npm (Node Package Manager) installed on your machine.
- PostgreSQL database server installed and running.

## Installation

Clone this repository to your local machine
~~~bash
git clone https://github.com/YashxPatel/Todo_app.git
~~~

Navigate to the project directory
~~~ bash
cd pern-todo-app
~~~

Install server dependencies
~~~bash
cd server
npm install
~~~

Install client dependencies
~~~bash
cd ../client
npm install
~~~


## Configuration

1. Set up your PostgreSQL database:
- Create a new PostgreSQL database for the ToDo app.
- Update the `server/db.js` file with your database connection details.

2. Configure CORS (Cross-Origin Resource Sharing) settings if your client and server are hosted on different domains. Update the `server/index.js` file as needed.

## Usage

Start the server:
~~~
cd server
npm start
~~~

Start the client:
~~~
cd ../client
npm start
~~~

Access the app in your web browser at 
~~~
http://localhost:3000
~~~

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test thoroughly.
4. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
