# openshift-banners

Used nginx proxy from openshift/router ported to a 3.11 project as base (Thanks!)

Added 3 lines for replacing the <head> on all routes with <head> <!--- replaced! ---> as a PoC that it can be done
  - Had to request to disable all compression from apps to do so
  - Will never work with TLS Passthough
  
TODO:
Host JS & CSS and inject script tags
Add to go template:
  - Read routes to inject on
  - Read raw html to inject
Start testing with all default openshift apps
