# Salinaka | E-commerce react app
[Live demo](https://salinaka-ecommerce.web.app/)
## Run Locally
### 1. Install Dependencies
```sh
$ yarn install
```

### 2. Create a new firebase project
Login to your google account and create a new firebase project [here](https://console.firebase.google.com/u/0/)

Create an `.env` file and add the following variables.

```
// SAMPLE CONFIG .env, you should put the actual config details found on your project settings

VITE_FIREBASE_API_KEY=AIzaKJgkjhSdfSgkjhdkKJdkjowf
VITE_FIREBASE_AUTH_DOMAIN=yourauthdomin.firebaseapp.com
VITE_FIREBASE_DB_URL=https://yourdburl.firebaseio.com
VITE_FIREBASE_PROJECT_ID=yourproject-id
VITE_FIREBASE_STORAGE_BUCKET=yourstoragebucket.appspot.com
VITE_FIREBASE_MSG_SENDER_ID=43597918523958
VITE_FIREBASE_APP_ID=234598789798798fg3-034

``` 

After setting up necessary configuration,
create a **Database** and choose **Cloud Firestore** and start in test mode

### 3. Run development server
```sh 
$ yarn dev
```

---

## Build the project
```sh
$ yarn build
```

## How to add products or perform CRUD operations for Admin
1. Navigate to your site to `/signup`
2. Create an account for yourself
3. Go to your firestore collection `users collection` and edit the account you've just created. Change the role from `USER` to `ADMIN`.
4. Reload or sigin again to see the changes. 

**Firebase Admin to be integrated soon**

## Features

* Admin CRUD operations
* Firebase authentication
* Firebase auth provider authentication
* Account creation and edit

