# Pico Library

## Introduction

Pico Library is a web application designed to help users discover and explore various subjects and books. It consists of both a Flask-based API for the backend and a React-based frontend for the user interface. Users can search for subjects, view associated books, and navigate through different pages of subjects.

- **Deployed Site:** [Pico Library](https://pico-lib.vercel.app/)
- **Final Project Blog Article:** [Pico Library Blog](https://medium.com/@rahimdaud246/crafting-a-book-library-my-journey-dd3e02a82713)
- **Author(s) LinkedIn:** [Author's LinkedIn Profile](www.linkedin.com/in/rahim-daud-piccolo)
  
![Pico Library Screenshot](./screenshots/pico-library-screenshot.png)

## Installation

To run Pico Library locally, follow these steps:

1. Clone the repository: 
   ```
   git clone https://github.com/piccolojnr/pico-lib.git
   ```
2. Navigate to the project directory:
   ```
   cd pico-lib
   ```
3. Install dependencies for both frontend and backend:
   ```
   cd pico-lib-app
   npm install
   cd ../pico-lib-api
   pip install -r requirements.txt
   ```
4. Start the frontend and backend servers:
   - **Frontend (React)**:
     ```
     cd ../pico-lib-app
     npm start
     ```
   - **Backend (Flask)**:
     ```
     cd ../pico-lib-api
     flask run
     ```

## Usage

Once the frontend and backend servers are running, you can access the application in your web browser at `http://localhost:3000`. From there, you can explore subjects, search for specific subjects, and view associated books.

## CHeckout the API
- [pico-lib-api](./pico-lib-api/README.md)

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request. 

## Related Projects

- [Pico Library API](https://github.com/piccolojnr/pico-lib-api): Flask-based API for Pico Library.

## Licensing

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
