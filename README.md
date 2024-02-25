# web-tech-lab
HTML Hello World Program
Welcome to the HTML Hello World program repository! This project is a simple demonstration of a "Hello, World!" program using HTML. Follow the steps below to set up and run the program.

Prerequisites
Before you begin, ensure you have the following installed:

Visual Studio Code
Node.js (for using a linter)
Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/html-hello-world.git
cd html-hello-world
Install Node.js Dependencies:

bash
Copy code
npm install
This installs the necessary dependencies, including the linter.

Open in Visual Studio Code:

bash
Copy code
code .
Configure VSCode Linter:

Ensure you have the VSCode ESLint extension installed.
Open the VSCode settings (settings.json) and add the following configuration:
json
Copy code
"editor.codeActionsOnSave": {
  "source.fixAll.eslint": true
},
Run the HTML Hello World Program:

Open the index.html file in your browser, or use a local development server if you prefer.
Linting and Code Quality
Linting is set up in this project to ensure code quality. The ESLint configuration can be found in the .eslintrc.json file.