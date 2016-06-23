cascade~
-------

I wanted to play with a version of **clone** that would cascade the audio from each clone to the next.
This works by using clone but only having the first instance read from the inlet~ and the last write to the outlet~ and using the set message for throw.
