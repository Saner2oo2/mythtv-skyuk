This is a very much, use at your own risk setup.

Initially you will want to set up your channels ordering and numbers, you can do this by running 

./dumpchan (in /create-channels)

This *should* sort out all you channels for you, most of the HD ones are removed as they are usless.

Once you have your channels setup you can run 

./updateepg (in /grab-epg)

This *should* pull the next 7 days EPG data and insert it into MythTV.

Every step is hashed, so you can read and see what it is doing.

You will need to set some channels to invisible (obviously) as Sky have duplicates, and it would be a nightmare to setup a script based on regions.

You will have lots of "N  Unknown xmltv channel identifier: " just ignore them and they might go away :).


TODO - Fix Radio Stations, Fix E4, clean up scripts, look at using Bouquets for regional setups.
