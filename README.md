# NOTE: this repo is old and not maintained.
Please visit the main fork at 
https://github.com/OpenBekenIOT/webapp


# OpenBekenIOT Web App

This repo publishes a simple javascript webb app to

https://openbekeniot.github.io/webapp/

The web app is initialted by a very simple webpage on the device at http://(IP)/app

Currently the address the device uses is hardcoded, but soon there will be a configuration, so you can host locally on your LAN for more security.

This calls for startup.js, which then loads VueJS and a SFC myComponent.vue, whic is the guts of the web app.

This is in prototype form at the moment, and currently can display logs from the device.
