# theVelops linter

## How to use
1. Copy this file into the root of your project
2. Add these scripts into the `package.json` file of your project
    ```json
    "scripts": {
      "test": "eslint . && jest tests/",
      "lint": "eslint .",
      "lint:fix": "eslint . --fix"
    }
    ```
3. Install the required packages
```sh
$ npm install eslint babel-eslint eslint-plugin-react@latest --save-dev
```

4. For running eslint and jest
```sh
$ npm run test
```
And for running just eslint 
```sh
$ npm run lint
```
