# Art Career Insights Platform  
A web-based dashboard application to help freelance artists, job seekers, and recruiters analyze trends in the creative job market.

## Project Description

The Art Career Insights Platform is designed to provide users with a comprehensive view of the art-related job landscape. By combining visual analytics and interactive filtering, the platform enables job seekers to understand hiring trends, compare salary benchmarks, and identify in-demand skills for various creative roles.

This project empowers freelance artists and aspiring professionals to make informed career decisions by offering a data-driven perspective of the job market.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Live Dashboard](#live-dashboard)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

1. Clone the repository:
```bash
https://github.com/harshithak01/Art-Career-Insights-platform.git
cd art-career-insights
```
## Set up the backend (Node.js + Express):
```
npm install
```
Set up the frontend (React.js):
```bash
cd client
npm install
npm start
```
## Usage

### To run the application locally:

```bash
npm run dev
```
This command will concurrently start both the frontend (React) and backend (Node.js + Express).
Once the application is running, users can:

Navigate through the embedded dashboards

Apply filters such as location, company, and employment type
##Project Structure

Analyze trends and insights based on the cleaned job dataset
art-career-insights/ ├── client/ # React frontend │ ├── public/ # Static assets (HTML, icons, etc.) │ ├── src/ # React components, pages, and styles │ │ ├── components/ # Reusable UI components │ │ ├── pages/ # Dashboard pages │ │ └── App.js # Main React app file │ └── package.json # Frontend dependencies │ ├── server/ # Node.js backend │ ├── routes/ # API endpoints │ ├── models/ # Data models (if using MongoDB) │ └── server.js # Main server setup │ ├── data/ # Cleaned CSV dataset for Tableau │ └── Deduplicated_Artist_Roles.csv │ ├── README.md # Project documentation ├── .gitignore # Git ignored files └── package.json # Backend 
dependencies

##Link to a Published Tableau Dashboard
https://public.tableau.com/app/profile/harshitha.kapalavayi/viz/Book1_17431348990250/Dashboard1?publish=yes


##Embed in GitHub Pages (Static Website)
https://harshithak01.github.io/Art-Career-Insights-platform/dashboard.html

![image](https://github.com/user-attachments/assets/bbfcb288-229a-4ab1-b7bd-c1dd13217ee5)

##Contribution
Harshitha- Team Lead

## LIcence
MIT License

