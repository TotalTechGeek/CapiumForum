# CapiumForum
A small, lightweight portable forum written in Node.js


### Welcome
This is a lightweight forum. It is similar to [Reddit](https://www.reddit.com) in some ways, due to it being board based. 

The forum gives you the ability to like and dislike posts, post pictures, paste links, and format text. It supports markdown, which is the same syntax used by popular websites such as [Github](https://www.github.com) to display formatted text.

Having been developed in 2013, the website uses technologies that were fairly new at  the time. The website is built on [socket.io](http://socket.io/), which creates [websockets](https://en.wikipedia.org/wiki/WebSocket) to allow new posts and edits to show up on everyone's screen in real time. 

Browsing the forum is very quick, as all of the threads are served as compact [JSON]() through the websockets. Rather than using old techniques rendering the website on the server, the rendering is left to the client, which makes response times much faster and allows the server to serve many more requests.

Because the server is powered by [Node.js](https://nodejs.org/), which is based on Google's V8 JavaScript Engine](https://developers.google.com/v8/?hl=en), JSON is native and serializing the forum to send to the clients is fast and easy. No libraries for parsing necessary.

The entire forum setup is 11KB compressed, miniscule in comparison to other forums, but similar in core functionality. Now that I am a more mature developer, I will likely add more features to the forum, and enhance the security.

### Running the Server

Use the terminal command :

```node server.js ```


### Demo
There is a small demo up and running at 

http://forum-creatorjames.rhcloud.com/
