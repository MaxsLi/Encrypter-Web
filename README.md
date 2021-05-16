# [Encrypter-Web](https://encrypter-web.herokuapp.com/)

Web version of Python script [Encrypter](https://github.com/MaxsLi/Encrypter).

## Description

The client side (this repo) is written using [React](https://reactjs.org/) with [Material-UI](https://material-ui.com/).

The server side ([Encrypter-API](https://github.com/MaxsLi/Encrypter-API)), is written in [Flask](https://flask.palletsprojects.com/en/1.1.x/).

Where the server side imports sciprt [Encrypter](https://github.com/MaxsLi/Encrypter) remotely using [httpimport](https://github.com/operatorequals/httpimport).

```
┌───────────────────┐      ┌───────────────────┐      ┌─────────────┐
│   encrypter-web   │ ---> │   Encrypter-API   │ ---> │  Encrypter  │
│      (Client)     │ <--- │      (Server)     │ <--- │   (Script)  │
└───────────────────┘      └───────────────────┘      └─────────────┘
```

This web application is currently hosted on Heroku, [**link**](https://encrypter-web.herokuapp.com/).

## Available Scripts

### `yarn`

Install all required packages.

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Screenshots

| Light Theme    | Dark Theme   |
| :------------: | :----------: |
| ![Home page in light theme](/static/screenshot1.png) | ![Encrypt text in dark theme](/static/screenshot3.png) |
| ![Encrypt text in light theme](/static/screenshot2.png) | ![Error input in dark theme](/static/screenshot4.png) |