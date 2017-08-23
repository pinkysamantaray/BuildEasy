# BuildEasy
One tool for End to End web/mobile app Development, Deployment and Testing

# Angular
- `npm install`
- `npm start`
- `npm test`


# Angular2
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.3.0.
### Prerequisites
- install angular-cli
 `npm install -g @angular/cli`
### Development server
Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
### Build
Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.
### Running unit tests
Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
### Running end-to-end tests
Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.


# Angular-fullstack
This project was generated with the [Angular Full-Stack Generator](https://github.com/DaftMonk/generator-angular-fullstack) version 4.2.2.
### Prerequisites
- [Node.js and npm](nodejs.org) Node >= 4.x.x, npm >= 2.x.x
- [Gulp](http://gulpjs.com/) (`npm install --global gulp`)
- [MongoDB](https://www.mongodb.org/) - Keep a running daemon with `mongod`
### Developing
1. Run `npm install` to install server dependencies.
2. Run `mongod` in a separate shell to keep an instance of the MongoDB Daemon running
3. Run `gulp serve` to start the development server. It should automatically open the client in your browser when ready.
### Build & development
Run `gulp build` for building and `gulp serve` for preview.
### Testing
Running `npm test` will run the unit tests with karma.
### Deployment
Follow: (https://angular-fullstack.github.io/deployment/)
#### Manual (Linux server)
- Run gulp build. This will build your project into the dist folder by default.
- Zip up the contents of your dist folder and send it off to your server.
- On your server, unzip your built files somewhere on the disk. Ex: in a myproj folder.
    `$ cd myproj`
    `$ SET NODE_ENV=production`
    `$ node ./server`
    

# React
### Prerequisites
- [Node.js and npm](nodejs.org) Node >=6.5, npm >=3.10
- [Yarn](https://yarnpkg.com/en/docs/install) 
### Developing
1. Run `yarn install`
2. Run `yarn start`
### Build, Test, Deploy
If you need just to build the app (without running a dev server), simply run:
 `$ yarn run build`
or, for a production build:
 `$ yarn run build -- --release`
or, for a production docker build:
 `$ yarn run build -- --release --docker`
NOTE: double dashes are required
After running this command, the /build folder will contain the compiled version of the app. For example, you can launch Node.js server normally by running node build/server.js.

To launch unit tests:
 `$ yarn run test`         # Run unit tests with Mocha
 `$ yarn run test:watch`    # Launch unit test runner and start watching for changes
By default, Mocha test runner is looking for test files matching the src/**/*.test.js pattern. Take a look at src/components/Layout/Layout.test.js as an example.

To deploy the app, run:
 `$ yarn run deploy`
The deployment script tools/deploy.js is configured to push the contents of the /build folder to a remote server via Git. You can easily deploy your app to Azure Web Apps, or Heroku this way. Both will execute yarn install --production upon receiving new files from you. Note, you should only deploy the contents of the /build folder to a remote server.




