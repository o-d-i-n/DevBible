# Frameworks
While writing everything from scratch is amazing, practical development work involves quick learning of Frameworks and their best practices to reduce development time and re-use highly maintained code as a dependency to your project.

We can't possibly teach every framework, hence we first propose an approach for learning frameworks followed by nice resources for the same.

## Approach

* We believe that in today's world learning any framework requires hands-on experience and good quality tutorials. Books make sense for sure, but who has time for them ?
* Follow API docs of the Framework, it should suffice in most cases.
* Websites like YouTube, [egghead](http://egghead.io) etc are great for learning new things.
* Once you have basic idea, create something, something that involves most of the concepts. For UI related APIs create a TodoList App for example.
* Do have a look at [awesome](https://github.com/sindresorhus/awesome) repo of the same on Github. For example [awesome-swift](https://github.com/matteocrippa/awesome-swift) has some nice sources for learning Swift.

Now we look at popular libraries and frameworks.

### [React](https://facebook.github.io/react)

React isn't really a framework, it's a library, however it isn't used as is in practical world.

React technically is a library for "View" part of your MVC, i.e. its responsibility is to create interactive views based on your data.
You can say View is a function of data and events. React is the function that implements it.

  ```
View = React(data, events)
  ```

  It allows you to create composable Components that can talk to each other, and can maintain state of their own. Based on several functional programming concepts, React has created an ecosystem which is redefining the way we look at UI. Same approach is extended to desktop and mobile applications today ([React Native](https://facebook.github.io/react-native))


#### Tools

  React and ES2015+ is infamous for requiring a lot of tools. However,
  we recommend using online bins like [webpackbin](http://webpackbin.com) or [esnextbin](http://esnextb.in) for
  writing code directly without setting up tools like Webpack, Babel etc.

#### Videos

  * [Intro Video](https://egghead.io/lessons/react-core-concepts-of-react-components-props-and-state) - Quick video to get basic idea

  * [Intro Series](https://www.youtube.com/watch?v=walnw4n8vSY&list=PLs0HJRuXPAqtG4P-YBUPYWpH1M6j5J60-) - Quick video series to understand basic idea *deeply*.

  * [Crash Course](https://www.youtube.com/watch?v=DfRibIkjhew) - Covers hell lot: Webpack/Babel/React/Router/Redux/React-Redux

  * [React Router](https://egghead.io/series/getting-started-with-react-router) - A nice brief playlist to get you started with React-Router

  * [React + Redux](https://www.youtube.com/playlist?list=PLQDnxXqV213JJFtDaG0aE9vqvp6Wm7nBg) - Watch this one for practical usage of redux, skip react part as by now you would be cool with it

  * [Redux](https://egghead.io/series/getting-started-with-redux) - For deep understanding of Redux from the author himself.

### [Meteor](https://github.com/meteor/meteor)

Meteor is a Node-based full-stack framework which allows to create reactive webapps, that could easily be ported to Android and iOS platforms.
Reactive webapp implies real-time behaviour: There is a continuous connection between the client and server side, and so, a change made in application by any means(direct entry in database, from server, or even by a client) is reflected on every instance of the application without any page reload.

Meteor is based on Websockets(sockJs). In Meteor, the client talks to server over DDP(Distributed Data Protocol), which is like "REST" for websockets. For websockets.

Meteor has its own package manager(Atmosphere) that seperates it from the rest of Node universe. However, NPM packages could be easily wrapped as a Meteor package.

It allows to create simple apps really fast since, most of the configuration comes packed. This makes it ideal for hackathons :P
It doesnot follow any strict development model (like MVC) and the files can be placed as we would like.

Meteor by default uses Blaze templating system that resembles Handlebars, and is really simple to build upon. It now supports Angular and React templating systems as well.

#### Tutorials and References
  * https://www.meteor.com/tutorials/blaze/creating-an-app
  * https://github.com/ericdouglas/Meteor-Learning

#### Essential Packages
  * https://github.com/aldeed/meteor-collection2
  * https://github.com/iron-meteor/iron-router
  * https://github.com/meteorhacks/npm
  * https://github.com/alanning/meteor-roles
  * https://github.com/arunoda/meteor-up/tree/mupx
  
### [Bootstrap](http://getbootstrap.com)

Bootstrap is an open-source Javascript framework developed by the team at Twitter. It is a combination of HTML, CSS, and Javascript code designed to help build user interface components. Bootstrap was also programmed to support both HTML5 and CSS3.

Also it is called Front-end-framework.

Bootstrap is a free collection of tools for creating a websites and web applications.

It contains HTML and CSS-based design templates for typography, forms, buttons, navigation and other interface components, as well as optional JavaScript extensions.

#### Some Reasons for programmers preferred Bootstrap Framework
  1. Easy to get started
  2. Great grid system
  3. Base styling for most HTML elements(Typography,Code,Tables,Forms,Buttons,Images,Icons)
  4. Extensive list of components
  5. Bundled Javascript plugins
  
#### References
  * http://getbootstrap.com/
  * http://www.w3schools.com/bootstrap/
  * https://github.com/twbs/bootstrap
  * http://www.tutorialspoint.com/bootstrap/
  * http://www.tutorialrepublic.com/twitter-bootstrap-tutorial/
  
#### Free books
  * https://www.tutorialspoint.com/bootstrap/bootstrap_tutorial.pdf
  * https://www.syncfusion.com/resources/techportal/ebooks/twitterbootstrap3
