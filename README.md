# Library Management System

A MERN stack web application for handling library operations such as member management, book management, and book issue/return transactions.

![Library Management System](https://user-images.githubusercontent.com/73348574/205624307-6a1b18fa-5ef7-4de9-b141-9225eca62c6c.png)

## Quick Links

- [Video Demo](#video-demo)
- [Features](#features)
- [Setup](#setup)
- [Frontend Setup](#frontend-setup)
- [Backend Setup](#backend-setup)
- [Technologies](#technologies)
- [Screenshots](#screenshots)
- [References](#references)
- [Author](#author)
- [Connect](#connect)
- [License](#license)

## Video Demo

[Watch the demo](https://drive.google.com/file/d/1gddUdOE41WaEyY4OWoJtDa0l6VJZTg94/view?usp=sharing)

Show some love and star the repository to support the project.

## Features

| Module | What It Supports |
| --- | --- |
| Authentication | Admin login and student login |
| Dashboards | Separate admin and student dashboard views |
| Members | Add and manage library members |
| Books | Add books and track available copies |
| Transactions | Track issue and return activity for books and members |
| Reservations | Reserve books for selected dates |
| Community | Display achievements and event gallery |

## Setup

Fork the repository, then clone it to your local machine:

```bash
git clone <repo-url>
```

## Frontend Setup

1. Move into the frontend directory:

   ```bash
   cd frontend
   ```

2. Install dependencies:

   ```bash
   yarn
   ```

3. Create a `.env` file and add the variables shown in `.env.example`.

4. Start the frontend:

   ```bash
   yarn start
   ```

## Backend Setup

1. Move into the backend directory:

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   yarn
   ```

3. Create a MongoDB account and get the `MONOGO_URL` for connecting the server with the database.

4. Create a `.env` file and add the variables shown in `.env.example`.

5. Start the server:

   ```bash
   nodemon server.js
   ```

   Nodemon should be installed globally before running this command.

## Technologies

- ReactJS with Hooks
- Node.js
- Express.js
- MongoDB

## Screenshots

![Screenshot 1](https://user-images.githubusercontent.com/73348574/205623377-999c0de5-6796-4100-85e6-96e3e7d4fb77.png)
![Screenshot 2](https://user-images.githubusercontent.com/73348574/205632416-bfcc2c19-3f70-4688-bb7e-0ccd83be3038.png)
![Screenshot 3](https://user-images.githubusercontent.com/73348574/205632598-6b009820-20ec-4e9f-92bf-00af92d4f1a4.png)
![Screenshot 4](https://user-images.githubusercontent.com/73348574/205632198-d99fcc8d-903d-4b60-9cec-56f8e0716290.png)
![Screenshot 5](https://user-images.githubusercontent.com/73348574/205631397-2793e97e-3cc6-4b60-8ee1-ec81716b9d6d.png)
![Screenshot 6](https://user-images.githubusercontent.com/73348574/205631670-5dcb6437-afb1-4aaf-87d7-b47c3b01d7b1.png)
![Screenshot 7](https://user-images.githubusercontent.com/73348574/205631804-6c631b5e-8bcd-41c4-bb73-bab6ea8b78f7.png)
![Screenshot 8](https://user-images.githubusercontent.com/73348574/205631977-f393ca09-aa24-42a5-9bd7-d92d471c514c.png)

## References

- [Node.js Documentation](https://nodejs.org/en/docs/)
- [React Documentation](https://reactjs.org/docs/getting-started.html)

## Author

- [@iampranavdhar](https://www.github.com/iampranavdhar)

## Connect

[![twitter badge](https://img.shields.io/badge/twitter-Pranavdhar-0077b5?style=social&logo=twitter)](https://twitter.com/iampranavdhar)<br/>
[![linkedin badge](https://img.shields.io/badge/linkedin-Pranavdhar-0077b5?style=social&logo=linkedin)](https://in.linkedin.com/in/sai-pranavdhar-reddy-nalamalapu-038104206)

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for details.
