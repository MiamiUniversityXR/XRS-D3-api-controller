# XRS - d3 api timeline controller
 An auto generated cuestack from Disguise's new api in [r25.0.3](https://www.disguise.one/download/)

![image](https://github.com/XR-Studios/XRS-D3-api-controller/blob/main/public/img/Screenshot%202023-09-08%20113546.png)



 ## THIS REQUIRES R25 OR NEWER TO FUNCTION

 This software is a nodejs server that queries the d3 server with a running project and constructs a cuelist based on the time of each notation. You can search the stack and filter by track. Clicking on an annotation tells the d3 (disguise) server to jump to the specified time. By default this opens a server at port 3000 on the device its run on and can be accessed with any connected network interface.

 This is designed to work responsively on phones, tablets, laptops, and desktops. As long as you are on the network with the server running, you can access the software. Your device does need to be on a shared network with the Disguise Servers as the http requests are being made on the client side.

## To install

Get Nodejs installed on your computer from [Node JS](https://nodejs.org/en) (LTS is fine), Clone this repo, navigate to the project directory, run *npm install* then *npm start* in your terminal. Voila, your server should now be running [here](http://localhost:3000)

## Rights

Forked with permission from XR Studios and re-released under the GPL3 liscence. Currently maintained by Nate Wilkens at Miami University