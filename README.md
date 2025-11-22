#  Student Task Master

I built this Full-Stack application to solve a common problem for students: knowing **what** to do, but not knowing **where to start**.
Instead of just a blank to-do list, this app helps break down big goals (like "Study for an exam") into small, actionable steps automatically.

##  How it works
The core feature is a **Smart Logic Engine** in the backend.
When a user selects a goal (e.g., "Find a Student Job"), the server doesn't just save the title. It processes the request and automatically generates a tailored checklist (Update CV -> Fix LinkedIn -> Apply).

##  Tech Stack
* **Backend:** Java 17, Spring Boot 3 (Maven)
* **Database:** PostgreSQL
* **Frontend:** Vanilla JavaScript, HTML5, CSS3
* **Security:** Spring Security with JWT (JSON Web Token)

##  Key Features
* **Smart Templates:** Pre-defined logic flows for common student tasks.
* **Kanban Board:** Drag-and-drop workflow (Todo / Doing / Done).
* **Authentication:** Secure login and registration system.
* **REST API:** Fully functional API connected to a real database.

##  Running the project
1. Clone the repo.
2. Set up your PostgreSQL database (update `application.properties`).
3. Run the Spring Boot app.
4. Open `index.html` in your browser.
