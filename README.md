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



Registration Form

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>User Registration Form</title>
  </head>
  <body>
    <h1>User Registration</h1>

    <form action="submit_form.php" method="POST">
      <!-- Full Name -->
      <label for="full-name">Full Name:</label>
      <input
        type="text"
        id="full-name"
        name="full-name"
        required
        maxlength="100"
      />
      <br /><br />

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required />
      <br /><br />

      <label for="password">Password:</label>
      <input
        type="password"
        id="password"
        name="password"
        required
        minlength="8"
      />
      <br /><br />

      <label for="age">Age:</label>
      <input type="number" id="age" name="age" required min="18" />
      <br /><br />

      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required />
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female" />
      <label for="female">Female</label>
      <input type="radio" id="other" name="gender" value="other" />
      <label for="other">Other</label>
      <br /><br />

      <label>
        <input type="checkbox" name="terms" required />
        I agree to the Terms and Conditions
      </label>
      <br /><br />

      <input type="submit" value="Register" />
    </form>
  </body>
</html>

