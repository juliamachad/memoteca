# Memoteca

Memoteca is a project developed with Angular that uses a mock backend to provide data through a simple REST API. The backend is created and managed with `json-server`, which generates a REST API from a JSON file. This project is ideal for front-end development and testing, providing a simulated environment for data manipulation.

## Features

- **List Thoughts**: View all stored thoughts.
- **Create Thought**: Add new thoughts to the collection.
- **Edit Thought**: Update existing thoughts.
- **Delete Thought**: Remove thoughts from the collection.

## Project Structure

- **Frontend**: Developed with Angular.
  - Uses `HttpClient` for communication with the REST API.
  - Includes a `PensamentoService` for performing CRUD (Create, Read, Update, Delete) operations on thoughts.

- **Backend**: Generated with `json-server`.
  - **Data File**: `db.json`
    - Stores thoughts.
  - **Server**: Configured to run on port 3000.
  - **Start Command**: `npm start`, which starts `json-server` and serves the API.

## Technologies Used

- **Angular**: Framework for building the user interface.
- **json-server**: Creates a REST API from a JSON file.
- **HTTP Client**: Used for making requests to the REST API in Angular.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/usuario/memoteca.git


2. **Navigate to the Project Directory**
   ```bash
   cd memoteca


3. **Install Frontend Dependencies**
   ```bash
   cd frontend
    npm install


4. **Start the Backend Server**
   ```bash
   cd ../backend
    npm install
    npm start


5. **Start the Frontend Server in another terminal**
   ```bash
    ng serve


Access the Application on http://localhost:4200/ in your browser.

![memoteca](https://github.com/user-attachments/assets/cb6c1870-98cc-4433-9d00-67853eb060d9)
