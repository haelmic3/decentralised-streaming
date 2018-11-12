Copyright 2018 Michael Julian Moran
Content is licensed for distribution under GPLv3 see attached for details.
# Decentralised Streaming
As a consumer of video and streams,
 and someone who knows the expensive computer resources,
 I think,
 it would be the greatest to have a video and stream shareing service,
 that was entirely controled by the artist.
I am also aware,
 networks are the most important thing for sharing stuff,
 so there must be few places for content,
 with many ways of distributing it.
This is my solution.
## Server
A server operates as a network point for shareing.
It has the job of viewing and distributing content efectively,
 using the design norms of the main platforms,
 while adding the incredible features that this service alone can do.
What are the features?
### Content decent
Content decent is the act of making things people want to see seeable,
 while pushing out things they don't want to.
Why do you need content decent?
Content decent is how finding things on the internet works.
It is how all search engines work,
 Every single search engine has content ranking.
Any query to a database must return in some order.
The order can be random or based on some arbratrary order.
Content decent should be the default order.
In a system where every entry is checked using datetime as the order makes sense,
 as everything needs to be looked at eventualy so look at the newest first or oldest unchecked first.
This system dosen't work on the internet and is not what the user expects.
A user of a ststem wants to go to the system that has what they are looking for and the want to find it in one step or they will go elsewhere.
If they can't find it anywhere else they might come back and take more steps but this is the internet.
We have one chance. (Who's we?)
### Video delivery
The point of the server as a service is that the video is not hosted on the server rather it is linked and perhapse cached to the actual video.
Videos must be manualy added the point is to make video sharing easy not to just replace entire sites.
### Video streaming
Video streaming is the most taxing feature and needs to be backed by hardware.
Please be warned you might want to disable the feature if it cannot be handled by your network.
This software will never clame to be able to deliver streaming service despite seeming to do so.
Results may vary.

Video streaming is the abiliy to provide direct comunication between a client and the hosting server's audance.
Client programs can interface with the server directly or the server users subscribe to a stream blast and their ip is added to a udp stream that they can listen to.
Udp streams can choose to stream just audio just video at some resolution or tap into a recording where the audio and video is syncd.
### Server layout
will determin.

## Open-Souce Closed-Commit
To keep the source clean this project will not accept code from unknown indeviduals.
Please feel free to fork under the provided license but never push to to the source.
This is a slow-moving project.
This is a usecase of applied code to be completed over years.
The commit structure is fragile by design.

## What is the commit structure?

I've worked with feature branches. They were a mess.
So I don't know what I'll do but probably this:
 - minor changes will be increased by 0.0.1 for fixing stuff correctly
 - major changes will be increased by 0.1.0 for adding stuff working
 - release changes will increase by 1.0.0 done... so in your dreams
 - forks that just fix stuff can be marked \*.[a-z].1
 - forks that add stuff can be marked \*.[a-z].1.0 
 - forks that actualy work... lol never but they cool like [a-z].[1-4].0.0
otherwise everything is pushed to master.
weird glitches can get branches so that might happen. They will get funky names.

## Why are you doing this ?
The point of the project is to develop content delivery.
Why? Because I want it. And because I think there's too much power in video and streaming networks and I want to provide people with more control.
This product is not a replacement to any service but a capable suplement.
Suplementing this industry is not easy which is why I __assume__ it's not been done.
Why don't you just release a website?
Computers cost money so let's pretend I don't have any.
