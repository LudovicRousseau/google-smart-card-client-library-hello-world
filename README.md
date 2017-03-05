google-smart-card-client-library-hello-world
============================================
Hello World sample for the Smart Card Connector App for Chrome OS

This code is a merge from:
- Example JavaScript Smart Card Client app https://github.com/GoogleChrome/chromeos_smart_card_connector/tree/master/example_js_standalone_smart_card_client_app
- Hello Word sample application https://github.com/GoogleChrome/chrome-app-samples/tree/master/samples/hello-world

The idea is to have a more complete PC/SC demonstrator that uses the same application as my other sample codes from "PC/SC sample in different languages" https://ludovicrousseau.blogspot.fr/2010/04/pcsc-sample-in-different-languages.html

Building
---------

- download the client library:

      ./lib/download-google-smart-card-client-library.py

- download jQuery and put it in `lib/jquery-3.1.1.min.js`

Running
-------

I only tested the execution inside Chrome browser. I do not have a Chromebook.

* Install the Smart Card Connector app:

    <https://chrome.google.com/webstore/detail/smart-card-connector/khpfeaanjngmcnplbdlpegiifgpfgdco>

*   Install the Example app:

    *   Navigate to chrome://extensions page;
    *   Tick the "Developer mode" checkbox;
    *   Press the "Load unpacked extension..." button;
    *   Select the directory of the Example app.
