# JavaScript &#10084;
A famous man once said JavaScript is the Language made for the Gods.
Okay we said  it and we am neither famous nor very smart, but going by the stats JavaScript is *the* most famous language in the world right now. If you don't believe us, we've got proof [here](http://www.eweek.com/developer/javascript-most-popular-language-stack-overflow-report.html) and [here](http://www.modulecounts.com/)
So they must be doing something right.

So getting right down to the facts. Some of the things we find really useful about JavaScript:

**1. It's made for the web**

More like the web is made of JavaScript.
**Literally**.Almost every website you come across has JavaScript in some way or form. In the early days when the Java guys were trying to get their own version of the web started (*applets*,ahem ahem).

A relatively unknown language called EcmaScript was born. It had it's quirks and bugs for sure. Poor design decisions? Absolutely .But it took a hold of the programmers like no other.
The brilliant thing about JavaScript was it was designed from the ground up with the internet in mind ,which sadly Java did not as they tried to shoehorn this extra 'web functionality' into their admittedly admirable language (We like all things Java, as you might have guessed)

**2. It's evolving like crazy**

JavaScript is changing at a rapid pace, what was cool six months ago has been replaced by a leaner and meaner counterpart. *Gulp* replaces *Grunt*.*Promises* replaces *Callbacks*.*Async Await* replaces *Promises* and so on and so forth.

This is what gives Js an edge over it's counterparts. The team behind it is dedicated and focused and this has led to the developers to take up arms and join the fight at bettering JavaScript.
The amazing community behind it is one of the reasons behind it's success.

**3. Async FTW**

For those who don't know, Async or *asynchronous* support is the ability for a client to request something and go on with it's other duties ,meanwhile leaving a guard or a watch keeper in place to constantly look whether the request has received a response. Upon receiving the response the program can respond accordingly.

But the important thing here is that the program doesn't have to **wait** for the response.
It can do other important things and deal with the outcome when it is ready to grace us with it's presence.

This has unbelievable advantages(and disadvantages,*callback hell is a terrible place to be in ,more on that later*)

* The primary advantage is increased responsiveness and  increased perceived performance, which is very important for a web developer. An example of this would be **commenting on a YouTube video**. If not for asynchronous function, the act of commenting would freeze everything for a second. JavaScript's event loop and async nature helps get better perceived performance and logical concurrency.

Click [here](https://www.youtube.com/watch?v=ztspvPYybIY) if you want to see the Ryan Dahl talking about this stuff in greater detail in the introduction of NodeJS .


* The second advantage can be engaging in long lasting database interactions(background tasks)

Async support is uncommmon in a lot of languages (though it is picking up steam),JavaScript is pretty ahead of the game on this front.

The complicated nature of callbacks were fixed by the new standards of Promises and Async Await which made the code more synchronous as far as readibility goes and put up checks so that our code doesn't do weird async things while still retaining its asynchronous nature. Here are links on Promises and Async Await [here](https://www.toptal.com/javascript/javascript-promises) and [here](https://www.twilio.com/blog/2015/10/asyncawait-the-hero-javascript-deserved.html) respectively.

**4. Server Side A.K.A Node.js**

In the early days JavaScript was really limited, which means it was only useful on the client side. The recent phenomenon of node.js has changed this scenario rapidly. Node.js can frankly add a backend to your frontend using only JavaScript, Another way of looking at it is ,it can create a server.
No PHP, No Python needed.

This has led to applications being created only in one language. So we can interact with the database, handle client requests all using Javascript.
This type of JavaScript being used everywhere is called Universal JavaScript or Isomorphic JavaScript. Here is a [link](https://medium.com/@mjackson/universal-javascript-4761051b7ae9#.jyg0exgy5) of a beautiful article on the same.

**5. Animations fast and fluid (Client Side Interaction)**

This language was always a client side affair first. It's adoption has led to support for all the beautiful animations ,parallax effects and overall responsiveness.
Libraries like JQuery provide great looking effects in a very easy to learn package.
Some quick features are:

* Manipulate the DOM like a boss
* Send Https requests
* Animations


**6. It pays to learn JavaScript**

Companies are looking for good JavaScript devs. It is a useful skill and if learnt properly can give you a career. JavaScript devs are plentiful but good JavaScript devs are rare and companies shell out a fair penny for people who know their way around the workings of this mysterious langague.

**7. Dynamic Browser Side Rendering**

Frameworks such as Angular, React and Meteor are changing the way client side coding is done. The Model View Container(MVC) principle has been taken to heart and now it is possible to *bind* an element such that change can be reflected instantaneously(Think the way a Facebook like changes when clicked upon).


New and better ways of rendering html elements have resulted in cleaner and faster code. Now it is possible to render an entirely new html page in a div.
This has given rise to a new breed of websites know as Single Page Applications, **S.P.A**. HackerRank is a prime example. The URL changes but the site never really reloads.

Technologies like React Native, Cordova/Ionic provide JS tech stack for Mobile App Development. React Native actually allows you to build native applications using principles of ReactJS for both iOS and Android. This not only increases code-reuse but also allows a JS Dev to use their favourite modules over NPM.

 Companies like Google and Facebook are at the forefront of these technologies and you know that those guys know their stuff.


 We hope this post convinces you to learn JavaScript. It really is a great language and totally worth your time.

## The bad things about JavaScript
#### Coming soon..
