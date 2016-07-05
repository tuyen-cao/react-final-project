# react-final-project
final project for trainees at company: todolist

Screenshot:
![todolist wireframe](https://www.dropbox.com/s/gdmvppq8wzyxx8w/Screenshot%202016-07-05%2011.30.38.png?dl=0 "todolist wireframe")

## step 1: redux
using react + redux to build a todo list application. the user can:
- input a new content, click the 'Add' button to insert a todo
- toggle a todo: completed (true/false)
- filter the todo list
  - all: get all the list
  - completed: get only completed todos
  - active: get only not completed todos

  when a filter is active, it will display in plain text, instead of a link

## step 2: improve
- step-2-1: logger
  using redux middleware, log every action to know:
  - previous state
  - current action
  - next state

- step 2-2: local storage
  add local-storage to allow saving persistent data,
  so when we add new todos and refresh the list, the list wont be empty

- step 2-3: react router - simple
  apply react router, create the index path '/' to map to the todo list

- step 2-4: react router - filter
  add an option parametter 'filter' to allow view filtered list in different routes:
  - / or /all: all todos
  - /active: only active todos
  - /completed: only completed todos

## step-3: refactor with best practices
  Aplly best practices to refactor the whole application

# Evaluation

each trainee will work on different branches
and push them to this repo (not before the deadline)
using the following pattern: [your-name/[step-name],
  - loc-phan/step-1
  - loc-phan/step-2-1
  - loc-phan/step-2-2
  - loc-phan/step-2-3
  - loc-phan/step-2-4
  - loc-phan/step-3

| Step | Score (%) |
|------|-----------|
|   1  |     60    |
|  2-1 |     10    |
|  2-2 |     10    |
|  2-3 |     10    |
|  2-4 |     5     |
|   3  |     5     |
