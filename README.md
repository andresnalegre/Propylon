# Propylon

## Description
Propylon is a web application that allows users to store and later retrieve files at a specified URL. The project is composed of a frontend JavaScript application and a backend API.

## Project Structure

The project is divided into two main parts:

- `backend`: This folder contains the API which provides endpoints for the frontend to upload and retrieve files. Written in [the Python framework you used, for example, Django].
- `frontend`: This folder contains the frontend application written in [the JavaScript framework you used, for example, React].

## Installation

To install and run this project, you need to follow the steps below:

### Backend

1. Open a terminal and navigate to the `backend` folder:

   ```bash
   cd backend
   cd file_storage_project

2. Start the server with the command:

   ```bash
   python3 manage.py runserver


### Frontend

1. Open a second terminal and navigate to the frontend folder:

   ```bash
   cd frontend
   cd src

2. Start the frontend application with the command:

   ```bash
   npm start

### Usage

Users can submit files to the application, specifying the desired URL. They can also submit a new version of the same file at the same URL. Users can retrieve the latest version of the file by accessing the document URL. The original version of the file can be accessed by appending "?revision=0" to the URL.

To upload files, go to http://127.0.0.1:8000/files/upload/.

### Authentication

Users must be authenticated to interact with the application. A user cannot access files submitted by another user.

For testing purposes, there already exists an admin user named "andresn".

### Testes

We demonstrate best-practice use of unit tests.

### Licença

This project is licenced under the MIT Licence. Please see the LICENCE.md file for more details.











