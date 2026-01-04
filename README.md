
## Overview
This is a full-stack application that displays the top-performing sellers for each month, filtered by branch.

## Demo

![Frontend Screenshot](FrontendInterface.png)

## Project Structure

- **TopSellers Dashboard (.NET + React)**
  - **Backend**
    - **SellersReport.API** – .NET Core backend
      - Controllers/
      - Models/
      - Services/
      - SellersReport.API.csproj
      - orders.csv
    - SellersReport.sln
  - **Frontend** – React + TypeScript
    - sellers-report-frontend/
      - node_modules/
      - src/
        - api/ – API service calls
        - components/ – Dropdowns, tables, etc.
        - models/ – TypeScript interfaces
        - pages/ – Page-level components
        - styles/
        - App.tsx
        - index.tsx
        - setupTests.ts
        - react-app-env.d.ts
      - jest.config.js
      - jest.setup.js
      - tsconfig.json
      - package.json

### Features
- Filter by branch
- Monthly top seller report
- REST API in .NET
- Frontend in React

### How to Run
1. `dotnet run` in the backend folder (cd /d "\TopSellers Dashboard (.NET + React)_Vilda\Backend\SellersReport.API")

2. `npm start` in the frontend folder (cd /d "\TopSellers Dashboard (.NET + React)_Vilda\Frontend\sellers-report-frontend")



### Technologies
- .NET 8
- React with TypeScript
- CsvHelper

### Author
Vilda Duan - [LinkedIn](https://www.linkedin.com/in/vilda-duan-518705270/)
