# WINshop

## API Spec

## Database Schema

### 1. User

| no  | attributes | type   | description                |
| --- | ---------- | ------ | -------------------------- |
| 1.  | name       | String | name of user               |
| 2.  | email      | String | email of user              |
| 3.  | password   | String | user password              |
| 4.  | isAdmin    | Bool   | admin or not               |
| 5.  | gender     | String | gender of user             |
| 6.  | timestamps | Date   | time when user take action |

### 2. Product

| no  | attributes | type   | description |
| --- | ---------- | ------ | ----------- |
| 1.  | name       | String |             |
| 2.  | slug       | String |             |
| 3.  | image      | String |             |
| 4.  | brand      | String |             |
| 5.  | category   |        |             |
| 6.  |            |        |             |

### 3. Order

|     |     |     |     |     |
| --- | --- | --- | --- | --- |
|     |     |     |     |     |
|     |     |     |     |     |
|     |     |     |     |     |

## Run Locally

### 1. Clone repo

```
$ git clone https://github.com/ILHAM2134/TechnicalTest-WIN.git
$ cd TechnicalTest-WIN
```

### 2. Create .env File

- duplicate .env.example in backend folder and rename it to .env

### 3. Run Backend

```
$ cd backend
$ npm install
$ npm audit fix --force
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm audit fix --force
$ npm start
```

### 5. Seed Users and Products

- Run this on browser: http://localhost:5000/api/seed
- It returns admin email and password and 6 sample products

### 6. Admin Login

- Run http://localhost:3000/signin
- Enter admin email and password and click signin
