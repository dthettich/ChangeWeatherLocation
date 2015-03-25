# ChangeWeatherLocation
Automatically changes settings in pretty-weather.widget to current location. For all those who carry their 
laptops around a lot.

ChangeWeatherLocation is a small shell script that automatically obtains Latitude and
Longitude via OS X's [CoreLocation](http://en.wikipedia.org/wiki/CoreLocation) 
framework and sets these values in [pretty-weather](http://tracesof.net/uebersicht-widgets/#pretty-weather)
widget's config for [Übersicht](http://tracesof.net/uebersicht/). [Übersicht](http://tracesof.net/uebersicht/) 
is an incredibly versatile desktop widget tool for OS X implemented by [Felix Hageloh](http://tracesof.net/).
Felix is also the author of the [pretty-weather](http://tracesof.net/uebersicht-widgets/#pretty-weather) widget.

ChangeWeatherLocation builds upon [whereami](https://github.com/robmathers/WhereAmI) implemented by
[Rob Mathers](http://grmm.ca/).

Usage
-----
Simply download the [whereami](https://github.com/robmathers/WhereAmI) executable. Then download ChangeWeatherLocation and execute in the same directory, either by double-click or in the terminal.

Notes
-----
I discovered [Übersicht](http://tracesof.net/uebersicht/) some hours ago and wrote this pretty quickly. 
I tested this script but make no guarantees or warranties whatsoever that it works for you as well. 
Additionally, I tried to have this script executed every time the network changes for convenience. 
It turns out that this is a rather difficult task, however. If you have suggestions, please feel free to drop me a message.