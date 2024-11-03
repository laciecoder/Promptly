
# Promptly

![Project Logo](https://img.logoipsum.com/277.svg)

## Overview

This project is a web application built with React and several modern libraries to enhance user interaction and readability. Key features include Token-based authentication, interactive animations, and markdown rendering.

## Features

- **Token-Based Authentication**: Implemented using [library/tool used, e.g., JWT, sessions].
- **Dynamic Content Rendering**: Utilizes `react-markdown` to display markdown content directly in the UI.
- **Smooth Animations**: Enhanced user experience with zoom animations and [React Type Animation](https://www.npmjs.com/package/react-type-animation) for engaging text transitions.
  
## Demo

Check out the live demo [here](https://promptly-frontend-pi.vercel.app/).

## Demo

Check out the Frontend Code [here](https://github.com/laciecoder/promptly-frontend).
Check out the Backend Code [here](https://github.com/laciecoder/promptly-backend).

## Technologies Used

- **Frontend**: React, Material UI, React-Router-Dom for routing
- **Markdown Rendering**: `react-markdown` for seamless markdown support
- **Animations**: `react-type-animation` for text effects
- **Backend**: Express, MongoDB
- **Authentication**: Token-based login system

## Installation

1. **Clone the repo**:
   ```bash
   git clone https://github.com/laciecoder/promptly-frontend.git
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**:
   Set up your `.env` file with the necessary environment variables:
   ```env
    OPEN_AI_SECRET= 
    OPEN_AI_ORG_ID=
    MONGODB_URI=
    JWT_SECRET=
    JWT_EXPIRES_IN=3d
    COOKIE_SECRET=
    HASH_ROUNDS=10
    DOMAIN=localhost
   ```

4. **Run the application**:
   ```bash
   npm start
   ```

## Usage

- **Login**: Start a Token-based login.
- **View Markdown**: Write and view markdown in real-time.
- **Animations**: Notice the smooth zoom-in/zoom-out effects and typing animations for text content.

## Update
- Due to some issues with vercel, token retrieval is not working, so for time being, I have attached some screen shots of project

## Screenshots
 Home Page
 ![](https://utfs.io/f/QyLqvzYvXKIN2ByorguXtmcdKpA9Ruxolk6gaTMjSeLZf1NQ)

 Login Page
 ![](https://utfs.io/f/QyLqvzYvXKIN0taUh3Iag2p4lO5JLi936RfcSzUvKWGAynX0)

 Chat Page
 ![](https://utfs.io/f/QyLqvzYvXKINyddHtzQYztFu6HwnJ1QjqCoMIT7ipcOdegVA)

 ![](https://utfs.io/f/QyLqvzYvXKINhZzVrEe2XOHUzc6Dgi3hN8QnFesr9qV7p5AM)

 Clearing Chat
 ![](https://utfs.io/f/QyLqvzYvXKIN9P3aKMmEj4KwoMzvQVXmCJ3ZyYRPgkTAx5qs)

 ![](https://utfs.io/f/QyLqvzYvXKINupPRMErHbA4swKduYFvxN3tQ9lnSWTOhiqz2)

 Sample Prompt
 ![](https://utfs.io/f/QyLqvzYvXKINqxhEsZJwAyp5PCZRvfoIbUX08unOQ2kg39ea)

 ![](https://utfs.io/f/QyLqvzYvXKINs2gSzTnudBV0KGzHExmkvfUJc7Qa4oLXyNRW)

## Contributing

Feel free to fork this repository, make feature requests, or submit issues!

## License

This project is licensed under the MIT License.
