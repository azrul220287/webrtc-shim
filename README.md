*Status: DEV*

Cross-browser WebRTC API
========================

A shim around the [WebRTC 1.0: Real-time Communication Between Browsers](http://dev.w3.org/2011/webrtc/editor/webrtc.html) specification
to make a consistent & compatible API available for the following browsers:

  * [Google Chrome](https://www.google.com/chrome/)
  * [Firefox](http://www.mozilla.org/firefox/)

See it in action:

  * Minimal WebRTC Demo - https://github.com/openpeer/webrtc-demo

Usage
-----

*TODO: Instructions on how to use the shim*


Development
-----------

Development of this shim is done via a development UI:

    make install-dev
    make run-dev
    open http://localhost:8081/

Development Process:

  1. `make test`
  2. Launch dev UI
  3. Run all dev UI tests
  4. Make changes
  5. Run/write individual tests to verify changes
  6. `make test`
  7. Commit


License
=======

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2012 Fractal contact@wearefractal.com

Copyright (c) 2013 SMB Phone Inc. 
