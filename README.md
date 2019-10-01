# cordova-vue-startup
a cordova startup project
## Prepare 
```
npm install -g cordova
npm install -g vue
npm install -g vue-cli
vue init webpack myapp
cd myapp
npm install
```
modify config/index.js
```
build:{
...
index:  => '../../www/index.html'
assetsRoot:  => '../../www'
assetsPublicPath:  => ''

}
```
## build
```
cd myapp
npm run build
cd ../
cordova build ios

```
open platform/ios/ in xcode and build project
