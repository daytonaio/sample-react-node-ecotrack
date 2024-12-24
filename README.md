<h3 align="center">EcoTrack</h3>
<p align="center">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white">

</p>


## Sample Javascript with React and Nodejs
Welcome to the EcoTrack, a LLM powered web app that calculates the carbon footprint of a family and gives advisory to reduce the carbon footprint.
EcoTrack harnesses the formidable capabilities of OpenAI's Language Model (LLM) via the OpenAI API to empower individuals to make informed decisions for a greener future.

Our app facilitates people to take actions for reducing their carbon footprint by asking users about their daily activity data such as number of people in household, electricity consumption, heating source, distance travelled using various mediums and lifestyle. This data is then processed through OpenAI's Language Model to generate personalized recommendations aimed at reducing users' environmental impact and tackling climate change.

Through our web platform, we seek to increase individuals' awareness of their environmental actions and offer tailored suggestions to decrease the pollution emitted by their daily activities.


## Table of Contents

- [Installation Guide](#installation-guide)
- [Configuration](#configuration)
- [Features](#features)
- [Technologies](#technologies)
- [License](#license)


## Installation Guide
## Getting Started

### Open Using Daytona

1. **Install Daytona**: Follow the [Daytona installation guide](https://www.daytona.io/docs/installation/installation/).
2. **Create the Workspace**:
   ```bash
   daytona create https://github.com/daytonaio/sample-react-node-ecotrack
   ```
3. **Create your own .env file under the backend directory**:
     ```bash
       OPENAI_API_KEY=your-api-key-goes-here
       OPENAI_BASE_URL=your-api-url-goes-here
       PORT=3000
     ```
4. **Start the Application**:

    Go to backend Folder
   ```bash
   npm start
   ```
    Go to frontend Folder
    ```bash
    npm run dev
    ```



## Configuration
- Obtain your OpenAI API key: Visit [OpenAI](https://openai.com/product) to get your API key. You can get it from ```NagaAI``` discord server too.

For the ```OPENAI_BASE_URL``` section, you need to specify the base URL for the API you're using. For example, if you're using the OpenAI API, enter ```https://api.openai.com/v1```. If you're using the OpenAI API from Naga, enter ```https://api.naga.ac/v1```. Ensure that the correct base URL is provided based on the API provider you're working with.

## Features
- Clean and easy to navigate User Interface.
- Calculate Carbon Footprint impact: Accurate calculation of carbon footprint three aspects energy consumption, lifestyle choices and transportaion.
- Personalized insights: Break down of footprint by category, highlighting areas with the most significant impact.
- Actionable advice: Actionable steps to reduce carbon footprint effectively using generative ai based on provided data.


## Technologies

This project is built using the following technologies:

- React: Frontend library for building user interfaces.
- Vite: Frontend build tool for faster development.
- Tailwind CSS: Utility-first CSS framework for styling.
- Express: Backend framework for handling server-side logic.
- Langchain: Language model used for providing carbon footprint reduction advice.
