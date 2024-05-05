

# Fintastic

* *Date Created*: 03 March 2024
* *Last Modification Date*: 03 March 2024
* *Deployed frontend website URL*: <https://fintastic-grp-14.netlify.app>
* *Deployed backend URL*:https://web-grp-14.onrender.com/
* *Git URL*: <https://git.cs.dal.ca/gosaliya/CSCI-5709-Grp-14>

* *Group 14 main branch Git URL*: <https://git.cs.dal.ca/gosaliya/CSCI-5709-Grp-14.git>

## Individual GIT URL
* *Group 14 Raman branch Git URL*: <https://git.cs.dal.ca/gosaliya/CSCI-5709-Grp-14/-/tree/feature-ramandeepkaur?ref_type=heads>

## Author
* [Ramandeep Kaur](rm661081@dal.ca) - *(Developer)*

# FinTastic Financial Management Platform

FinTastic is a cutting-edge financial management platform meticulously crafted to empower users in navigating their financial journeys with confidence. With a rich array of features, FinTastic offers a holistic approach to financial well-being, catering to individuals from diverse backgrounds and professions.

## Individual Feature

### Objective Key Results (OKR) Tracker
The OKR tracker assists users in setting and tracking their financial goals and objectives. This feature allows users to define SMART (Specific, Measurable, Achievable, Relevant, Time-bound) goals, track progress towards these goals.

## Technologies Used

### Frontend
- React.js: JavaScript library for building user interfaces
- React Router: Declarative routing for React applications
- Axios: Promise-based HTTP client for making requests to the backend API
- SweetAlert2: Library for displaying nice-looking alert messages
- Material-UI: React components implementing Google's Material Design

### Backend
- Node.js: JavaScript runtime environment
- Express.js: Web application framework for Node.js
- MongoDB: NoSQL database for storing application data
- Mongoose: MongoDB object modeling tool for Node.js
- JWT: JSON Web Tokens for user authentication
- CORS: Cross-Origin Resource Sharing middleware


## Folder Structure for Individula work

/frontend
  /src
    /Components
      /okr
        /js
          - AddObjective.js: Component to add a new objective including title and timeframe
          - Home.js: Component to render all objectives and key results
          - ObjectiveView.js: Component to view the objective progress, key results, and their progress, and to edit or delete key results
          - UpdateKR.js: Custom popup used to add or delete key results
        /css
          - (CSS files for the OKR components)


/backend
  /controllers
    - objectiveController.js: Controller for handling objectives
  /routes
    - okrRoutes.js: Routes for the OKR functionality
  /models
    - okrModel.js: Model for objectives (title and timeframe) 
    - keyResultModel.js: Model for key results (title and progress)



## Installation and Setup

1. Clone the repository:
 https://git.cs.dal.ca/gosaliya/CSCI-5709-Grp-14.git


2. Navigate to the project directory:


3. Install dependencies for both frontend and backend:

cd frontend
npm install
cd ../backend
npm install


4. Set up the MongoDB database:
   - Install MongoDB locally or use a cloud-based MongoDB service like MongoDB Atlas.
   - Create a database and configure the connection by adding env file..

5. Start the backend server:
npm start


6. Start the frontend development server:

cd ../frontend
npm start


7. Access the application in your web browser at http://localhost:3000.

## Usage

- Register a new account or log in with existing credentials.
- Navigate through the dashboard/navbar (under Profile you can see OKR, click on that to access it) to manage objectives and key results.
- Use the search feature to find objectives by title.
- Add, edit, or delete objectives and associated key results.
- Log out when done using the application.



## References

- **SweetAlert:** 
  - Website: [SweetAlert](https://sweetalert.js.org/)
  - GitHub Repository: [SweetAlert GitHub](https://github.com/sweetalert2/sweetalert2)

- **Material-UI:**
  - Website: [Material-UI](https://material-ui.com/)
  - GitHub Repository: [Material-UI GitHub](https://github.com/mui-org/material-ui)

- **FontAwesome:**
  - Website: [FontAwesome](https://fontawesome.com/)
  - GitHub Repository: [FontAwesome GitHub](https://github.com/FortAwesome/Font-Awesome)