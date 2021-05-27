# What is this ?

have you ever tried to find a good image viewer gallery on web ? that is feeling like native app on phone and has good feels on pc, and that is not a dark heavy expensive wordpress plugin or an old shit running on jquery ? I bother me so much so I pocked something after a long time of research. I will eventually come with a custom implementation with react support one day but here is the first poc...

# How to run the project ?

* `yarn && node server.js`
* open http://localhost:8080
# What does it use

It's a poc in vanilla modern js. It uses:

* swiper.js
* photoswipe v5 (early stage)

# Implemented features:

* good perfs
* native feel on phones (gestures/swipe/double-tap/pinch/history/transitions)
* good enough feel on desktop/laptop
    * missing apple trackpad gesture support
    * missing mouse wheel support
* native fullscreen toggle
* lazy images + preload of close images

# Incoming features:

* responsive image and adaptative sizes
* responsive ratioed layout
* pan-position & zoom level restauration when toggling native-fullscreen
* support complexe html slides (image + placeholders + whatever)

# Out of scope:

* videos and other medias support
* image zoom tiling

# next step:

make custom implementation based on:

* https://github.com/pmndrs/use-gesture
* https://github.com/willmcpo/body-scroll-lock
* https://github.com/d4nyll/lethargy
* ...

# Help me !

If you did great researches online, or you think I might be interested by a cool lib somewhere, please drop me a message by email (@ in bio)