
# 🥗 Daily Diet

> A system to record a user's meals and track their eating journey.

## Getting Started

To start the application on a specific port (3333), use:

```bash
bun dev
```

The application uses environment variables to define the database and port, so create a `.env` file and set the environment variables.

```env
PORT=3333
DATABASE_URL=./db.sqlite
```

End-to-end tests also use environment variables, so create a `.env.test` file and set the environment variables.

```env
DATABASE_URL=./db-test.sqlite
```

Here we define only a new variable for the test database to be separated, so to run the tests, use (we only use end-to-end tests in this project):

```bash
bun run test
```

## Application Rules

- [x] It must be possible to create a user.
- [x] It must be possible to identify the user between requests.
- [x] It must be possible to record a meal with the following information:
  - Name
  - Description
  - Date and Time
  - Whether it is within the diet or not
- [x] Meals must be related to a user.
- [x] It must be possible to list all meals for a user.
- [x] It must be possible to view a single meal.
- [x] It must be possible to edit a meal, being able to change all the above data.
- [x] It must be possible to delete a meal.
- [x] It must be possible to retrieve user metrics:
  - Total number of registered meals.
  - Total number of meals within the diet.
  - Total number of meals outside the diet.
  - Best streak of meals within the diet.
- [x] A user can only view, edit, and delete meals that they created.

## ☕ Contact

You can find me on any of the social networks below:

<a href="https://www.linkedin.com/in/nathanpalatin/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
