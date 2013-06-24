pyiso8601-strict
================

## The current pip verions of this util has not been updated since 2007.  
The package does not throws errors on a lot of parse exceptions leading to erronous data.
I got screwed over by this and decided to fork the repository and apply all the outstanding patches.
##



***



###Update Version -- Simple Python module to parse ISO 8601 date strings###




A simple package to deal with ISO 8601 date time formats.

ISO 8601 defines a neutral, unambiguous date string format, which also
has the property of sorting naturally.

e.g. YYYY-MM-DDTHH:MM:SSZ or 2007-01-25T12:00:00Z

Currently this covers only the most common date formats encountered, not
all of ISO 8601 is handled.

Currently the following formats are handled:

* 2006-01-01T00:00:00Z
* 2006-01-01T00:00:00[+-]00:00

I'll add more as I encounter them in my day to day life. Patches with
new formats and tests will be gratefully accepted of course :)

References:

* http://www.cl.cam.ac.uk/~mgk25/iso-time.html - simple overview

* http://hydracen.com/dx/iso8601.htm - more detailed enumeration of
  valid formats.

See the LICENSE file for the license this package is released under.
