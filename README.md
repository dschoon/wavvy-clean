# Wavvy

Wavvy is a full stack software project that allows users to host podcasts. Software allows users to manage their podcasts and episodes, create an RSS feed for itunes/spotify, and create a personalized website to share social media links. Software is in dark mode by default.

<span style="display:block" class="note">
  <img src="https://voiceblasts1.s3.amazonaws.com/Screen+Shot+2021-02-14+at+10.55.07+AM.png">
</span>

<img width="812" alt="Screen Shot 2022-03-15 at 8 16 20 PM" src="https://user-images.githubusercontent.com/38474161/158503551-c6ea7fd3-2342-4556-8305-fc33ebda8748.png">


## Tech/framework used

Frontend tech stack:

- React JS
- CSS
- Redux
- React Router
- [React Icons](https://react-icons.github.io/react-icons/)
- [React Toast Notifications](https://jossmac.github.io/react-toast-notifications/)

Backend tech stack:

- Node
- Express
- PostgresSQL
- Nodemailer
- AWS SDK

Frontend of the app is in the client folder. Under src directory store folder contains all of the redux actions and reducers. The website folder is responsible for building the landing page.

Edit index.js to change the server connection. Middleware, routes, and utils directories contain server code for API endpoints.

Hosted on Heroku: Folder structure is set up specifically to be compatible with Heroku

Production site is deployed to [wavvy.us](https://www.wavvy.us/) 

Here is a quick [Loom demo](https://www.loom.com/share/b46061898fc54d15870cd734b96886a6) 

## Installation

To run this project, install it locally using npm:

```
$ cd client
$ npm install
$ npm start
```

to run the Node JS server:

```
$ node index.js
```

In the root directory create a .env file with the values from env.txt

## Contribute

Feel free to use code however you would like.

If you have any questions feel free to email me at toshvelaga@gmail.com

## License

MIT © Tosh Velaga
