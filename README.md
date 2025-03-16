# SoundWeave-App
Creating an App that can detect changes in frequencies/pitch for Instrumental scores to suggest transitions

First things first you'll need to create a youtube data/google data API account so you can pull songs/videos from youtube and scrap dynamically over pages. 
https://developers.google.com/youtube/v3
Once you have this set up, you can then run the code and just alternate the names of artists you want to use for analysis (I'm focusing on instrumental composers for film scores because that's my passion
but you can expand that out to lyrical artists etc....just see if the lyrica have an impact on frequencies and transition points/similarity values

You'll also want to remove any videos that contain your artists' name that arent specfically a music video or for me tha OST track itself....no live performances, no analysis, no interviews etc...

Start with the collection process. Because the API limits to 10,000 requests a day you can only run through so many artists a day (I'm building it out to run the code daily and collect examples over a few months
so I have a good sample size. Then once you have you sample you can feed wherever you stored the data (for me google drive) in that .txt file and convert it for analysis in the librosa package for Python (this is all in part 2).

By using this template you acknowledge you cannot claim this as your own intellectual property unless modified out substantially to other music genres 
