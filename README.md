# Spotify Playlist Analyzer: Final Project for Sta323 Statistical Computing

For this project, I wanted to make something really practical that I would use. 
After I thought for awhile, I realized a common issue I have is that there's 
not a lot of nice tools for Spotify to manage playlists. I store all my music 
in one large mega-playlist (about ~3000 songs), which, while I like, doesn't 
let me easily analyze my music or communicate my taste in music to others. 
For example, if I wanted to send all of my music of a certain genre, or a 
certain feel, I'd have no way of doing so easily without manually doing so. 
This is clearly intractable for me now with the amount of music in my playlist,
and it's even worse for some of my friends, who have playlists with > 10,000 songs.

As a result, I resolved that I wanted to make a ShinyApp that made it easy to do 
a few key tasks with playlists. For one, I wanted to be able to filter my 
playlists by a variety of features easily, as well as have visualizations that
let me understand both the distribution of my music and how to effectively filter 
it. I also wanted to make the app capable of handling Liked Songs, an internal 
playlist that Spotify doesn't normally let you turn into public playlists. My 
friend has all of his music in his Liked Songs, and it makes it really difficult
for him to share music in a mass-way. 

Finally, I wanted to have a clean implementation to combine playlists together,
as the current method of dragging and dropping in the Spotify client becomes
really cumbersome for large datasets. 

Unfortunately, due to limitations with the SpotifyR API, this webapp can only be run locally
on someone's machine by pulling the code here and running it in their RStudio. 
