
# Face Recognition Web App

This project is deployed with Heroku at this [link](https://frontend-face-recognition.herokuapp.com/).

This is a web application that allows users to provide links of images
and then, using the [Clarifai Face Recognition API](https://clarifai.com/models/face-detection-image-recognition-model-a403429f2ddf4b49b307e318f00e528b-detection),
the application visually indicates where the faces in the image are located.

Total number of images submitted by a given user and user login information is 
stored in a PostgreSQL database, more information can be found at the GitHub repo
for the backend [here](https://github.com/AustinMoninger/face-recognition-backend).

## What I Learned

How to...

* use React components and props
* use node package manager
* keep track of state in a web app

## Available Scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

