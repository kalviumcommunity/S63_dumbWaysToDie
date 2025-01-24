# Dumb Ways to Die

A silly project where users can log in and create a list of dumb ways to die. Built with the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User authentication (login/register)
- Create, read, update, and delete (CRUD) operations for lists
- Responsive design
- Social media sharing
- Commenting on lists
- Upvoting/downvoting lists
- User profiles with avatars
- Notifications for list updates
- Real-time updates with Socket.io
- Enhanced security with Passport.js
- Improved state management with Redux
- Containerization with Docker
- GraphQL for more efficient data fetching

## Technologies Used

### Primary Stack
- MongoDB
- Express
- React
- Node.js

### Additional Technologies and Libraries
- Redux
- Socket.io
- Passport.js
- Mongoose
- Tailwind CSS
- Jest
- Docker
- GraphQL

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/dumbWaysToDie.git
    cd dumbWaysToDie
    ```

2. Install server dependencies:
    ```bash
    cd server
    npm install
    ```

3. Install client dependencies:
    ```bash
    cd ../client
    npm install
    ```

### Running the Application

1. Start the MongoDB server:
    ```bash
    mongod
    ```

2. Start the Express server:
    ```bash
    cd server
    npm start
    ```

3. Start the React client:
    ```bash
    cd ../client
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000`

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## License

Distributed under the MIT License. See `LICENSE` for more information.
