
# Promptly

![Project Logo](https://linktoyourlogo.com/logo.png)

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

## Contributing

Feel free to fork this repository, make feature requests, or submit issues!

## License

This project is licensed under the MIT License.
