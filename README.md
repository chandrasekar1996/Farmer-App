# Farmer-App

React native app with android release settings.

## Development Setup

- Clone Repository: `git clone HTTPS/SSH Url`
- Move to root directory: `cd Farmer-App`
- Install dependency: `npm install`
- Starting Proejct: `npx react-native run-android`

## Folder Structure

    Farmer
    │
    └───src
    │   │
    │   └───action (Contains all action methods)
    |       |   actionConstants.js (Contants specific to actions & reducers)
    │   │
    │   └───assets
    │       └───fonts (Contains all fonts used in application)
    │       └───images (Contains all images used in application)
    │   |
    |   └───common
    |       |   applicationConstants.js (Contains all application level constants)
    |       |   connect.js (Contains API call helpers)
    |       |   localStorage.js (Contains helpers to access local storage values)
    |       |   urls.js (All the urls used in the application)
    │   |
    │   └───components (Includes all the components in application)
    │       └───Common (Common helper components)
    │   |
    │   └───container (Parent Of the Page)
    │       └───All Pages (with page folder and js file)
    |
    │   └───Layout (Child Of the Container)
    │       └───All Pages Layout design (with page folder and js file)
    |
    │   └───Layout Component (Child Of the Layout)
    │       └───All Pages Components design (with page folder and js file) 
    │   |
    │   └───reducers (Includes all the redux reducers)
    |       |   index.js (All reducers are combined into parent reducer)
    │   |
    │   └───styles (Includes common style and font size settings)

## Developer Best Practice

- Maintain proper namespacing for folders, files, variable and function declarations.
- Format code using [Prettier](https://www.npmjs.com/package/prettier) package.
- Always create feature or bug branches and then merge with stable master branch.
- Provide proper commit messages & split commits meaningfully.
