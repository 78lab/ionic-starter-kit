# Ionic Starter Kit 
###— The most basic ionic boilerplate

[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/78lab/ionic-starter-kit)

Demo: https://play.google.com/store/apps/details?id=com.lab78.ionicstarterkit &nbsp;|&nbsp;

Join [#ionic-starter-kit](https://gitter.im/78lab/ionic-starter-kit) chatroom on Gitter to stay up to date.

#Introduction

Ionic-starter-kit is for new ionic developers.

If you try to start your first ionic project, you are more then welcome.

Before you start an ionic project, there are some issues to fix.

This project helps you don't waste time to try to find them.

Since the kit dosen't include any theme or ui-kit,
Feed free to use other starters or themes after use this.


#What's included?

###Patches and Improvements
- ios9 patch - webview patch (angular-ios-uiwebview.patch.js)
- ios9 patch - advance security patch (.plist) :  this will fix 'ionic run ios --livereload' issue and ionic deploy issue
- fix local image loading issue
- use native scroll for android
- use translate3d in css for hardware accelerated animation

###Modules and Plugins
- ngCordova
- ionic-platform-web-client
- ionic-plugin-deploy
- cordova-plugin-inappbrowser
- cordova-plugin-contacts

###Others
- crosswalk

# Prerequisite

You must have the following installed on your machine.

  * [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
  * [NodeJS](https://nodejs.org)
  * [Bower](http://bower.io)
  * [Ionic](http://ionicframework.com/docs/guide/installation.html)


# Getting Started

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

# TODO
- ngResource
- firebase
- angular-moment
- angular-jwt, angular-storage
- parse push

# References
  * [Preparing for iOS 9](http://blog.ionic.io/preparing-for-ios-9/)
  * [iOS 9 Potential Breaking Change](http://blog.ionic.io/ios-9-potential-breaking-change/)
  * [Preparing Your Apps for iOS 9](https://mobile.awsblog.com/post/Tx2QM69ZE6BGTYX/Preparing-Your-Apps-for-iOS-9)
  * [Animating Elements in your Ionic App](http://blog.ionic.io/animating-elements-in-your-ionic-app/)
  * [Crosswalk comes to Ionic](http://blog.ionic.io/crosswalk-comes-to-ionic/)
  * [Use The Ionic CLI To Integrate Crosswalk Into Your Project](https://blog.nraboy.com/2015/02/use-ionic-cli-integrate-crosswalk-project/)
  * [Setup ngCordova in Ionic](https://www.mobomo.com/2015/8/setup-ngcordova-in-ionic/)
