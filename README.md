# TodoList App

A simple and user-friendly Todo List web application built using React and Vite.  
The application allows users to add and manage daily tasks through a clean and responsive user interface.  
This project is fully containerized using Docker to allow any developer to run it in minutes.

---

## Demo Video
https://github.com/user-attachments/assets/eda8c7df-7b08-4e5d-8477-8ac96930b6e5


## Tech Stack
- React
- Vite
- Docker
- Docker Compose (Bonus)

---

## How to Build and Run Using Docker

### Step 1: Build the Docker Image

docker build -t todo-app .



### Step 2: Run the Container docker 

run -p 5173:5173 todo-app

### Run Using Docker Compose
docker compose up --build
Then open:
http://localhost:5173
 
 ### How to Stop the Container and Clean Up

 ### Stop the running container
Press:
CTRL + C

### Configuration Notes
The application runs on port 5173

No environment variables are required

Port mapping used:

5173:5173

### How to Test the Application

Run the project using Docker or Docker Compose

Open a browser and navigate to:

http://localhost:5173

Author : Future Teaching Assistan in IUG 🔥🔥
Saleem Wael Qandeel

