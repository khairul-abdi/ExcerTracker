# ExcerTracker

### In this App, we need 5 dependencies below:

- Express.js
- React.js
- Bootstrap
- Axios
- MongoDB

### Quick Start

```bash
# Install dependencies
- Backend
$ cd backend && npm install

- Frontend
$ cd frontend && npm install

# Database

Using MongoDB
Example: 
- const uri = mongodb+srv://<username>:<password>@cluster0-nqgmm.gcp.mongodb.net/test?retryWrites=true&w=majority


# Start App
- Backend
$ cd backend && npm run dev

- Frontend
$ cd frontend && npm run dev

App Run On: http://localhost:3000

```

### Test the APIs Using Postman

#### User Add : http://localhost:5000/users/add
Request : POST
Key :
  - username : ...

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/user-add.png)


#### All User : http://localhost:5000/users
Request : GET

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/all-user.png)


#### Add Exercises : http://localhost:5000/exercises/add
Request : POST
Key :
  - username : ...
  - description: ...
  - duration: ...
  - date: ...
  
  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/add-exercises.png)


#### Get Exercises By Id  : http://localhost:5000/exercises/:id
Request : GET

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/get-exercises-by-id.png)


#### All Exercises  : http://localhost:5000/exercises
Request : GET

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/all-exercises.png)


#### Update Exercises  : http://localhost:5000/exercises/update/:id
Request : POST
Key :
  - username : ...
  - description: ...
  - duration: ...
  - date: ...

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/update-exercises.png)

#### DELETE Exercises  : http://localhost:5000/Qexercises/update/:id
Request : DELETE

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/delete-exercises.png)

### Demo

<!-- #### All Exercises  : http://localhost:5000/Qexercises/update/:id
Request : DELETE

  ![alt text](https://github.com/khairul-abdi/ExcerTracker/blob/master/frontend/public/img/delete-exercises.png) -->
