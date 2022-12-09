# Food-Fest

Find a food festival near you.

### **User Stories**

- As a user, I want the application to load quickly
  Add offline functionality

### **User Stories**

- As a user, I want to use the Food Festival application even if I don't have an internet connection
  Allow users to download the application as if it were a phone app

### **User Stories**

- As a user, I want to download the app to the home screen on my mobile device

DOWNLOAD STARTER CODE

By navigating around the homepage in our browser, we can discover the following basic behaviors:

The homepage has a carousel that contains different images and information on each slide.

The tickets page has a modal that pops up when the user selects “Purchase Tickets.”

The tickets page modal captures user information and should send an email to complete the purchase.

The schedule page displays data from various events.

When an event is clicked, something must happen to route the user to the event’s page.

The event data must be stored in localStorage in order to be accessed on both the events page and the individual event page.

The project doesn't include a server, but it does include static assets.

In this lesson, we've added the following to our knowledge base:

How to use a manifest.json in our projects, and how that will work along with a service worker to make our app a PWA.

How to link a manifest to the HTML to let the browser know the app is a PWA.

How to use webpack to dynamically create a manifest.json based on configurations provided in webpack.config.js.

How to add properties to the manifest.json so the user can add the PWA to the home screen of their mobile device.

Now let's look at some of the big takeaways from this module:

Measured performance metrics for a website using Chrome DevTool's Lighthouse app.

Performed audits to expose performance flaws which are especially critical when dealing with slower mobile devices on sluggish networks.

Learned how to use an automated build tool like webpack to bundle assets through a dependency graph to optimize performance by lazy loading and minification.

Used service workers to cache the websites assets for offline functionality.

Offered installable icons for quick access to our app using PWAs.

This module should serve as a nice transition into the next unit, React. We will use webpack with React to build and modularize our application. webpack will be key in creating our dependency graph that will keep our modules in React linked to their dependencies.
