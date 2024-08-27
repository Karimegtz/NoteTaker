# NoteTaker

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Description

NoteTaker is a simple and efficient application designed for small business owners and anyone who needs to write, save, and manage notes effectively. This application features an intuitive interface that allows users to write and save notes. The backend is powered by Express.js, which handles saving and retrieving notes from a JSON file.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Deployed Application](#deployed-application)
- [License](#license)

## Installation

To get a local copy of the project up and running, follow these steps:

1. **Clone the repository**  
   git clone https://github.com/Karimegtz/NoteTaker.git

2. **Navigate to the project directory**
  cd NoteTaker

3. **Install dependencies**
  npm install

 4. **Start the application**
  npm start
 The application will run on http://localhost:3000.

 ## Usage

Once the application is running, you can use it to write and save notes. The main functionalities include:

- Viewing existing notes listed on the left-hand side of the screen.
- Writing new notes by filling out the title and body fields on the right-hand side.
- Saving notes, which adds them to the list of existing notes.
- Clicking on a saved note to view its contents.
- Adding new notes using the "New Note" button.

## Routes

### HTML Routes

- `GET /notes`: Returns the `notes.html` file.
- `GET *`: Returns the `index.html` file for any other routes.

### API Routes

- `GET /api/notes`: Retrieves all saved notes as JSON.
- `POST /api/notes`: Saves a new note and returns the saved note as JSON.
- `DELETE /api/notes/:id`: Deletes a note by its unique ID.

## Deployed Application

The NoteTaker application is deployed on Render. You can access it [here](https://notetaker-6pvs.onrender.com).

## License

This project is licensed under the MIT License. See the LICENSE file for more details.





