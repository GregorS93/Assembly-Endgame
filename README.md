# Assembly Endgame

An advanced, dynamic, and full-featured game crafted with React. The idea behind this capstone project is to showcase all of the basic React features and it's capabilities. The game is a rebranded version of the popular Hangman game, known through out the world.

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Available Scripts](#available-scripts)
5. [Dependencies](#dependencies)
6. [Project Structure](#project-structure)

## Features

- Conditional Rendering: UI updates dynamically to show correct/incorrect guesses as well as the game lose/win state.
- Dynamic Word Selection: the game starts with a randomly selected word with each new game
- State Management with useState: different variables are being tracked using React's useState hook
- Basic Game Logic Implementation: incorrect guesses tracking, letter validation and more
- Event handling for user input: onClick events allow users to guess letters

## Getting Started

### Installation

Install the dependencies and run the project

- npm install
- npm start

Head over to https://vitejs.dev/ to learn more about configuring vite

## Usage

To start the development server, run:
**npm run dev**
The application will be accessible at **http://localhost:5173.**

## Available Scripts

Available Scripts in the project directory, you can run:

- npm run dev : Starts the development server
- npm run build : Builds the application for production
- npx prettier --check : Checks prettier formatting
- npx prettier --write : Runs prettier and formats it

## Dependencies

- "clsx": "^2.1.1",
- "react": "18.3.1",
- "react-confetti": "^6.1.0",
- "react-dom": "18.3.1",
- "vite": "latest"

## Project Structure

This project follows a modular structure for better organization and maintainability. Here's an overview of the folder structure:

- **css**: css (style) file exported into index.html.
- **node_modules**: stores all dependencies and libraries used throughout the project.
- **pages**: Main folder for the view (page) of the application.
- **public**: Stores all static assets that are not processed by the build system.
- **utils**: Stores different .js files used throught out the project.

Below is an example folder structure for the "pages" view:

```
pages/
└─ pages/
├── App.jsx/

```
