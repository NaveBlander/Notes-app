# Notes-app

A simple command-line notes application built with Node.js. This app allows users to manage their notes by adding, removing, listing, and reading them using command-line commands.

## Features

- **Add a new note:** Create a note with a title and body.
- **Remove a note:** Delete an existing note by its title.
- **List notes:** Display all your notes' titles.
- **Read a note:** View the content of a specific note.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/notes-app.git

2. Navigate into the project directory:
    ```bash
    cd notes-app

4. Install the dependencies:
    ```bash
    npm install

 ## Usages
 - **Add a note:** To add a new note, use the following command:
      node app.js add --title="Your Note Title" --body="Your Note Body"
- **Remove a Note:** To remove a note, use:
      node app.js remove --title="Your Note Title"
- **List Notes:** To list all your notes, run:
      node app.js list
- **Read a Note:** To read a specific note, use:
      node app.js read --title="Your Note Title"

## Data storage
Notes are stored in a JSON file named notes.json. Each note has a title and body.

## Dependencies
This project uses the following npm packages:
- **chalk** - For styling terminal strings.
- **yargs** - For parsing command-line arguments.

 





