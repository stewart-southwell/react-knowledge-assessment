# Knowledge Assessment

## Instructions

This project is a simple tasklist application that has the following functional requirements.

- A user should be able to add new tasks
- A user should be able to delete tasks
- A user should be able to edit tasks to change the name
  - While a task is in edit mode a user should be able to cancel or save
- A user should be able to mark a task as completed
- A user should be able to filter the task list using the filter button toggles at the top
- The count of the tasks should be updated whenever the tasklist shown changes.

The goal of this assessment is to find and fix all the bugs so that the functional spec above is fulfilled.

### Time Limit

60 Minutes

### Before you begin

1. Run `npm install` to install all the dependencies for the app

### Problems

#### Compile Time Bugs

The first challenge is to fix the compile time errors.

Run `npm start`. You will notice a couple of errors. Please track down and fix the problems identified.
Any change you make will automatically rebuilt and be hot reloaded.
The linter can be your friend here (both the problems tab and the build output in the terminal should show relevant information here).

#### Application Bugs

- The delete button for a task is not working (causes an error)
- The Active filter toggle is not working.  The filter, when active, should only show the tasks that are not yet completed.
- The task counter does not get updated when a filter is active.
- **Bonus** - Currently, when toggling a `<Todo/>` template from viewing to editing the `<input>` field does not receive focus. The expected behavior is that when a user toggles a `<Todo/>` template from viewing to editing, we should focus on the `<input>`used to rename it; when they toggle back from editing to viewing, we should move focus back to the "Edit" button.  **Hint**: ReactJs refs (via the useRef hook) comes in handy here.




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
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
