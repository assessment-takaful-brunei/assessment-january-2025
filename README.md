# assessment-january-2025

# Assessment: Islamic Insurance Product Management System

## Objective
Evaluate your ability to:
1. Build a simple backend service that serves Islamic insurance product information.
2. Create a frontend that interacts with the backend to display products.
3. Demonstrate basic coding, problem-solving, and documentation skills in the context of Islamic insurance.

---

## Part 1: Backend Development (30 Minutes)

### Scenario
You are tasked with creating an API to manage Islamic insurance products (Takaful products). Each product must have the following information:
- **Product ID** (Unique identifier)
- **Product Name** (e.g., Takaful Plan A)
- **Type** (e.g., Family Takaful, General Takaful)
- **Premium** (Amount to be paid by the participant)
- **Coverage Type** (e.g., Health, Life, Property)
- **Shariah Compliance** (Boolean: `true` if the product is Shariah-compliant)

### Task
1. **Create a backend service** using your preferred framework (e.g., FastAPI, Flask, or Node.js) that exposes an endpoint `/products`.
   - The API should return a list of sample Islamic insurance products (hardcoded for simplicity).
   - Example of the data to be returned:
     ```json
     [
       {
         "id": 1,
         "name": "Takaful Plan A",
         "type": "Family Takaful",
         "premium": 100,
         "coverage_type": "Health",
         "shariah_compliant": true
       },
       {
         "id": 2,
         "name": "Takaful Plan B",
         "type": "General Takaful",
         "premium": 200,
         "coverage_type": "Property",
         "shariah_compliant": false
       }
     ]
     ```

2. **Optional Bonus**
   - Implement a filtering feature using query parameters:
     - Filter by `type` (e.g., `type=Family Takaful`).
     - Filter by `shariah_compliant` (e.g., `shariah_compliant=true`).

---

## Part 2: Frontend Development (45 Minutes)

### Scenario
You need to create a user interface to display the Islamic insurance products fetched from the backend.

### Task
1. **Build a frontend application** (HTML/JavaScript, React, or Vue) that:
   - Fetches data from the backend API `/products`.
   - Displays the product `name`, `premium`, `coverage_type`, and whether it's `shariah_compliant` (yes/no).
   - Display the products in a neat table or list format.

2. **Optional Bonus**
   - Add a simple **search box** that allows users to filter products by their `type` (e.g., "Family Takaful").

---

## Part 3: Documentation (15 Minutes)

### Task
1. Write a **README file**:
   - Describe how to run the backend and frontend locally.
   - Explain the purpose of each field in the product data (e.g., `type`, `premium`, `shariah_compliant`).
   - Include instructions for setting up the development environment.

---

## Part 4: Deployment and Testing (Optional, 20 Minutes)

### Scenario
Now that the app is functional, you need to consider how you would deploy it.

### Task
1. Write a short description of how you would deploy both the backend and frontend to a cloud platform (e.g., AWS, Heroku, or Vercel).
   - Include steps for deploying the backend as an API.
   - Include steps for hosting the frontend (if using a framework like React or Vue).

---

## Evaluation Criteria

| **Skill**              | **Criteria**                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Backend Development     | Correctness and clarity of API implementation, data structure, and error handling. |
| Frontend Development    | Clean, user-friendly UI, correct data fetching, and filtering.             |
| Problem Solving         | Ability to implement filtering and querying based on requirements.        |
| Documentation           | Clarity of README, completeness of instructions, and understanding of the context. |
| Deployment (Optional)   | Clear, step-by-step deployment instructions.                              |

---

## Instructions for the Candidate
1. Use any tech stack you are comfortable with (e.g., **FastAPI**, **Flask**, **Node.js** for the backend and **React**, **Vue**, **HTML/CSS/JavaScript** for the frontend).
2. Submit your solution as a GitHub repository or a `.zip` file with the code and README file.
3. Ensure the solution runs locally without errors. 
4. You may use Google or documentation to complete the tasks.

---

## Islamic Insurance Context
- **Takaful** is an Islamic insurance system based on mutual cooperation where participants contribute money into a pool to help each other in times of need. 
- **Shariah compliance** ensures that the products are in line with Islamic law, avoiding investments in prohibited areas (e.g., alcohol, gambling).

Good luck!
