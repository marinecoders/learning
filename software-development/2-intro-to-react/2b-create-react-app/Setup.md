## Create React App Setup

### Instructions

#### 1. CMD Line (Windows) or Terminal (macOS)

1. Working directory: **/users/\${username}/Documents/GitHub**
2. Type **npx create-react-app react-app-example**
3. Watch as the Create React App is downloaded and installed to your repository directory
4. Once the app is complete you should receive a message in your terminal
   stating **Happy Hacking**. At this point you know the application is installed properly.
5. Type **cd ./react-app-example** (navigating into your application directory)

#### 2. START your application

1. Type **npm start**
2. Observe that the application auto starts the browser with your react app
   at http://localhost:3000. Congratulations! You just created your first web
   application using ReactJS.

#### 3. STOP your application

1. Press (Windows) Ctrl+c (macOS) Cmd+c to stop the ReactJS application runtime.

#### 4. RUN a application test

1. Type **npm run test**

#### 5. BUILD a production deployment of your application

In order to deploy your application you will need to run the following command.

1. Type **npm run build**

Often the deployment pipeline you choose will do this for you. Only when testing
locally, manually uploading or auto deploying directly to a static file
storage (e.g. AWS S3) location would you run the above command. Worth trying to
see how a ReactJS application is converted from JSX into a deployment bundle.
