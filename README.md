# Todolist - JAVA API REST

A simple todolist api using java spring boot

## stack

- Spring web
- Spring devtools
- H2 Database

rotas:

- [POST] `/users` => Create new user
  - username
  - email
  - password
- [POST] `/tasks` => Create new task
  - title
  - description
  - startAt
  - endAt
  - priority
- [GET] `/tasks` => List all tasks for a user
- [PUT] `/tasks` => Update task for id