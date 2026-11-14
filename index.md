## Technical Skills
* **Languages:** Java, C#, C++, Python, JavaScript
* **Tools and Frameworks:** Git, GitHub Actions, Maven, Node.js, Angular, Express, JUnit 5, .NET MAUI,
* **Concepts:** OOP, Data Structures and Algorithms, SQL, REST APIs, Testing, CI/CD, Software Architecture

---

## Projects and Applications

### Appointment Book
* Upgraded a Java-based appointment management application to use persistent SQLite database storage instead of temporary in-memory data structures. Implemented a layered architecture separating data models, database operations, and business logic. Expanded automated testing and configured GitHub Actions to run tests as part of a continuous integration workflow.

* Technologies & Tools: Java, SQLite, JDBC, Maven, JUnit 5, Git/GitHub, GitHub Actions.

  * Implemented JDBC-based database operations using parameterized SQL queries to insert and retrieve appointment records. Used prepared statements and automatic resource management to interact with the SQLite database safely and reliably.

    <div style="text-align:center; margin:20px 0;">
      <img src="images/DAOAddGetAppt.png"
           alt="AppointmentDAO Add and Get Methods"
           style="max-width:100%; height:auto;">
      <p><em>AppointmentDAO — SQLite Database Operations</em></p>
    </div>
 
   * JUnit 5 tests verifying appointment creation, retrieval, deletion, and updates. Tests interact with the SQLite database and use assertions to confirm that database operations produce the expected results.
 
    <div style="text-align:center; margin:20px 0;">
      <img src="images/DAOTest.png"
           alt="AppointmentDAO - Database Integration Testing"
           style="max-width:100%; height:auto;">
      <p><em>AppointmentDAO - Database Integration Testing</em></p>
    </div>
 
   * Configured a GitHub Actions CI workflow to automatically build and execute the Maven/JUnit test suite on each push. All 46 tests pass, verifying application functionality and database operations.
    
    <div style="text-align:center; margin:20px 0;">
      <img src="images/CIWorkflow.png"
           alt="GitHub Actions CI Workflow"
           style="max-width:100%; height:auto;">
      <p><em>GitHub Actions CI Workflow</em></p>
    </div>

### Full Stack Travel Webpage
* Enhanced a full-stack travel application featuring a public-facing website and an administrative dashboard. Worked with an Angular frontend and a Node.js/Express backend connected to MongoDB through Mongoose. Implemented and refined REST API functionality for retrieving and managing travel listings, along with administrative authentication and access.
  
* Technologies & Tools: JavaScript, Node.js, Express.js, Angular, MongoDB, Mongoose, REST APIs, Handlebars, Bootstrap, Git/GitHub.

  * Implemented administrative functionality using Angular to add new travel listings.

    <div style="text-align:center; margin:20px 0;">
      <img src="images/AdminAdd.png"
           alt="Admin Add Trip Page"
           style="max-width:100%; height:auto;">
      <p><em>Admin Add Trip Page</em></p>
    </div>
 
  * Developed the administrative listing view to display and manage travel listings retrieved from the backend API.
 
    <div style="text-align:center; margin:20px 0;">
      <img src="images/travlr.png"
           alt="Admin Trips Listing Page"
           style="max-width:100%; height:auto;">
      <p><em>Admin Trips Listing Page</em></p>
    </div>
 
  * Documented interactions between the frontend, backend API, and database.
    
    <div style="text-align:center; margin:20px 0;">
      <img src="images/SequenceDiagram.png"
           alt="Application Architecture"
           style="max-width:100%; height:auto;">
      <p><em>Application Architecture</em></p>
    </div>

---

## Education
* B.S. in Computer Science (Software Engineering) - SNHU 2026
* A.A.S in Physical Therapist Assistant - Blinn College 2019
* B.S. in Kinesiology - Texas A&M 2013

## Professional Experience
* 7 Years in hospital and rehabilitation settings as a licensed Physical Therapist Assistant
* History working on multidisciplinary teams, creating and achieving client/patient centered goals
