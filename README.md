PhotoFlip - submission for Global Android Dev Camp 2012 - bit.ly/PhotoFlip
==========================================================================

[Note that this was developed over the course of 24 hours and hasn't been touched since, but still should be a viable example of a Sony Smartwatch App.]

LiveView photo slideshow app.
-----------------------------

This is a modified version of the SmartWatch sensor example. Added a mechanism to detect a flipping motion of the wrist.

It makes an HTTP get request for a list of URLs, then grabs an image from each one. It vibrates at the end of the list of images before it starts over again.

It caches the Bitmap's in memory so it's faster the second time around.
