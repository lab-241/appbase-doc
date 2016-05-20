### Getting started with App Base

App Base is your production ready mobile app foundation.
Its the result of two framworks combined to create a powerfull fullsatck js ecosystem.

### App Base projects

| Need |Solution| AppBase repo |
|---|---|---|
|REST API|[LoopBack Framework](https://strongloop.com/node-js/loopback-framework)|[Appbase server](https://github.com/lab-241/appbase-server)|
|Mobile App|[Ionic Framework](http://ionicframework.com/)|[Appbase ionic](https://github.com/lab-241/appbase-client-ionic)|
|Admin Dashboard|[NG-admin](https://github.com/marmelab/ng-admin)|[Appbase server](https://github.com/lab-241/appbase-server)|

### Development quick start

__Prerequites__

* [NodeJs](https://nodejs.org/en/download/package-manager)

__Install dev tools__

App base is built on top of ionic (who use cordova) and strongloop.
Some others automation tools (like gulp) are required.

```
npm install -g cordova ionic strongloop grunt-cli gulp bower karma-cli phantomjs
```

__Start app components__

* Start loopback REST api server

```
$ git clone git@git.mikangali.com:lab-241/appbase-server
$ cd appbase-server
$ npm install
$ grunt
```

Server is running at `http://localhost:3000`

* Start ionic mobile app

```
$ git clone git@git.mikangali.com:lab-241/appbase-client-ionic
$ cd appbase-client-ionic
$ bower install
$ ionic serve --lab

# Run ionic app on android

$ ionic platform android
$ ionic run android --livereload
```

## Links

* [Project website](http://appbase.ga)
* [Github repo](https://github.com/lab-241/appbase)
* [Slides show](https://slides.com/mikamboo/app-base/edit)