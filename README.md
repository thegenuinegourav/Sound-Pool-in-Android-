# Sound-Pool-in-Android-  
Sound pool is actually audio mixer. It can play short clips only regardless of whether they are encoded as ogg or mp3 or 
they are uncompressed. Sound pool always store them in memory uncompressed, and you must know that limit is 1 MB.  
  
Can be used for short clips (need to get played 10 times per second) in game development.  
  
In a closer look, the SoundPool class uses the MediaPlayer service to decode the audio into a raw 16-bit PCM mono 
or stereo stream and play the sound with very low latency, thus helping the CPU not suffer from the load of decompress effort.  
  
If it is helpful to you then follow me (you can give it a star too), I will make some more useful standard codes..
Happy Coding :)
