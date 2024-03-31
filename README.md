﻿# Getting Started with the Rewrapped Backend

Clone the code with your personal access token and run the following commands to get started.

## Available Scripts

In the project directory, you can run:

### `yarn`

To install all the relevant packages with the correct versions.

### .env

In order to properly setup the backend repo to work correctly with the frontend repo please the following information in the .env file within the ReWrapped-BE source directory

```
DATABASE_URL='postgres_url'
JWT_SECRET_KEY='Your_JWT_Secret_KEY'
DATABASE_PORT=PORT_NUMBER
REACT_APP_CLIENT=CLIENT_SIDE_URL
EMAIL_SERVICE='Your_email_service'
EMAIL_ID='youremail@email.com'
EMAIL_PASSWORD='your_email_password_for_the_app'
```

### `yarn start`

Runs the app in development mode.

### `yarn test`

Launches the test runner in the interactive watch mode.
