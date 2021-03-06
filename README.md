NodeJS app for taking notes via command-line (CLI)

# Prerequisities

To run this app, you must have both **node** and **npm** installed on your machine.

## Installing dependencies

Install required dependencies by running the following command

```
npm install
```

## To learn about commands

```
node app.js --help
```

The above command will list all available commands.

## To add a note

Open your terminal and go to the corresponding directory

```
node app.js add --title="some title" --body="some body"
```

Upon success, a JSON file will be created and it will be storing all notes in an array.

## To remove a note

```
node app.js remove --title="some title"
```

## To list your notes

```
node app.js list
```

## To read note

```
node app.js read --title="some title"
```

> Credits goes to Andrew Mead, my instructor.
