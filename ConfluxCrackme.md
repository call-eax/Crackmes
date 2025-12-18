I'm solving the crackme from https://crackmy.app/crackmes/keygenme-conflux1-by-conflux-by-crackmes-de-37597

It has been chosen randomly by clicking the "I'm feeling lucky" button on the website's advanced search form.
I recorded my screen while solving this crackme, so no dedicated writup is available (read: lazy slob :grin:).

The video has been split into 4 parts to meet Youtube's "we will let you upload longer videos only if you give us your telephone number" criteria for
unverified users.

This is my first video of this sort, so of course I made a big boo boo by placing a semicolon at the end of an if statement and not noticing it until after the video was finished.

I also totally forgot to point out, why the keygen has to start the crackme, so let me explain:
The crackme uses a call to time(0) to get the number of elapsed seconds since epoch and uses them to seed the random generator.
Since the resolution of time() is one second, the crackme has to be started within the same second in order for the keygen to get the same value and be able to calculate the relevant char.
Thus the keygen first gets time(0) and starts the crackme immetiately afterwards, which then should run within the same second and therefore get the same seed value.

Playlist is here: https://www.youtube.com/playlist?list=PLnntGq1c257P5dt0TB1vNILAylSJB5u42

No narration

