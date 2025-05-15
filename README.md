# 14 Full-Stack React: Kanban Board

## Description

This project enhances a Kanban board application by integrating user authentication using JSON Web Tokens (JWT). JWTs are a secure, stateless method for handling authentication in full-stack apps. They allow for compact, URL-safe transmission of user verification data, ensuring that only authenticated users can access and manage their tasks.

## User Story

```
AS A member of an agile team
I WANT a Kanban board with a secure login page
SO THAT I can securely access and manage my work tasks
```

## Acceptance Criteria

```
GIVEN a Kanban board with a secure login page
WHEN I load the login page
THEN I am presented with form inputs for username and password
WHEN I enter my valid username and password
THEN I am authenticated using JWT and redirected to the main Kanban board page
WHEN I enter an invalid username or password
THEN I am presented with an error message indicating that the credentials are incorrect
WHEN I successfully log in
THEN a JWT is stored securely in localStorage for future authenticated requests
WHEN I log out
THEN the JWT is removed and I am redirected to the login page
WHEN I try to access the Kanban board page without being authenticated
THEN I am redirected to the login page
WHEN I remain inactive for a defined period
THEN the JWT expires and I am redirected to the login page upon next action
```

## Demo Preview
[![Watch the video](https://raw.githubusercontent.com/username/repository/branch/path/to/thumbnail.jpg)](https://raw.githubusercontent.com/username/repository/branch/path/to/video.mp4)


### 🚀 Deployment Link

> Live Site: [[https://your-kanban-app.onrender.com](https://kanban-board-2mr4.onrender.com)]

> GitHub Repo: [https://github.com/atrvvm/kanban-board](https://github.com/atrvvm/kanban-board.git)
---

© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
