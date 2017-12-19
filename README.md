# animated header for ionic 2 pages
Use the animated-header-component in a regular ionic-page like this:

`<animated-header [opacityFactor]="2">`

== Ionic page html goes here == 

`</animated-header>`

See /src/pages/home/home.html for an example

## Notes

I only tested this for ionic-pwa and mobile-views. Not sure yet how this behaves natively with cordova.
Maybe should be extended for desktop-views?
