# Docker Hub

![logo](https://imgur.com/8UL6iBD.png)

#### What is Docker Hub ?
Docker Hub provide you a place to put all your different url for all your docker and web apps.

#### How to add an app to your hub ?
Edit the `index.html` file
```js
var data = {  
  "apps" : [
    {
      "name" : "Name",          // The name you want your app to have
      "icon" : "name.png",      // The name of the logo of your app (must be located in /img)
      "url" : "http://ip:port"  // The url of the app
    },
    {
      ...                       // Feel free to add as many app as you want to the array.
    },
  ]
}    
```