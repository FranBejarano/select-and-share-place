# Select and Share a Place

Select and Share a Place is a simple web application that allows users to search for a location by entering an address. The application uses the Google Maps Geocoding API to convert the entered address into geographical coordinates (latitude and longitude) and displays the location on a map.

## Table of Contents

- [Select and Share a Place](#select-and-share-a-place)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Technologies Used](#technologies-used)
  - [Contributing](#contributing)
  - [License](#license)

## Installation

To use Select and Share a Place, follow these steps:

1. Clone this repository to your local machine using Git:

   ```
   git clone https://github.com/your-username/select-and-share-a-place.git
   ```

2. Navigate to the project directory:

   ```
   cd select-and-share-a-place
   ```

3. Install the project dependencies using npm or yarn:

   ```
   npm install
   ```

   or

   ```
   yarn install
   ```

4. Get a Google API Key:

   - Go to the [Google Cloud Console](https://console.cloud.google.com/).
   - Create a new project or select an existing one.
   - Enable the "Geocoding API" for your project.
   - Generate an API key.
   - Replace `'YOUR_GOOGLE_API_KEY'` in the code with your actual API key.

5. Start the development server:

   ```
   npm start
   ```

   This will start the application on `http://localhost:3000` by default. You can access it in your web browser.

## Usage

1. Enter an address in the input field provided on the web page.

2. Click the "Search" button or press Enter.

3. The application will make a request to the Google Maps Geocoding API to retrieve the coordinates of the entered address.

4. If the address is valid, it will display a map centered on the location and mark it with a pin. If the address is not found, an error message will be displayed.

## Technologies Used

This project uses the following technologies:

- JavaScript
- Axios: Axios is used to make HTTP requests to the Google Maps Geocoding API.
- Google Maps JavaScript API: This API is used to display the map and place a marker on the location.
- HTML and CSS: For the basic structure and styling of the web page.

## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bug fix:

   ```
   git checkout -b feature-name
   ```

3. Make your changes and commit them with a clear and concise message:

   ```
   git commit -m "Add feature or fix bug"
   ```

4. Push your changes to your fork:

   ```
   git push origin feature-name
   ```

5. Create a pull request to the `main` branch of the original repository.

6. Your pull request will be reviewed, and once approved, it will be merged.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
