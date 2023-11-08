# Quick-Notes

## Features:
- CRUD Application.
- Google Auth is used for Authentication.
- Create a new note with a title and content.
- View a list of all saved notes.
- View the details of a single note.
- Update the content of an existing note.
- Delete a note.

## API Endpoints

The following API endpoints are available:

- GET /notes: Retrieve all notes for the authenticated user.
- GET /notes/:id: Retrieve a specific note by ID.
- POST /notes: Create a new note.
- PUT /notes/:id: Update an existing note by ID.
- DELETE /notes/:id: Delete a note by ID.

## Requirements:
- Database (MongoDB)
- Google Console Account to create the API Auth Key's.

## Create .env file
Create a .env file to store your credentials. Example below:

```
MONGODB_URI = mongodb+srv://<username>:<password>@mongodburlhere
GOOGLE_CLIENT_ID= YOUR_GOOGLE_ID_HERE
GOOGLE_CLIENT_SECRET= YOUR_GOOGLE_CLIENT_SECRET_HERE
GOOGLE_CALLBACK_URL=http://localhost:5000/google/callback
```

## Installation
To install and run this project - install dependencies using npm and then start your server:

```
$ npm install
$ npm start
```
