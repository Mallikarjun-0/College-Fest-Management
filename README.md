
# College Festival Management System

### Description

In this project I built a web application for College Festival Management, this application is a goto for every person/user involved in organising college fest, participaitng in college fest, Managing events, logistics.

### Tech Stack

- ReactJS for frontend
- NodeJS for backend

### Database

- PostgreSQL
A remote or local database can be connected.\
Add a file nammed db.js in the server folder and pase the following code.\
```bash

import * as pg from 'pg'
const { Pool } = pg.default;


const pool = new Pool({
    user: "USER_NAME",
    password: "PASS",
    host: "localhost",
    port: port_no,
    database: "postgres"
});

export default pool;

```

Replace the following:\
USER_NAME : PostgreSQL username in the local/remote server\
PASS : password of the database\
port_no : Port on which the database is accessible

### Run

Add the db.js file as shown in the Database part above.

Run client app using the following commands:

```bash


```
Run server app using the following commands:

```bash


```

### Demo(Screenshots)

