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
<div style="position: relative; padding-bottom: 56.25%; height: 0;"><iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" src="https://www.tella.tv/video/cmapefphk00090blb8x4va7xt/embed?b=0&title=0&a=0&loop=1&t=0&muted=0&wt=0" allowfullscreen allowtransparency></iframe></div>

### 🚀 Deployment Link

> Live Site: [[https://your-kanban-app.onrender.com](https://kanban-board-2mr4.onrender.com)]

> GitHub Repo: [https://github.com/atrvvm/kanban-board](https://github.com/atrvvm/kanban-board.git)
---

© 2024 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
