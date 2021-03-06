# Shredify

## by [Ryan Mathisen](https://github.com/rtmath), [Nigel Burnett](https://github.com/nigelorion), [Quinn Schwartz](https://github.com/quinnschwartz) and [Rafael Perez](https://github.com/doohinkus) 2/2/2017

# Description

_Shredify is a mobile app built with Angular2 and Ionic that allows users to browse skate spots in their area. User can view spots by panel view or using google maps, and can filter either view using a filter located in the menu. Users can also add their own spot using phone geo-location or google maps marker placement, upload a photo from their phone's camera or gallery, and choose name and features for their spot. The core data of the app is user-driven and stored in firebase._

**A seed.json is supplied with this project if you would like to import it to your own firebase for ease of use.**

## Requirements
This project requires:
  * npm
  * bower
  * Typescript
  * Angular2
  * Ionic2
  * Cordova

## Installation
  * Clone this repository to a location on your computer
  * Add a ~/src/app/api-keys.ts file with the following code (adding your api key info from firebase):
  ```javascript
   export var masterFirebaseConfig = {
    apiKey: "YOUR API KEY HERE",
    authDomain: "YOUR AUTHDOMAIN HERE",
    databaseURL: "YOUR DATABASE URL HERE",
    storageBucket: "YOUR STORAGE BUCKET HERE",
    messagingSenderId: "YOUR MESSAGING SENDER ID"
   };
   export var mastergoogleMaps = {
      apiKey: "YOUR API KEY HERE"
    }
  ```
  * Navigate to the repo location using your console/terminal and run the following commands:
    * npm install
    * bower install
    ##### THEN (to view in browser)
    * ionic serve
    * Then navigate to localhost:8100 in your browser and enjoy!
    ##### OR (to view natively on your mobile device)
    * ionic build android (or ionic build ios for iOS devices)
    * ionic upload
    (using this method requires the Ionic View app, enter the app id generated by ionic upload or the id found in ionic.config.json)


## License
Copyright (c) 2016 [Ryan Mathisen](https://github.com/rtmath), [Nigel Burnett](https://github.com/nigelorion), [Quinn Schwartz](https://github.com/quinnschwartz) and [Rafael Perez](https://github.com/doohinkus)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
