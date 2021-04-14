# native client app & web app

## the difference  between  native client application and web application

 native contain ersistent local storage 

the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files,

about web application

in early invent the cookies to web app 

 can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
 
 1-slowing down your application because cookies included to each HTTP  request .

 2- sending data unencrypted over the internet (unless your entire web application is served over SSL).

 3-Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.

 userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. 

 ### In 2002, Adobe introduced  Local Shared Objects. 

  Local Shared Objects: Local Shared Objects.

  ### In 2007, Google launched Gears,

  an open source browser plugin aimed at providing additional capabilities in browsers

  ## So what is HTML5 Storage? 

   way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site,
