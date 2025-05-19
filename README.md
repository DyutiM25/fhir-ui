

# FHIR Query UI (Part 2)

This is the React-based frontend for the **AI on FHIR** project. It allows users to input natural language health queries (e.g., _"Show me diabetic patients over 50"_) and visualizes the corresponding results with tables and charts.

## 🖥️ Features

- Text input for natural language queries
- Sends requests to a Flask backend (`/parse` endpoint)
- Displays results in:
  - A table (Name, Age, Condition)
  - A bar chart (Age distribution)
- Simple and intuitive UI

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 recommended)
- npm

### Setup

1. Navigate to the project folder:

   cd part-2/fhir-ui


2. Install dependencies:

   npm install


3. Start the development server:


   npm start


   The app will run at `http://localhost:3000`.


## 🧠 Example Usage

Try queries like:

* `Show me diabetic patients over 50`
* `List asthma patients under 18`
* `Find patients with hypertension above 60`
* `Show cancer patients older than 70`

## 📦 Built With

* [React](https://reactjs.org/)
* [Chart.js](https://www.chartjs.org/) + [react-chartjs-2](https://github.com/reactchartjs/react-chartjs-2)
* [Axios](https://axios-http.com/)

## 📁 Project Structure

```
fhir-ui/
├── src/
│   ├── App.js         # Main React component
│   └── index.js
├── public/
├── package.json
```

## 📄 License

This project is part of a take-home assessment and is for educational/demo purposes only.


