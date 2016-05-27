# Asset Optimization & Performance

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

## Challenge introduction

Performance is the first aspect of your design that users will encounter. A slow-loading site will lose 75% of it’s potential viewership on mobile devices if it doesn’t show up in less than 5 seconds (and that’s generous; the number goes down steadily as network speed increases). By making performance a primary consideration in your design process, you can increase the likelihood of a successful outcome and help guide the design conversation with the client to achieve a good balance of aesthetics and usability. Loading speed, asset size and ways in which you can optimize the rendering of the design on screen are all critical aspects of design, not just development.

## Background research

* [How to make a performance budget](http://danielmall.com/articles/how-to-make-a-performance-budget/) by Dan Mall

* [Performance as Design](http://bradfrost.com/blog/post/performance-as-design/) by Brad Frost

* [Image Performance](http://radar.oreilly.com/2014/01/image-performance.html) by Lara Swanson

* [Loading Web Fonts with the Web Font Loader](https://css-tricks.com/loading-web-fonts-with-the-web-font-loader/) by Robin Rendle

* [Improving UX Through Front-End Performance](http://alistapart.com/article/improving-ux-through-front-end-performance) by Lara Hogan

* [Remove Render Blocking Javascript](https://developers.google.com/speed/docs/insights/BlockingJS) by Google Developers Team

* Bonus reading: great overview of time, perception & behavior on the web

    * [Why Performance Matters, Part 1](http://www.smashingmagazine.com/2015/09/why-performance-matters-the-perception-of-time/) by Denys Mishunov

    * [Why Performance Matters, Part 2](http://www.smashingmagazine.com/2015/11/why-performance-matters-part-2-perception-management/) by Denys Mishunov

## Challenge outline

While there is a lot more to learn about performance as a design consideration and how to improve it, this challenge focuses on 3 aspects in particular that can help inform your design thinking and open your eyes to how the choices made in the design process can ripple through to when (or if!) your design will show up on a user’s screen.

* Review sample page & performance information:

    * What is being loaded?

    * When is each asset being loaded? In what order?

    * Is what you are loading optimized?

* Images are important: they are often a critical design element, but often overlooked as a place to find quick performance gains, and in need of deeper consideration when thinking about how designs must transform based upon the screen size on which they are viewed.

    * Use one of the tools you’ve learned about to optimize the images on the sample page

    * Try using the <picture> element and included sample crops of each image to ensure that the appropriate image is served to various devices

* Web fonts: they are simultaneously one of the most important and troublesome design elements on the page, so it’s critical that you use only what you need, and take care to not impede the page loading/drawing process.

    * Are you using all of the fonts being loaded?

    * Are they being loaded first or can they load in the background?

* JavaScript is one of the culprits in blocking the rendering of pages. Where the links to load JS files and how they are called can greatly impact how quickly content shows up on the screen.

    * Are you putting JS calls in the right place?

    * Are you minimizing what gets downloaded?

    * Have you tried adding ‘async’ to the JS links? (tip: it’s not always possible, but anything that loads external resources like web fonts can likely benefit from this)

## Recommended process

1. Copy the sample code directory and view the ‘index.html’ page in your browser. (download here: [https://github.com/freshtilledsoil/AUX-Challenge-UX-Performance](https://github.com/freshtilledsoil/AUX-Challenge-UX-Performance))

2. Using the Developer Tools in Chrome, set ‘Network Throttling’ to ‘Regular 3G’ to simulate a slower loading experience. Take notes on the number of requests, amount of data loaded and loading times.

3. Explore optimizing the images supplied, rerunning the tests to gauge improvement.

4. Optimize the Google Web Fonts being loaded (for the number of fonts and how they are loaded).

5. Update the JavaScript being loaded (where on the page, and how).

6. Retest the page and note the results.

## Deliverables

Upon successfully completing the challenge, you should have a new set of files with updated HTML, optimized images, CSS, and JS files, and notes on the overall performance benchmark improvements.

## Timeline

You’ll have just under two weeks to complete your work. The challenge starts on a Monday and is due for evaluation by Trish Dallmeyer, Scott O’Hara or Steve Hickey the following Thursday. We highly recommend checking in several times with members of the design team along the way. There will not be any project extensions, you are responsible for delivering on time. Part of delivering on time is making sure you’re on the correct path at several intervals along the way.

Your brief talk will be due for presentation the day after the challenge is due.

