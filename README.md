## master-vue-cordova-webpack-pwa

> This is master of setting up a development platform on which you can build Hybrid web and mobile apps.  
> This includes:  
> - Cordova + Webpack + Vue.js + PWA (there are still a few bugs for pwa)
> - Unit Testing with Jest/Mocha-Karma
> - Functional Testing with Nightwatch
> - Preview your app in the Web Browser
> - Build to Android/iOS mobile devices

#### Starting a Master Vue Cordova Webpack PWA
``` bash
git clone https://github.com/eksant/master-vue-cordova-webpack-pwa <your-app>  
cd <your-app>  
npm install
```

#### Running on Website (localhost:8080)  
``` bash
# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

#### Running on mobile   
``` bash
# add platform android
cordova platform add android

# running on android device
cordova run android

# add platform ios
cordova platform add ios

# running on ios device
cordova run ios
```

#### Run Test   
``` bash
# run unit tests
npm run unit

# run all tests
npm test
```

![npm run unit](master-vue-cordova-webpack-pwa/src/assets/npm-run-unit.png)

**Need Contributors.**  
We are actively looking for contributors for testing and documentation. Please contact us: eksant[at]gmail.com. I really appreciate your cooperation.
