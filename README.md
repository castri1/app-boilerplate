# NODE Application Template

This is a starter template for developing node.js applications using typescript.

Includes:
* Nodemon configuration for typescript and vscode debugging.
* Tests using jest
* Eslint configuration with prettier
* Swagger configuration enabled to document your api

To start developing:

First install all the dependencies:
`yarn install` or `npm start`

Avaible scripts:
* `yarn start`: this will run the application using ts-node, you can attach a debugging session pressing `F5` in VSCode.
* `yarn dev`: runs nodemon to monitor file changes and also runs `start` script configuration
* `yarn build`: transpiles application TS files and adds them into a build folder.
* `yarn test`: runs unit tests using jest.
