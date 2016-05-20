# Configuration

In this section we wille lear how to edit appbase ionic conf.
The main config file is located at `www/app/conf/ConfParams.js`.

## Setup api endpoint : API_ENDPOINT

That config make the link between the mobile app and the REST api.

* Manually

Edit `www/app/conf/ConfParams.js` and change the value of `API_ENDPOINT` constant.

* Using grunt

The default grunt task can be used to edit `ConfParams.js` via env vars.
It use [ngconstant](https://github.com/werk85/grunt-ng-constant) grunt plugin to edit de conf file.

Example :

```
export API_ENDPOINT=http://your-server-with-appbase.org/api 
grunt && ionic serve --lab
```

