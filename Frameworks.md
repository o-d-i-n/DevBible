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

## [React](https://facebook.github.io/react)

React isn't really a framework, it's a library, however it isn't used as is in practical world. 

React technically is a library for "View" part of your MVC, i.e. its responsibility is to create interactive views based on your data.
You can say View is a function of data and events. React is the function that implements it.

  ```
View = React(data, events)
  ```

  It allows you to create composable Components that can talk to each other, and can maintain state of their own. Based on several functional programming concepts, React has created an ecosystem which is redefining the way we look at UI. Same approach is extended to desktop and mobile applications today ([React Native](https://facebook.github.io/react-native))


### Tools

  React and ES2015+ is infamous for requiring a lot of tools. However,
  we recommend using online bins like [webpackbin](http://webpackbin.com) or [esnextbin](http://esnextb.in) for
  writing code directly without setting up tools like Webpack, Babel etc.

### Videos

  * [Intro Video](https://egghead.io/lessons/react-core-concepts-of-react-components-props-and-state) - Quick video to get basic idea

  * [Intro Series](https://www.youtube.com/watch?v=walnw4n8vSY&list=PLs0HJRuXPAqtG4P-YBUPYWpH1M6j5J60-) - Quick video series to understand basic idea *deeply*.

  * [Crash Course](https://www.youtube.com/watch?v=DfRibIkjhew) - Covers hell lot: Webpack/Babel/React/Router/Redux/React-Redux

  * [React Router](https://egghead.io/series/getting-started-with-react-router) - A nice brief playlist to get you started with React-Router

  * [React + Redux](https://www.youtube.com/playlist?list=PLQDnxXqV213JJFtDaG0aE9vqvp6Wm7nBg) - Watch this one for practical usage of redux, skip react part as by now you would be cool with it

  * [Redux](https://egghead.io/series/getting-started-with-redux) - For deep understanding of Redux from the author himself.

