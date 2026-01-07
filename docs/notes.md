# Technical Notes

## Docker Issue and Solution

While working on the project, I faced a major issue where Docker was not starting properly on my system. After troubleshooting, I discovered that the problem was caused by an outdated version of WSL (Windows Subsystem for Linux). Docker depends on WSL to run correctly on Windows.

To solve this issue, I updated WSL to the latest version using the official update command. After the update, Docker started working normally. Although Docker Compose was somewhat challenging at first, especially understanding how services and containers work together, it was a very interesting experience and made the assignment more exciting.

Overall, working with Docker and Docker Compose was challenging but enjoyable, and it made the assignment really cool.

## Git/GitHub Lesson Learned

The most important lesson I learned from this assignment was how to properly use Git and GitHub for version control. I learned how to commit changes frequently, push updates to a remote repository, and manage my project history. This helped me track my progress, collaborate better, and avoid losing work.

--- 

## Challenges and Solution:

Initially, the deployment did not work because the Vite configuration blocked requests from external hosts. To fix this, I updated the vite.config.js file to allow the Render host by adding it to the allowedHosts array. This enabled the application to run successfully on Render.
 
 allowedHosts: [
      'todolist-app-with-react.onrender.com'
    ]

