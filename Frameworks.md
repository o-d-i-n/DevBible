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
  
### [Django](https://www.djangoproject.com/)

Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel. It’s free and open source.

#### Some features of Django
  * ##### Ridiculously fast.
  
    Django was designed to help developers take applications from concept to completion as quickly as possible.
  * ##### Reassuringly secure.
  
    Django takes security seriously and helps developers avoid many common security mistakes.
  * ##### Exceedingly scalable.
  
    Some of the busiest sites on the Web leverage Django’s ability to quickly and flexibly scale.
    
#### Tutorials and References
  * http://www.tangowithdjango.com/
  * https://docs.djangoproject.com/en/1.10/intro/tutorial01/
  * https://tutorial.djangogirls.org/en/
  * http://www.tutorialspoint.com/django/
  * https://realpython.com/learn/start-django/
  * http://gregblogs.com/how-django-reactjs-and-browserify/

#### Free Books
  * http://djangobook.com/
  * http://masteringdjango.com/
  * http://chimera.labs.oreilly.com/books/1234000000754/index.html
  * https://media.readthedocs.org/pdf/django/1.9.x/django.pdf
  * http://gsl.mit.edu/media/programs/south-africa-summer-2015/materials/djangobook.pdf
  * https://media.readthedocs.org/pdf/django/1.10.x/django.pdf
