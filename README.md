SST Tool JS Client
===============

The JS file at https://s3.amazonaws.com/pfscreenshottool/sst_iframe.js when installed on a drupal site
Allows the SST tool to talk to it to get public data out of it in a way that the JS tool can parse it via iframes.

This modules needs to install into a drupal site and load this remote JS file on every page.

This needs to remain on S3 so we can update it as needed. Note the hardcoded url of staging.

