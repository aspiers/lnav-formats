# Log format description files for lnav

[http://lnav.org](lnav) is a powerful log file reader, designed to take
multiple log files and order them by date.  It understands log file formats
using regular expresions and can highlight sections of line, find errors
and warnings, and more.

This repository is for the log file format descriptions I've written so far.

You can install these by simply checking this directory out in your
`~/.lnav/formats` directory.

## lnav version compatibility

Some of these formats may use features that are only available in `lnav`
version 0.8.0 or above.  If you get warnings, try renaming the
offending files to end in `.json-unused` to see if this fixes things.
