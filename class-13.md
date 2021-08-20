## Read 13: Local Storage:
[Go back to Reading Notes home](README.md)

<b><h3>THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS</h3></b>

Cookies was first created early in the web’s history.
They can be used for persistent local storage of small amounts of data, but have downsides:

- They slow down web application by transmitting the same data over and over, since they're included with every HTTP request.
- They send unencrypted data over the internet since they are included with every HTTP request.
- Cookies are limited to only 4 KB of data. This is enough to slow down your application.

What IS Ideal:
- a lot of storage space
- on the client
- that persists beyond a page refresh and isn’t transmitted to the server

“HTML5 Storage” is a specification named web storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. 

Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.

So what is HTML5 Storage?
- Its a way for web pages to store named key/value pairs locally, within the client web browser. 
- Similar to cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually) 
- Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.


