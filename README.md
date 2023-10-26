# Google Login Using Passport

## Installation

```bash
$ npm install
```

## Running the app

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## How to Test

- Goto http://localhost:3000/auth/google
- It will redirect to google login page
- Select any google account to login
- It will redirect to http://localhost:3000/auth/profile
- Due to the guard `CheckTokenExpiryGuard` it will validate the token and return user details
- Goto http://localhost:3000/auth/logout to logout from the app and revoke the google refresh token
