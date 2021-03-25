# yfi 

### Details

This was the original www.yourfinancialintel.com where I learned Nodejs but modifying an Angular
project that grabbed tweets from the twitter api. This started back in about 2016, at the 
time I knew very little about the current Distributed Systems technology and had many problems.
One significant problem was that it used a npm library called masonry. This library 
gave the tools to layout the dynamically retrieved tweets in a perfect layout, box after box
the same width apart. This was all well and good, except that one day while I was still 
adding and modifying the project, the library owner made a breaking change and I could
never get it to work again. There's a lot I didn't know at the time, like how I could 
have made sure to use only that version of the library. But over time, I then found
another library to grab news from New York Times, which this as well didn't work at some 
point in this process. So currently, this only shows tweets. And when I learned grid and
flex box this last year I realized that power could help me place these tweets in a nice
layout like masonry did many years ago. It works to a certain degree, but it's not perfect
without a more significant refactor because they are dynamic and I think it needs to be
rendered with the data not as it is now where the browser renders and then the tweets come
in as they are retrieved. 

The hopefully last of my problems was a few days ago when I realized the push to yfi was
no longer triggering the deploy to AWS Elastic Beanstalk because I believe something
to do with now using the Linux 2 environment..  this I'm in the process of working out 
for sure.
