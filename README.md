# knowdroids software engineer assignment 

- create a docker compose project with two services
  - `api`
    - API written in python using fastapi framework
    - two public routes - GET and POST `/tasks`, one to fetch all tasks, second to create a new task
    - tasks has an `id`, `name` and `completion_status`
    - managed by poetry package manager
    - handle db init with alembic migration tool
    - write Dockerfile for it (no need to cache anything)
  - `db`
    - postgresql database
    - with persistent data volume (so compose up and down won`t lose data)
- the project should be easily started with `docker compose up`
- push it to public github repo and mail to jakub.jun@knowdroids.ai next week 7.10. - 13.10.
