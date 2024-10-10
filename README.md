# Ahmad Alfan Juniyanto Portfolio

This repository contains the source code for Ahmad Alfan Juniyanto's personal portfolio website. The website showcases personal projects, experience, and contact information. It is built using HTML, SCSS (compiled to CSS), and various tools for managing and optimizing the front-end assets.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Available Scripts](#available-scripts)
- [Technologies Used](#technologies-used)
- [License](#license)

## Demo

You can view the live portfolio at: [Ahmad Alfan Juniyanto Portfolio](https://alfanjuni.github.io/)

## Features

- Navigation Bar: Links to social media profiles like LinkedIn, Twitter, Instagram, GitHub, and Facebook.
- Responsive Design: Mobile-first responsive design, making the site accessible across different devices.
- Dynamic Sections:
  - "About Me" section with an introduction and background information.
  - "Projects" section showcasing various Web, Desktop, and Mobile applications.
  - "Team Stories" section where testimonials and stories from colleagues are displayed.
  - "Contact Me" section with a form to get in touch via email.
- SASS Styling: Styling is handled using SCSS, which is then compiled to CSS.

## Project Structure

```
├── css/
│   ├── style.css         # Compiled CSS
│   └── style.concat.css  # Concatenated and processed CSS
├── img/                  # Images used on the website
├── sass/
│   └── main.scss         # Main SCSS file
├── index.html            # Main HTML file
└── package.json          # Node.js package configuration
```

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

* Node.js (v16.x or higher)
* npm (comes with Node.js)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/alfanjuni/alfanjuni.github.io.git
   cd alfanjuni.github.io
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

### Running the Development Server

To start the development server and watch for changes in the SCSS files, run:

```bash
npm run start
```

This will:
* Start a live server using `live-server`.
* Watch for changes in the `sass/main.scss` file and automatically compile it to `css/style.css`.

### Building the CSS

To build and optimize the CSS for production, run:

```bash
npm run build:css
```

This will:
1. Compile the SCSS to CSS.
2. Concatenate the CSS files.
3. Add vendor prefixes using `postcss` and `autoprefixer`.
4. Compress the final CSS file.

## Available Scripts

Here is a list of npm scripts defined in the `package.json` file:

* `npm run start`: Starts the live server and watches for SCSS changes.
* `npm run watch:sass`: Watches the `sass/main.scss` file for changes and compiles to `css/style.css`.
* `npm run build:css`: Compiles, concatenates, prefixes, and compresses the CSS for production.
* `npm run devserver`: Starts the live server without watching SCSS files.

## Technologies Used

* **HTML5**: Structure of the web pages.
* **SCSS (Sass)**: CSS pre-processor for writing more maintainable and powerful styles.
* **Node.js**: Used to run various development tasks.
* **npm-run-all**: Utility to run multiple npm scripts in parallel.
* **PostCSS**: Post-processing tool for CSS, using Autoprefixer to add vendor prefixes.
* **Live Server**: A simple development HTTP server with live reload capability.

## License

This project is licensed under the ISC License.