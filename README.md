# Cordova Plugin to hack ipv6 off

There is a bug in java that will cause things like setting the TTL on UDP multicast to fail if you have both ipv4 and ipv6.
This lets you work around that by disabling ipv6.

## Using

Install the plugin

    $ cd ipv6_disable
    $ cordova plugin add https://github.com/jontaylor/cordova-disable-ipv6
    


Install Android platform

    cordova platform add android
    
Run the code

    cordova run 

## More Info

For more information on setting up Cordova see [the documentation](http://cordova.apache.org/docs/en/4.0.0/guide_cli_index.md.html#The%20Command-Line%20Interface)

For more info on plugins see the [Plugin Development Guide](http://cordova.apache.org/docs/en/4.0.0/guide_hybrid_plugins_index.md.html#Plugin%20Development%20Guide)
