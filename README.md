# InteractiveMap Project for Informatics 151

This full-stack Interactive Map application is a part of the coursework for Informatics 151. The application web scrapes state data from a simple Wikipedia list, parses it, and populates a SQL database using Django models. The front end initiates a GET request to our request handler upon startup to receive all state data as a JSON response. The onClick() functionality is currently unimplemented.

## Features

- **Web Scraping**: Automated data extraction from the Wikipedia page.
- **Data Parsing**: Processing and structuring the scraped data.
- **Database Integration**: Using Django models to store state data.
- **Frontend Interaction**: Serving state data as a JSON response upon a GET request.

## Usage

### Prerequisites
- Ensure you have Django installed and configured.
- Node.js and npm must be installed on your system.

### Running the Application

To get the application running on your local machine, follow these steps:

1. Start the Django server within the Django folder:

2. Install the necessary Python packages:

3. In the project directory, start the React application:

4. The application will open in your default web browser at `http://localhost:3000`.

### Installation

Ensure that you have the following npm packages installed:
- ReactJS for the interactive map: [react-usa-map](https://www.npmjs.com/package/react-usa-map)

## Development Scripts

- `npm start`: Runs the app in development mode at `http://localhost:3000`.
- `npm test`: Runs the test suite in interactive watch mode.
- `npm run build`: Builds the app for production to the `build` folder.
- `npm run eject`: Removes the single build dependency from your project.

## Learn More

For more information on React and Django, you can refer to the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started) and the [Django documentation](https://docs.djangoproject.com/en/3.1/).

## Beta Version Screenshots

![Interactive Map Beta Screenshot 1](https://github.com/JaylenLuc/InteractiveMap/assets/91278747/9efc6e91-d50b-4ac0-8328-92f3dfbba576)

![Interactive Map Beta Screenshot 2](https://github.com/JaylenLuc/InteractiveMap/assets/91278747/510d72d4-c3d3-4943-9304-51df66002c45)

![Interactive Map Beta Screenshot 3](https://github.com/JaylenLuc/InteractiveMap/assets/91278747/e5d55ba8-0333-4d45-928d-e8dcea3726b9)

*Note: Replace the image URLs with the correct paths to the images in your repository.*

## Contributing

If you would like to contribute to the project or suggest improvements, please follow the standard GitHub pull request process.

## License

This project is provided under the terms of the MIT License.
