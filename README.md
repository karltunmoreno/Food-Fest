# Food-Fest

Find a food festival near you. Progresive Web Application.

_____________________________________________________________________________________________________________________________________________________________



![Ss](https://karltunmoreno.github.io/My-Portfolio/assets/images/foddfest1.jpg)

_____________________________________________________________________________________________________________________________________________________________

- As a user, I want the application to load quickly
  Added offline functionality

- As a user, I want to use the Food Festival application even if I don't have an internet connection
  Allows users to download the application as if it were a phone app

- As a user, I want to download the app to the home screen on my mobile device
_____________________________________________________________________________________________________________________________________________________________


##Tech Used:

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?logo=html5&logoColor=white&style=for-the-badge)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?logo=css3&logoColor=white&style=for-the-badge)
![JavaScript](https://img.shields.io/badge/-JavaScript-%23F7DF1C?style=flat-square&logo=javascript&logoColor=000000&color=d1b01f)
 ![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?logo=bootstrap&logoColor=white&style=for-the-badge)
 ![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=ffffff)
 
 _____________________________________________________________________________________________________________________________________________________________

1. DOWNLOAD CLIENT STARTER CODE

By navigating around the homepage in our browser, we can discover the following basic behaviors:

The homepage has a carousel that contains different images and information on each slide.

The tickets page has a modal that pops up when the user selects “Purchase Tickets.”

The tickets page modal captures user information and should send an email to complete the purchase.

The schedule page displays data from various events.

When an event is clicked, something must happen to route the user to the event’s page.

The event data must be stored in localStorage in order to be accessed on both the events page and the individual event page.

The project doesn't include a server, but it does include static assets.


Used a manifest.json in our projects, and how that will work along with a service worker to make our app a PWA.

Linked a manifest to the HTML to let the browser know the app is a PWA.

Usde webpack to dynamically create a manifest.json based on configurations provided in webpack.config.js.

Added properties to the manifest.json so the user can add the PWA to the home screen of their mobile device.

Measured performance metrics for a website using Chrome DevTool's Lighthouse app.

Performed audits to expose performance flaws which are especially critical when dealing with slower mobile devices on sluggish networks.

Learned how to use an automated build tool like webpack to bundle assets through a dependency graph to optimize performance by lazy loading and minification.

Used service workers to cache the websites assets for offline functionality.

Offered installable icons for quick access to our app using PWAs.


