# Skincare Recommender System

A **full-stack web application** that provides personalized skincare product recommendations.  
The system leverages **Spring Boot** for the backend, **React.js** for the frontend, and **MySQL/PostgreSQL** for the database. It combines default recommendations based on skin type with community-driven suggestions submitted by users.

---

## **Features**

- **Personalized Recommendations:**  
  Suggests skincare products based on individual skin type and concerns.

- **Community-Driven Suggestions:**  
  Users can submit product recommendations; the system aggregates these for others.

- **Interactive Frontend:**  
  - Dynamic UI with **React.js**  
  - Responsive design for multiple devices  
  - Animations with **Framer Motion**  
  - Conditional rendering for real-time interactivity

- **Backend APIs:**  
  REST APIs for:
  - Fetching personalized recommendations  
  - Submitting new user suggestions  
  - Real-time updates to recommendations

- **Database Integration:**  
  - Efficient handling of comma-separated values  
  - Prevents redundancy and ensures data integrity  
  - Supports both **MySQL** and **PostgreSQL**

- **Form Handling & Validation:**  
  Smooth user experience with error handling and validation for user inputs.

---

## **Tech Stack**

 Layer        Technology 
 Frontend     React.js, Tailwind CSS, Framer Motion 
 Backend      Spring Boot (REST APIs) 
 Database     MySQL / PostgreSQL 
 Deployment   Netlify (frontend), Render/Heroku/AWS (backend + DB) 

---

## **Architecture Overview**

1. **Frontend:** React app handles user interaction, forms, and dynamic UI rendering.  
2. **Backend:** Spring Boot REST APIs fetch and submit data to the database.  
3. **Database:** Stores default and community-sourced recommendations efficiently.  
4. **Recommendation Engine:** Combines default and user-submitted suggestions for personalized output.


