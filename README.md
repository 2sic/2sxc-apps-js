# 2sxc-apps-js
The $2sxc core client objects used by JS apps which want to leverage 2sxc data and toolbars.

It's a core component in [2sxc](https://github.com/2sic/2sxc/) and is maintaned separately, to make contributions easier. 

The current setup has

1. js - the shared, global js library. As DNN 7 & 8 always has jQuery installed, it also relies on jQuery
2. angular - the angular implementation 2sxc4ng

Note that this is used as a submodule in [2sxc-ui](https://github.com/2sic/2sxc-ui). That's where the packaging / bundling / minification takes place. 

Current 2sxc Version: 08.07

## How to Contribute
To create another client-side library for another framework (like flux, aurelia, etc.) just fork this, create a new folder and start developing. To test it inside DNN you'll have to load your JS from your app template with a standard `<script...>` tag, when you believe that you're ready, send us a pull request :) 

## ToDos on Existing Parts

1. $2sxc
  1. extract the parts which are not really for the client library - like the upgrade message
2. 2sxc4ng
  1. add toolbar functionality


## Desired new parts

1. Angular 2
2. React
