# Conference-Room
A collection of .net application for a conference room system.

We needed a better way to project our screen to the conference room tv, we tried wireless HDMI of all brands and ended up back with a cord. We looked in to some "click to screen" usb dongle, that had alot of the same problems and cost a ton. So I decided that if we were going to give up the "outside" user part for now. We might as well make something that is easy for us.

(By the way we tried screen mirroring on smart TVs but that didn't really work great on most of our machines and we had a ton of TV so it wasn't as easy as I think this is)

Programs:
  A "Server" that runs on a conference room TV, meant to be on "all the time" and run on a stick PC.
     Features:
        A pretty background graphic / logo
        The time and subject of the next meeting (pulled from EWS)
        A screen share host
        Control the TV (coming soon) - over RS-232 and CEC
        Multiple screens at once (coming soon)
  
  A "Client" program that displays your screen (primary screen only) on the selected conference room TV.
     Features:
        Simple - click on the icon in the notification bar select the TV you want to send to.
        
 A "Client" program that displays the background image and upcoming meetings (coming soon)
    Features:
       I use surface 3, with a POE to USB adatper, and a nice mount, they are super easy to disable all kinds of stuff so people can't "break" them. I'm going to mount them outside the rooms, I will probably give a way to schedule meetings from them, but I have to get everything else working completely first.
       


You can use this for anything you want, if you do end up using it, let me know and I would love to work on this with someone else so if you have ideas, or want to submit some pull requests that would be awesome.


        
        
