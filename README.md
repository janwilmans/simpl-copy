# simpl-copy


* simpl library forked from v3.3.8
* updated to compile using gcc 8.3.0 (just removed inline in a couple of places)
* fixed signal handers to allow coredumps from a user application to happen as usual, they were being suprressed


## note about signal handlers
<https://gist.github.com/janwilmans/49489fb4d5b5936ffcafaaddc437f292>
