
# Todo List Web App CI/CD

This repository contains the source code for a Todo List Web App with Continuous Integration and Continuous Deployment (CI/CD) set up using Jenkins and Docker. The application is built with Node.js.

## Prerequisites

Make sure you have the following dependencies installed on your machine before running the project:

- Node.js: `sudo apt install nodejs`
- npm: `sudo apt install npm`

## Getting Started

Follow the steps below to set up and run the project:

1. Clone the repository:

   ```bash
   git clone https://github.com/Ahmad10Raza/ToDo-List-WebApp-CICD.git
   ```

2. Change into the project directory:

   ```bash
   cd ToDo-List-WebApp-CICD
   ```
3. Install project dependencies:

   ```bash
   npm install
   ```
4. Run the application:

   ```bash
   node app.js
   ```

   The Todo List Web App should now be accessible at `http://localhost:3000` in your web browser.

## CI/CD Pipeline

The CI/CD pipeline for this project is configured using Jenkins and Docker. Jenkins is set up to automatically build and deploy the application whenever changes are pushed to the GitHub repository.

For more details on the CI/CD setup, refer to the Jenkinsfile in the root of this repository.

## Contributing

If you'd like to contribute to this project, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
