![FireShot Capture 038 - Random Ideas - randomidea-m9cr onrender com](https://github.com/agunduuz/random-idea/assets/76620858/6d9aee3e-008b-48ed-8145-111fffe17209)

# Welcome to Random Idea👋
[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/agunduuz/random-idea)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](#)
[![Twitter: frontendanil](https://img.shields.io/twitter/follow/frontendanil.svg?style=social)](https://twitter.com/frontendanil)

> App for tracking calories, meals and workouts with use the HTML, CSS, JavaScript and Webpack

### 🏠 [GitHub](https://github.com/agunduuz/random-idea)

### ✨ [Live](https://randomidea-m9cr.onrender.com/)

## Install Dependencies on the Front-End & Back-End

```bash
npm install
```
* Front-End
```bash
cd client
npm install
```

## Back-end/Express Server

```bash
npm start
```

or

```bash
npm run dev (Nodemon)
```

Visit `http://localhost:5000`

## Front-End / Webpack Dev Server

```bash
cd client
npm run dev
```

Visit `http://localhost:3000`

To build Front-End production files

```bash
cd client
npm run build
```

* The production build will be put into the `public` folder, which is the Express static folder.

## Environment Variables

`.env` and add your MongoDB URI to the `.env` file.

```
MONGO_URI=your_mongodb_uri
```

## REST Endpoints

### Ideas

| Endpoint       | Description    | Method | Body                    |
| -------------- | -------------- | ------ | ----------------------- |
| /api/ideas     | Get all ideas  | GET    | None                    |
| /api/ideas/:id | Get idea by id | GET    | None                    |
| /api/ideas     | Add idea       | POST   | { text, tag, username } |
| /api/ideas/:id | Update idea    | PUT    | { text, tag, username } |
| /api/ideas/:id | Delete idea    | DELETE | username                |

* When updating or deleting, the username must match the username of the idea creator.

## Author

👤 **Anıl Gündüz**

* Twitter: [@frontendanil](https://twitter.com/frontendanil)
* Github: [@agunduuz](https://github.com/agunduuz)
* LinkedIn: [@anilgunduuz](https://linkedin.com/in/anilgunduuz)

## Show your support

Give a ⭐️ if this project helped you!
