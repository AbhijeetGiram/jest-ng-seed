> npm uninstall karma karma-chrome-launcher karma-coverage karma-jasmine karma-jasmine-html-reporter

> npm install jest @types/jest jest-junit jest-preset-angular ts-jest --save-dev

> Remove test object from angular.json

> Update scripts in package.json as below

"scripts": {

    "ng": "ng",
    "start": "ng serve",
    "build": "ng build",
    "watch": "ng build --watch --configuration development",
    "test": "jest -c ./jest.config.js ./src",
    "test:watch": "jest -c ./jest.config.js ./src --watch",
    "test:coverage": "jest -c ./jest.config.js ./src --coverage"

}

> Delete karma.conf.js

> Create and update jest.config.js at root level of project

> Delete test.ts

> Create and update setupJest.ts in src folder

> Update tsconfig.json and tsconfig.spec.json

> npm run test