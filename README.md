# PingPongPlatform
PingPongPlatform (PPP, TripleP). Table Tennis VAR, 1on1 coaching using AI, and currrent world rankings. 


I want to make an all in1 ping pong platform


Analyze your clips ( 1 on 1) coaching, rankings of current world rankings, Video Assistant referree in live matches. using your phone. (Phone as camera, connected to an external screen for best set up). 


Ok so what are the major pieces to this? First off I want this both as a mobile and a web app. So we would need whatever stack accepts both. The for our features we should have

1. VAR (mixture of CV and video generation) 
2. Coaching using CV methods and trained models
3. Table of live rankings to keep up

Biggest thing here would be streaming the data to the live running server for CV analysis and live point tracking. 
2. How can we host this at a free charge? aka where is there free compute for this? What can we host on free of charge? 
3. How do we visualize the VAR to work? Track points? Faults?
	1. we need some rules in which our program will be based off of. 
4. How should the user interact with this? How can we have the camera function as the primary device for video streaming and connect to another device to showcase score? 
	1. What kind of concepts are needed for me to understand? 


## Pieces of the puzzle 
1. VAR (hardest part)
2. 1on1 Coaching 
	1. CV models tracking ur technique and faults. 
	2. Train models on youtube videos from top ranked professionals.
		1. Potentially scrape the web for videos, pretrained models on ping pong, or publicly available datasets (video data)
3. Live rankings
4. Design the front end. Biggest piece to our puzzle