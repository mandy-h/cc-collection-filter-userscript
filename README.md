# cc-collection-filter-userscript
This is the userscript version of the equivalent to the [Collection Filter Chrome extension](https://github.com/mandy-h/cc-collection-filter). It can be installed using a userscript manager such as Greasemonkey, Tampermonkey, or Violentmonkey. The main differences between this and the Chrome extension are:
* It uses localStorage to cache the guide tags, which is compatible with all browsers.
* Cache expiration isn't implemented here, so to refresh the tags displayed in the filter dropdown, you would have to manually clear the stored data. One way to do this to clear your browser cookies/website data and select the time range "All Time".
