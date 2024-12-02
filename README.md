<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Multimedia Webpage</title>
  </head>
  <body>
    <h1>My Multimedia Webpage</h1>

    <h2>Audio Player</h2>
    <audio controls>
      <source src="audio.mp3" type="audio/mp3" />
      <source src="audio.ogg" type="audio/ogg" />
      Your browser does not support the audio element.
    </audio>

    <br /><br />

    <h2>Video Player</h2>
    <video width="600" controls poster="video-poster.jpg">
      <source src="video.mp4" type="video/mp4" />
      <source src="video.webm" type="video/webm" />
      Your browser does not support the video element.
    </video>
  </body>
</html>
