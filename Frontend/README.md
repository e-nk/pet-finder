# Pet-finder
This is a simple web application for pet adoption. Users can view a list of available pets and their details, add new pets to the list, and edit or delete existing pets.

## Live Demo
Link to project : 

[![Click Me](https://img.shields.io/badge/Click%20Me-yellow?style=for-the-badge)](https://deluxe-genie-ecbb1a.netlify.app/)


## Technologies Used
This project was built with the following technologies:

    React: a JavaScript library for building user interfaces
    Bootstrap
    Netlify: this project's frontend is deployed on netlify

# Installation
To install and run the application locally, follow these steps:

1. Clone the repository:

        git clone https://github.com/your-username/pet-adoption-app.git
2. Navigate to the project directory:

        cd pet-adoption-app
3. Install the dependencies:

        npm install
4. Start the server:

         npm start

5. Open the application in your browser at http://localhost:3000

# Usage
The application allows users to:

- View a list of available pets and their details
- Add a new pet to the list with a name, description, breed, species, contact information, and photo
- Edit an existing pet's details
- Delete an existing pet from the list

# API Routes
The application uses the following API routes:

- GET /pets: Get a list of all pets
- POST /pets/create: Create a new pet
- PUT /pets/update/:id: Update an existing pet
- DELETE /pets/destroy/:id: Delete an existing pet

# License
This project is licensed under the MIT License.