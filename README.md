## FreeCodeCamp | Coding Interview Prep — Take-Home Projects

**Five interactive web applications built with HTML, CSS, and JavaScript.**

[**View Live Project Portfolio**](https://stellar-pixie-207316.netlify.app/)

## Overview

This repository contains five web application projects developed as part of FreeCodeCamp's Coding Interview Prep curriculum.

The projects explore fundamental concepts in front-end development, including DOM manipulation, event handling, asynchronous programming, API integration, browser storage, and algorithmic problem-solving.

Each project is implemented as a standalone application using vanilla JavaScript, with no front-end frameworks or build dependencies.

The applications are hosted through Netlify, with source code maintained on GitHub.

## Projects

| Project | Description | Live Demo |
|---|---|---|
| **Light-Bright** | Interactive drawing board with customizable colors, mouse interactions, and clearing tools | [Launch](https://stellar-pixie-207316.netlify.app/01-light-bright/) |
| **Wikipedia Viewer** | Search application using the Wikipedia API to retrieve and display encyclopedia articles | [Launch](https://stellar-pixie-207316.netlify.app/02-wikipedia-viewer/) |
| **Recipe Box** | Recipe management application supporting creation, editing, deletion, and persistent browser storage | [Launch](https://stellar-pixie-207316.netlify.app/03-recipe-box/) |
| **Local Weather** | Weather dashboard with location search, browser geolocation, and temperature conversion | [Launch](https://stellar-pixie-207316.netlify.app/04-local-weather/) |
| **Tic Tac Toe** | Interactive game featuring computer-opponent logic, win detection, player selection, and score tracking | [Launch](https://stellar-pixie-207316.netlify.app/05-tic-tac-toe/) |

The corresponding source code is available in the numbered project directories within this repository.

## Technology Stack

**Core technologies**
- HTML5 — Application structure and semantic markup
- CSS3 — Responsive layouts, styling, and interactive interfaces
- JavaScript (ES6+) — Application logic and event-driven functionality

**Browser APIs and external services**
- DOM API for dynamically updating interfaces
- Fetch API for asynchronous HTTP requests
- Local Storage API for persistent browser data
- Geolocation API for location-based weather
- MediaWiki API for encyclopedia search
- Open-Meteo API for weather and location data

**Development and deployment**
- GitHub — Source control and repository management
- GitHub Codespaces — Cloud-based development environment
- Netlify — Continuous deployment and public hosting

## Development Process

### 1. Requirements and Planning

Development began by reviewing the FreeCodeCamp project descriptions and identifying the primary behaviors needed for each application.

The goal was to create lightweight, functional prototypes that demonstrate core JavaScript concepts without introducing unnecessary dependencies.

Individual applications were organized around different technical concepts:

- User interface interaction and DOM manipulation
- Asynchronous data retrieval
- CRUD operations and local persistence
- External API integration
- Game state management and conditional logic

### 2. Implementation and Iteration

The applications were developed using an AI-assisted workflow.

ChatGPT was used to help produce the initial application implementations, including substantial portions of HTML, CSS, JavaScript logic, and interface design.

The generated implementations were organized into separate application directories within a GitHub repository.

The project structure allows each application to operate independently while sharing a common stylesheet and portfolio homepage.

### 3. Development Environment and Deployment

GitHub Codespaces was used as the development environment, allowing the projects to be managed without a separate local development installation.

The repository was connected to Netlify for deployment.

The deployment structure provides:

- A public homepage linking to all five projects
- Individual URLs for each application
- Direct access to the underlying source code through GitHub
- Deployment updates through the connected repository

### 4. Testing and Validation

The project files have undergone JavaScript syntax checking. The deployed pages have also been reviewed for basic accessibility through their public URLs.

Full interactive testing and comparison against every FreeCodeCamp project requirement remain in progress.

The intended functional checks include:

- [ ] Light-Bright: Test painting, erasing, and clearing the board
- [ ] Wikipedia Viewer: Confirm that searches retrieve and display results
- [ ] Recipe Box: Confirm that recipes can be created, edited, deleted, and restored after refreshing
- [ ] Local Weather: Verify city searches, location permissions, and temperature conversions
- [ ] Tic Tac Toe: Validate player turns, computer moves, win detection, and game resets

## Repository Structure

- `index.html` — Main project portfolio homepage
- `styles.css` — Shared application styling
- `01-light-bright/` — Interactive drawing application
- `02-wikipedia-viewer/` — Wikipedia search application
- `03-recipe-box/` — Recipe management application
- `04-local-weather/` — Weather dashboard
- `05-tic-tac-toe/` — Tic Tac Toe game
- `README.md` — Project documentation

Each numbered project folder contains its own `index.html`, including the application's JavaScript.

## Running the Projects Locally

**Requirements:** A modern web browser and Python 3 for the optional local development server.

1. Clone or download this repository.
2. Open the repository directory in VS Code or GitHub Codespaces.
3. Start a local server using `python3 -m http.server 8000`.
4. Open `http://localhost:8000/` in your browser.
5. Select an application from the homepage.

No npm installation or build process is required.

An internet connection is necessary for external API functionality in the Wikipedia Viewer and Local Weather applications.

## Technical Considerations

Several implementation decisions keep the projects lightweight and easy to explore.

**Framework-free development:** Plain JavaScript provides direct exposure to browser APIs and DOM manipulation without relying on a framework.

**Local persistence:** The Recipe Box uses browser localStorage rather than a backend database. Recipes are stored in the visitor's own browser.

**External data:** Weather and Wikipedia features depend on publicly accessible services. Availability and response behavior may vary.

**Simple deployment:** All five projects are static applications, making them suitable for hosting through a single Netlify deployment.

## AI Assistance and Development Transparency

**This repository contains substantial AI-assisted code.**

ChatGPT was used to generate initial implementations for the five applications, including application structure, interface design, JavaScript functionality, and portions of the documentation.

My work on this collection has included organizing the project files, establishing the GitHub Codespaces environment, configuring the GitHub-to-Netlify deployment workflow, and coordinating the preparation and review of the applications.

The projects are presented transparently as AI-assisted learning prototypes rather than entirely independently authored implementations.

My broader FreeCodeCamp coursework has involved working through JavaScript data structures, studying algorithmic concepts, understanding method behavior, and practicing code execution and debugging.

This project collection reflects an effort to combine that foundational learning with practical experience using modern development tools and AI-assisted workflows.

## Current Status and Next Steps

**Status: Deployed prototypes — validation and refinement ongoing.**

Planned improvements include:

- Completing functional verification against the original challenge requirements
- Improving error handling and edge-case behavior
- Refining responsive design and accessibility
- Expanding automated and manual testing
- Refactoring selected features to reinforce independent JavaScript implementation skills

## Acknowledgments

- [FreeCodeCamp](https://www.freecodecamp.org/) — Coding Interview Prep curriculum and project challenges
- [GitHub](https://github.com/) — Source control and cloud development
- [Netlify](https://www.netlify.com/) — Application hosting
- [OpenAI ChatGPT](https://chatgpt.com/) — AI-assisted implementation and documentation

---

**[Explore the Live Applications](https://stellar-pixie-207316.netlify.app/)**

*Educational portfolio project | JavaScript • HTML • CSS • APIs • AI-assisted development*