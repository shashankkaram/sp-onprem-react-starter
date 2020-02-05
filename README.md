This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, run:

### `npm i`

Installs the required project dependencies.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
The project was built assuming it is hosted at `/SiteAssets/react-starter/`.<br/>
You can control this with the `homepage` field in your `package.json`.

Your app is ready to be deployed!
Copy the `static` folder and the `index.html` from the build folder into the SharePoint folder specified in the homepage field. <br />
Add a content editor web part on the SharePoint page and point it to the index.html file to view your app.

## Additional Notes

1. The `browserslist` property in package.json was modified to include `ie 11`, so that the app works in IE11.
2. If the app does not load correctly on the SharePoint page, check the dev tools console for any 404 errors related to loading js/css files. Update the references in the index.html file as needed
