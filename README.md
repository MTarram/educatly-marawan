# EducatlyTask

This project is a responsive Angular application that fetches and displays blog posts from the [DEV.to API](https://dev.to/api/articles). It follows a modern design with pagination, error handling, and loading indicators.

## 🚀 Features
- Fetch and display blog posts from DEV.to API
- Infinite scrolling pagination (Load More button)
- Responsive design for desktop and mobile
- Loading indicator while fetching data
- Error handling with retry option
- Placeholder image for missing blog cover

## 📌 Setup Instructions

###  Install Dependencies
```bash
npm install
```
This will install all required packages for the Angular project.

### Run the Development Server
```bash
ng serve
```
After running this command, open your browser and navigate to:
```
http://localhost:4200/
```
The application will automatically reload when you modify any source files.

## 🏗️ Building the Project
```bash
ng build
```
This will generate the production-ready build in the `dist/` directory.

## 🧪 Running Tests
### Unit Tests
```bash
ng test
```
Runs the unit tests using Karma.

### End-to-End Tests
```bash
ng e2e
```
Executes end-to-end tests (make sure you have a test framework configured).

## 🌍 Deployment
For deploying to services like Netlify or Vercel:
```bash
ng build --prod
```
Then upload the `dist/` folder to your hosting provider.
