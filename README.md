# Art Career Insights Platform

A web-based dashboard application to help freelance artists, job seekers, and recruiters analyze trends in the creative job market.

---

## 📝 Project Description

The Art Career Insights Platform is designed to provide users with a comprehensive view of the art-related job landscape. By combining visual analytics and interactive filtering, the platform enables job seekers to understand hiring trends, compare salary benchmarks, and identify in-demand skills for various creative roles.

This project empowers freelance artists and aspiring professionals to make informed career decisions by offering a data-driven perspective of the job market.

---

## 📁 Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Live Dashboard](#live-dashboard)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/harshithak01/Art-Career-Insights-platform.git
cd art-career-insights
```
###2. Install dependencies
Install both frontend and backend dependencies.

For Frontend (React):
Navigate to the client folder and run:

```bash
cd client
npm install
```

For Backend (Node.js):
Navigate to the server folder and run:

```bash
cd server
npm install
```

###4. Run the Application
Start the Backend:
From the server folder, run:

```bash
node server.js
```

Start the Frontend:
From the client folder, run:

```bash
npm start
```

This command will concurrently start both the frontend (React) and backend (Node.js + Express).
Once the application is running, users can:

Navigate through the embedded dashboards

Apply filters such as location, company, and employment type
##Project Structure

Analyze trends and insights based on the cleaned job dataset

### Features

User Authentication (Sign up/Login)

Power BI Embedded Dashboards

Job trend analysis over time

Company & salary comparisons

Location and employment-type based insights

Clean and responsive UI

art-career-insights/ ├── client/ # React frontend │ ├── public/ # Static assets (HTML, icons, etc.) │ ├── src/ # React components, pages, and styles │ │ ├── components/ # Reusable UI components │ │ ├── pages/ # Dashboard pages │ │ └── App.js # Main React app file │ └── package.json # Frontend dependencies │ ├── server/ # Node.js backend │ ├── routes/ # API endpoints │ ├── models/ # Data models (if using MongoDB) │ └── server.js # Main server setup │ ├── data/ # Cleaned CSV dataset for Tableau │ └── Deduplicated_Artist_Roles.csv │ ├── README.md # Project documentation ├── .gitignore # Git ignored files └── package.json # Backend 
dependencies

##Link to a Published Powerbi Dashboard
<iframe title="Art Career Insights Dashboard" width="100%" height="700" src="https://app.powerbi.com/view?r=eyJrIjoiYzI4NWQzOTQtNjE1Yy00N2Q2LWI1MzgtMGNmMjc3N2I5Yjc1IiwidCI6IjgzYzE3ZDkwLTU4MzItNDhiOS04ZWYyLWIyMGY3NjJlYWZiNSIsImMiOjN9&navContentPaneEnabled=false" frameborder="0" allowFullScreen="true"></iframe>



##Embed in GitHub Pages (Static Website)
https://harshithak01.github.io/Art-Career-Insights-platform/dashboard.html

##Contribution
Harshitha- Team Lead

## LIcence
MIT License

