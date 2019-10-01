# UTSC-DSC Website Template

First of all this is a React App with bootstrapping. You will need to run `npm i` to install the necessary packages.

## .ENV file
This file will have the major variables that you can change that will be reflected on the website such as logo images, the Google Calendar embed url, the Mailchimp signup action url and Firebase Credentials. Please change this file's values as needed so the website will work as intended.

# **CRUCIAL DEPENDENCIES**

## Firebase Events
It is required that you set up a Firebase project and edit the `.env` file as the Events Carousel module grabs events that are in the Firebase database.
Events in firebase must comply with the following fields:

### Name
varType= string, [name of the event]
### Date
varType= timestamp
### Description
varType= string, [description of the event, try to keep it within 2-3 sentences]
### Fees
varType= string, [fees if any]
### Image
varType= string, [this is an image associated to the event (url to the pic)]
### Link
varType= string, [this is the link to the event signup if it is required]
### Signup
varType= string, [Leave this blank if you have provided a signup link above]
### Location
varType= string, [location of the event, keep it brief]


## Mailchimp Newsletter
We use Mailchimp as our newsletter provider, and so our embedded signup module requires the Mailchimp Action URL to work. Please change the URL in the `.env` accordingly.


## Google Embeds
Google calendar and maps on our website are embeds, so you will need to grab your own relevant URLS that pertain to your calendar and map location and paste them into the `.env` file provided.


## Pictures/images
Place them in the `/public/` folder.

## How to start
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

## Thank You
Again we at UTSC-DSC hope that this template will help serve as a starting point in for your own DSC website and Thanks You for choosing our template!
