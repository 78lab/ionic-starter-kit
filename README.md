## Ionic Starter Kit — The most basic ionic boilerplate

Demo: https://play.google.com/store/apps/details?id=com.lab78.ionicstarterkit &nbsp;|&nbsp;
Join [#ionic-starter-kit](https://gitter.im/78lab/ionic-starter-kit) chatroom on Gitter to stay up to date.

##Why?

There are some issues to fix before you start ionic project.
This project helps you don't waste time to try to find and fix yourself.
This project dosen't include any theme or ui framework.
Feed free to use other starter or themes after use this.

###What's included?

#Patches and Improvements
- ios9 patch - webview patch (angular-ios-uiwebview.patch.js)
- ios9 patch - advance security patch (.plist) :  this will fix 'ionic run --livereload' issue and ionic deploy issue
- fix local image loading issue
- use native scroll for android
- use translate3d in css for hardware accelerated animation

#Modules and Plugins
- ionic platform web client
- ionic-plugin-deploy
- cordova-plugin-inappbrowser

#Others
- crosswalk



### Getting Started

Just clone the repo:

```shell
$ git clone git@github.com:78lab/ionic-starter-kit.git MyApp
$ cd MyApp
$ cordova prepare               # Restore cordova plugins
$ npm install                   # Install Node.js components listed in ./package.json
$ bower install                 # Install Node.js components listed in ./bower.json
$ ionic io init
$ cp ./tmp/info.plist ./platforms/ios/MyApp/MyApp-Info.plist
```

### TODO
- ngCordova, ngResource
- firebase
- angular-moment
- angular-jwt, angular-storage
- parse push

### References
  * [Preparing for iOS 9](http://blog.ionic.io/preparing-for-ios-9/)
  * [iOS 9 Potential Breaking Change](http://blog.ionic.io/ios-9-potential-breaking-change/)
  * [Preparing Your Apps for iOS 9](https://mobile.awsblog.com/post/Tx2QM69ZE6BGTYX/Preparing-Your-Apps-for-iOS-9)
  * [Animating Elements in your Ionic App](http://blog.ionic.io/animating-elements-in-your-ionic-app/)
  * [Crosswalk comes to Ionic](http://blog.ionic.io/crosswalk-comes-to-ionic/)

### Learn More
### Support
### License
