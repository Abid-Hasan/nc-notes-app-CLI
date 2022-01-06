# Notes-App (CLI)

## A simple command line app built with Node.js to Save, Read, Remove notes.

### How to use:

0. Install Node.js on your machine if you haven't already.
1. Get Notes-App to machine and navigate there.
2. Run "npm i" to install node_modules
3. After that, run any command or run "node app.js -- help" to get the list of all commands and options

### Commands:

- node app.js add --title <TITLE> --body <BODY> [Add a new note]
- node app.js remove --title <TITLE> [Remove a note]
- node app.js read --title <TITLE> [Read a note]
- node app.js list [Get the list of all notes]

### Options:

- --help [Show help]
- --version [Show version number]
- --title <TITLE> [Required for add, remove and read]
- --body <BODY> [Required for add]

### Example:

- node app.js add --title "My note's title" --body "My note's body"
