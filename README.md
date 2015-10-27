# random-quote-generator

##About
This is a webpage that pulls semi-random quotes from quotedb.com.
It was created to satisfy the requirements of the second Free Code Camp Zipline.

##Latest Live Version
http://codyschindler.com/fcc/quotes

##Working principles
The given http://quotedb.com script returns a couple `document.write()` js lines. This is problematic for page reloads so I have it run on rq.html. Then I load rq.html in a hidden iframe on index.html and pull the `contents()` of it into another `div`. The iframe can be reloaded with a button, and the text in the `div` is reloaded. 

##Deprecation
The files randomquote.html and randomquote-js.js are deprecated, but I keep them in the working directory so that a codepen I made a while back continues to work.

##Thanks
Thanks to http://quotedb.com for having a simple free API. You guys rock!
