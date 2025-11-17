React + Vite App
This folder contains a minimal setup for a React application built using Vite—optimized for fast dev experience and CI/CD automation.

Structure
/public: Static assets

/src: Source code (React components)

Dockerfile: Production build steps for containerization

package.json, package-lock.json: Project metadata and dependencies

vite.config.js: Vite build configuration

Getting Started
Install dependencies
Make sure you have Node.js & npm installed. Then:

text
npm install
Run the development server
text
npm run dev
Build a production bundle
text
npm run build
Preview the production build locally
text
npm run preview
Main Dependencies
React

Vite

ESLint (with custom config for linting)

Docker
Build the Docker image for the app:

text
docker build -t aws-devops-app .
Run the container locally:

text
docker run -p 80:80 aws-devops-app
Notes:

For TypeScript setup, see Vite + React TS Template.

Project is CI/CD-ready—see the root infrastructure documentation for automated build & deployment flow.

