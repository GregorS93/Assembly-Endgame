# Assembly Endgame

A modern, responsive, and feature-rich booking project built with React. This project is meant to showcase the popular React Router library and all of it's most popular use cases to provide an efficient and latest user experience.

## Table of Contents

1. [Features](#features)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Available Scripts](#available-scripts)
5. [Dependencies](#dependencies)
6. [Project Structure](#project-structure)

## Features

- Responsive design, compatible with tablet and mobile devices
- Use of nested and deeply nested routes for multipage layering design
- Mock user login with provided User email and password
- Showcase of filtering with different filter types
- Firebase database integration for data fetching
- Mirage JS integration for setting up a server and user for login validation
- Clear and modular code structure

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

### Mock login credentials

- username: b@b.com
- password: p123

## Available Scripts

Available Scripts
In the project directory, you can run:

- npm run dev : Starts the development server
- npm run build : Builds the application for production
- npx prettier --check : Checks prettier formatting
- npx prettier --write : Runs prettier and formats it

## Dependencies

- "clsx": "^2.1.1",
- "firebase": "^11.3.1",
- "miragejs": "^0.1.48",
- "react": "18.2.0",
- "react-dom": "18.2.0",
- "react-icons": "^5.5.0",
- "react-router-dom": "6.4.3",
- "vite": "latest"

## Project Structure

This project follows a modular structure for better organization and maintainability. Here's an overview of the folder structure:

- **apis**: Global functions used for any kind of interactions with APIs.
- **assets**: Contains all images used thrughout the project.
  - **each view (page name)**: Folder for storing images specific to a view.
- **components**: Stateless components used in multiple places.
- **consts**: Fixed variables.
- **css**: View (page) specific css (style) files all exported into index.html.
- **localStorage**: handles for adding, accessing and removing localStorage data.
- **node_modules**: stores all dependencies and libraries used throughout the project.
- **pages**: Main folder for all the views (pages) in the application.
  - **page names**: Individual folders for each view.
  - **host pages**: Separete folder with all views (pages) relating to the user (host)
- **public**: Stores all static assets that are not processed by the build system

Below is an example folder structure for the "pages" view:

```
pages/
└─ Host/
└─ HostDashboard/
├── components/

```
