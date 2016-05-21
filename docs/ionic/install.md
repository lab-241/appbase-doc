### Appbase : Ionic mobile client installation

Appbase __mobile client__ is a [ionic framwork](http://ionicframework.com) project built to work with the [appbase-server](https://github.com/lab-241/appbase-server) project. This mobile client consumes the [appbase-server](https://github.com/lab-241/appbase-server) REST api.

## Pre requistes

* [Node.js](http://nodejs.org), Cordova and [Ionic-cli](https://npmjs.org/package/ionic) are required on your computer to start this project.

## Dev tools install

When [Node.js](http://nodejs.org) is present on your environment just run following command to install appbase-ionic dev requirements.

```
$ npm install -g cordova ionic grunt-cli gulp bower karma-cli phantomjs
```

__CAUTION__ : Before start the client, you must ensure that server is up and running. Read [install server tutorial](../server/install.md) for instructions.

## Get + start appbase ionic

```
$ git clone git@git.mikangali.com:lab-241/appbase-client-ionic
$ cd appbase-client-ionic
$ npm install
$ ionic serve --lab
```

## Run ionic app on android device/emulator

```
$ ionic platform android
$ ionic run android --livereload
```

### About Ionic framework

Ionic is an open source mobile SDK for developing cross-platfom

![](../img/ionic-logo.png)

For more about ionic projects, read official [doc](http://ionicframework.com/getting-started/).
