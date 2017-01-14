# ionic2-leaflet-demo

A demonstration of [leaflet](http://leafletjs.com/) integration in [ionic2](http://ionicframework.com)

![](https://github.com/patrickr/ionic2-leaflet-demo/raw/master/screenshots/demo.png)

## Global Dependencies
to run this or any other ionic 2 application you should install ionic, typescript, typings, and cordova globally
```
npm install -g typescript
npm install -g typings
npm install -g cordova
npm install -g ionic
```
## Installation
```
git clone git@github.com:patrickr/ionic2-leaflet-demo.git
cd ionic2-leaflet-demo
npm install
typings install
```
## Startup and Testing
you can load the app in your browser for testing just run ```ionic serve``` in the ionic2-leaflet-demo directory

### faking location for testing or privacy reasons
In chrome you can use CTRL+SHIFT+i to open the inspector/console, go to 'more tools' and open the 'sensors' panel which will provide you with the option to select from a list of locations or specify a custom one.
![](https://github.com/patrickr/ionic2-leaflet-demo/raw/master/screenshots/open_sensors.png)
![](https://github.com/patrickr/ionic2-leaflet-demo/raw/master/screenshots/select_location.png)

