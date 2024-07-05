# Real-Time Tracker

## Description
Real-Time Tracker is a web application that allows users to share their location in real-time. This application uses Express for the server, Socket.IO for real-time communication, and EJS for rendering views.

## Features
- Real-time location sharing
- User connection and disconnection notifications
- Simple and clean interface

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Dushyantgoswami/real-time-location-tracker.git
    ```

2. Navigate to the project directory:
    ```sh
    cd real-time-location-tracker
    ```

3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```

2. Open your browser and go to:
    ```
    http://localhost:3000
    ```

## Project Structure

- `app.js`: Main application file where the server and Socket.IO are set up.
- `package.json`: Contains the project metadata and dependencies.
- `package-lock.json`: Contains the exact versions of the installed dependencies.
- `public/`: Directory for static assets (e.g., CSS, JS, images).
- `views/`: Directory for EJS templates.

## Dependencies

- [Express](https://expressjs.com/) - Web framework for Node.js
- [Socket.IO](https://socket.io/) - Library for real-time web applications
- [EJS](https://ejs.co/) - Embedded JavaScript templating

## Contributing
1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
6. Create a new Pull Request.

## License
This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.
