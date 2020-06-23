# MicroReact
This is non-optimized version of modern React JS framework with useState hook implemented

Usage: 
1) import Reacto to your component, you should export it first from reacto.js
2) Make your entry (it is "./reacto.js" by default) in webpack config file
3) Make your app component, then add following:
  ```
  const container = document.getElementById("root")
  reacto.render("Your app component/function name", container)
  ```
  And remove same code from reacto.js (it will be fixed later :D)
  
  
  

4) Use npm run build to compile app component with babel
5) Just open index.html file to run a site.
