NodeJS app for taking notes via command-line (CLI)

# Prerequisities

To run this app, you must have **node** and **npm** installed on your machine.

## Installing dependencies

Install required dependencies by running the following command

```
npm install
```

# To add a note

Open your terminal and go to the corresponding directory

```
node app.js add --title="some title" --body="some body"
```

Upon success, a JSON file will be created, this file will storing all notes.

# To remove a note

```
node app.js remove --title="some title"
```
