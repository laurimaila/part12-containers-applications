# React application

This application is created from create-react-app.

Install dependencies with `npm install`

You can run the application in development mode with `npm start`

You can build static files for production release with `npm run build`

You can run tests with `npm run test`

## Environment variables

Use REACT_APP_BACKEND_URL to set where the backend for this application is.

Ensin docker build -t todo-front .

Tällä hetkellä toimii docker run -p 3002:80 todo-front

Build dev with docker build -f ./dev.Dockerfile -t todo-front-dev .

docker run -p 3002:3000 todo-front-dev