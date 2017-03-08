# geolocationAPI
Using the HTML5 Geolocation API, I built a simple app that requests the user's location and displays it on a Google map embeded within the application. 

<img src="demoscreenshot.png">

<h3>HTML5 Geolocation API</h3>
The geolocation API provides developers with scripted access to geographical information associated with the hosting device. Essentially it has allowed developers to focus more on the data they can extract and how to use it, rather than how to get it. However due to some out-lying factors the results aren’t always super accurate, and there for, shouldn’t be 100% relied on. 

<h3>Browser Compatibility</h3>
As of right now HTML5's geolocation compatability is as such: 

<h4>Desktop</h4>
  <ul>
  <li>Firefox 3.5+</li>
  <li>Chrome 5.0+</li>
  <li>Safari 5.0+</li>
  <li>Opera 10.60+</li>
  <li>Internet Explorer 9.0+</li>
  </ul>
  
<h4>Mobile</h4>
  <ul>
  <li>Android 2.0+</li>
  <li>iPhone 3.0+</li>
  <li>Opera Mobile 10.1+</li>
  <li>Symbian (S60 3rd and 5th generation) </li>
  <li>Blackberry OS 6</li>
  <li>Maemo</li>
  </ul>
  
  <h3>Geolocation Methods</h3>
  The geolocation object can be used within JavaScript to gather location information about the device through the browser, and it uses three public methods.
  
  <strong>getCurrentPostiion()</strong> :The get current position function does what you’d imagine it would, it grabs the coordinates of the devices location through the browser.</br>
  <strong>watchPosition()</strong> :The watch position method, updates the location at a set interval, so if the user was in a vehicle the location would change over time.</br>
  <strong>clearWatch()</strong> :The clear watch method, is what stops watch position.</br>
  
  <h3>Geolocation and Privacy</h3>
  Due to the nature of the geolocation API, the browser will always request permission to access the user’s location. The get current position function is what makes a request through the user’s browser, it is here that they will see a pop up that will ask them if they’d like to share their location or not.
  
  <h3>How it works</h3>
  <p>Well for starters it's dependent on the brwoser, and from there it searches for numerous factors which include:</p>
<ul>
<li>IP address</li>
<li>Cell tower IDs</li>
<li>GPS information</li>
<li>WiFi access points</li>
<li>Signal strengths etc.</li>
</ul>
Then each browser uses it’s own location services, and an approximate location is then returned, via a JavaScript callback.

Where the user is makes a difference as well. For example they will yield more accurate results if they're in an urban area, versus a rural one, or if they're stationary, versus moving. Users who use a VPN to alter their location, will also get inaccurate results. 

<h3>So let's get to the code!</h3>








