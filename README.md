websockets-streaming-audio
==========================

Click a browser button to launch a node.js process on the server side which streams audio using web sockets back to the browser which is then rendered using web audio API

I am currently addressing some edge conditions, but the basic idea is finally functional

My plan is to make this modular enough to get added to your process as simple API calls

# Installation

visit [nodejs.org](http://nodejs.org) and install node.js

see project npm site at 

[https://www.npmjs.org/package/websockets-streaming-audio](https://www.npmjs.org/package/websockets-streaming-audio)




Clone this repository to your local machine:

```bash
npm install websockets-streaming-audio
```
Change directory into the project folder websockets-streaming-audio

Then install the dependent modules:

```bash
npm install
```


Launch the nodejs app:

```bash
npm start
```


Using a WebGL savvy browser, point it at URL :

```bash
		 http://localhost:8888 
```

now in your browser (firefox/chrome) click stream_audio

or ignore above and just see this WebGL app deployed live on heroku :

[http://websockets-streaming-audio.herokuapp.com](http://websockets-streaming-audio.herokuapp.com)


Feel free to contact me on twitter if you have any questions! :) [@scottstensland](http://twitter.com/scottstensland)


