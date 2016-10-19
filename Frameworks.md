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

Django is a full featured web applications framework for Python that allows for rapid development. It achieves
this by including a vast number of features that prevent developers from reinventing the wheel. This helps enforce a
don't repeat yourself (DRY) principle where components can be reused and pluggable, which allow developers
the option to share components and enhance their apps functionality. Arguably, Django is the most
popular web framework for Python and is adopted by many well-known sites such as Pintrest, Mozilla and Disqus.

At its core Django follows a Model View Template (MVT) pattern. The model provides the way the data is structured within
the database. Represented as a Python class, the model is the single definitive source of information about the data and handles
the creation of the database table. In order to interface with the database, Django provides an object relational mapper (ORM).
This allows database queries to be constructed by interfacing with a Python object rather than communicating directly with
the database by constructing SQL queries.

The view handles all the logic required to process requests and return the proper response. This includes the ability to
define URL endpoints, handle file uploads and serialize the data returned in the response. In general, data is
retrieved by constructing a ORM query through a model object. The result is passed to the response in the form of a
context. Typically, the code will load a template which uses the context as a dictionary that maps template variable
names to Python objects.

The template defines the overall presentation of the data. This defines how the front end will look when a user receives
the response from the view. Templates are powerful, because they reduce the need to repeat code on the front end.
Templates have their own syntax that introduces logic and variables within the typical HTML markup. This makes it possible
to access the content of the context. For instance, one can loop through all the data of a query while applying the
correct styling. Lastly, templates can import from a base template, which allow common elements, such as a navbar, to be
written once and plugged where needed.

Django also includes more advance features such as an administrative interface, user authentication and a caching
framework. Additionally, Django's features can be extended further through third party apps. Some popular choices
include the Django Rest Framework (DRF), Channels, Elasticsearch and Celery.


#### Tutorials and References
  * http://www.tangowithdjango.com
  * https://tutorial.djangogirls.org
  * https://docs.djangoproject.com/en/1.10/intro/tutorial01

#### Essential Packages
  * http://www.django-rest-framework.org
  * https://github.com/django/channels
  * https://django-endless-pagination.readthedocs.io/en/latest
  * http://docs.celeryproject.org/en/latest/django/first-steps-with-django.html
  * https://github.com/liberation/django-elasticsearch

### [Express](https://www.expressjs.com/)

Express is a minimalist web applications framework for Node. It is a great solution for single page applications, web sites, hybrids, or
public HTTP APIs. It is the most popular web framework for Node and is used by companies like Uber, Paypal and Paytm.
It achieves this by including a vast number of features that prevent developers from reinventing the wheel. This helps
enforce a don't repeat yourself (DRY) principle where components can be reused and pluggable, which allow developers
the option to share components and enhance their apps functionality.

At its core Django follows a Model View Template (MVT) pattern. The model provides the way the data is structured within
the database. Represented as a Python class, the model is the single definitive source of information about the data and handles
the creation of the database table. In order to interface with the database, Django provides an object relational mapper (ORM).
This allows database queries to be constructed by interfacing with a Python object rather than communicating directly with
the database by constructing SQL queries.

The view handles all the logic required to process requests and return the proper response. This includes the ability to
define URL endpoints, handle file uploads and serialize the data returned in the response. In general, data is
retrieved by constructing a ORM query through a model object. The result is passed to the response in the form of a
context. Typically, the code will load a template which uses the context as a dictionary that maps template variable
names to Python objects.

The template defines the overall presentation of the data. This defines how the front end will look when a user receives
the response from the view. Templates are powerful, because they reduce the need to repeat code on the front end.
Templates have their own syntax that introduces logic and variables within the typical HTML markup. This makes it possible
to access the content of the context. For instance, one can loop through all the data of a query while applying the
correct styling. Lastly, templates can import from a base template, which allow common elements, such as a navbar, to be
written once and plugged where needed.

Django also includes more advance features such as an administrative interface, user authentication and a caching
framework. Additionally, Django's features can be extended further through third party apps. Some popular choices
include the Django Rest Framework (DRF), Channels, Elasticsearch and Celery.


#### Tutorials and References
  * http://www.tangowithdjango.com
  * https://tutorial.djangogirls.org
  * https://docs.djangoproject.com/en/1.10/intro/tutorial01

#### Essential Packages
  * http://www.django-rest-framework.org
  * https://github.com/django/channels
  * https://django-endless-pagination.readthedocs.io/en/latest
  * http://docs.celeryproject.org/en/latest/django/first-steps-with-django.html
  * https://github.com/liberation/django-elasticsearch
