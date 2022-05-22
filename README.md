# Getting Started with Boilerplate

In the project directory, you can run:

### Native mode
```bash
yarn install

# Downloads all dependencies declared in package.json
```


```bash
yarn start

# Runs the app in the development mode.\
```
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

```bash
yarn run build

# Builds the app for production to the build folder.\
```
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


### Docker mode
```bash
yarn run dev

# Runs internally docker compose up to start app locally
```


```bash
yarn run prod

# Runs docker compose build to start app to deploy
```


## Enviroments

```dosini
# .env.local, not committed to repo

REACT_APP_BASE_URL=localhost:3000
```
