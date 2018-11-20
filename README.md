
# AirTM Boilerplate

This is a boilerplate that rely on the following structure for development:
```
▾ src/
  ▾ components/
    ▾ App/
      ▸ __tests__/
          App.test.js
      App.css
      App.js
      index.js
    ▾ AddFundsPage/
      ▸ __tests__/
          AddFundsPage.test.js
          ...
      AddFundsPage.js
      index.js
      ...
    ▾ NotFoundPage/
      ▸ __tests__/
          NotFoundPage.test.js
          ...
      NotFoundPage.js
      index.js
      ...
    ▾ Shared/
      ▸ __tests__/
          SharedComponent1.test.js
          SharedComponent2.test.js
          SharedComponent3.test.js
          ...
      SharedComponent1.js
      SharedComponent2.js
      SharedComponent3.js
      ...
    ▾ WithdrawPage/
      ▸ __tests__/
          WithdrawPage.test.js
      WithdrawPage.js
      index.js
    ▸ OtherComtainer1Page/
    ▸ OtherComtainer2Page/
    ▸ OtherComtainer3Page/
    ...
  ▾ store/
    ▾ actions/
      ▸ __tests__/
          addFundsAction.test.js
          ...
      addFunds.js
      ...
    ▾ middleware/
      index.js
    ▾ reducers/
      ▸ __tests__/
          addFundsReducer.test.js
          ...
      addFundsReducer.js
      ...
    ▾ sagas/
        index.js
  ▾ tests/
      i18n.test.js
      store.test.js
      helpers.test.js
  ▾ translations/
      en.json
  ▾ utils/
      helpers.js
  index.css
  index.js
  logo.svg
  serviceWorker.js
  package.json
  README.md
```

There is also other three folders in the root path `build`, `public` and `config`:

- `build/` - Production ready version
- `public` - Here is the plublic resources, and the `index.html` respossible to load the entiry app
- `config` - General configurations for webpack, envs, paths and others. 

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Initial Resources

- React
- Redux - State Manager
- Saga/Thunk - Asynchronous call for Redux
- React Router - Routes for React
- Reselect - Selector library for Redux 
- React-Intl - Internationalize React apps
- Jest - Test library
- Enzyme - Test library for React components

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
