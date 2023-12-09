# HW 9

Homework untuk Week 9

## Available Scripts

Di project ini daat me run dengan :

### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

<details>
<summary>🧰Dependencies</summary>

```gradle
dependencies: {
    "bcrypt": "^5.1.1",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "jsonwebtoken": "^9.0.2",
    "morgan": "^1.10.0",
    "pg": "^8.11.3",
    "sequelize": "^6.35.1"
  }
```
</details>

<details>
<summary>API </summary>

- Endpoint
  `Get`

  > http://localhost:3000/users/
  > http://localhost:3000/movies/
  > http://localhost:3000/movies/:id

  - Endpoint
  `Post`

  > http://localhost:3000/users/login
  > http://localhost:3000/users/register
  > http://localhost:3000/movies/create
  > http://localhost:3000/movies/:id

    - Endpoint
  `Put`

  > http://localhost:3000/movies/update/:id

  - Endpoint
  `Delete`

  > http://localhost:3000/movies/delete/:id


    </details>
