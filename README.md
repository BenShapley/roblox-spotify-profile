![Logo](gh-assets/SpotifyRobloxLogo2.png)

<h4>A Playlist Generator Customised For Your Robloxian</h4>

<h5>This is part of the full <a href="https://github.com/proud-p/spotify-roblox-project">Spotify to Roblox Studio</a> workflow.</h5>



<p>
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#credits">Credits</a> 
</p>




![spotify_images](gh-assets/SpotifyScreenshot.png)

## Key Features

* Robloxian Searching
  - Search for a specific Roblox player by their username or find similar results
  - Pick from the user from the results to start building the playlist
  
* Playlist Creating
  - Create a playlist based on the Robloxian username
  
* Album Cover Setting

  * Album cover set based on their profile Thumbnail
  * Fully personalised  

* Playlist Opening

  * Playlist opens directly into your browser to start playing!

  

## How To Use

Before trying to run this application, please ensure you install all of the correct libraries to a virtual environment.

> **Note**
> Please refer to the [**requirements.txt**] in the repository to install all of the correct and up-to-date libraries.



1) **Cookie Grabbing**:

   Log into your Roblox account and use *Google Chrome* for easily cookie grabbing

   Enter Inspect Element (CTRL + SHIFT + I) -> Application -> Cookies -> Grab your **.ROBLOSECURITY** cookie

   Save your cookie as a .txt file, saved locally within the repository in a folder named 'keys'

   > **Note**
   > Do not share this Cookie with anyone, doing so can compromise your account

![CookieLocation](gh-assets/CookieLocation.png)

2. **Inputting a Roblox Username:**

   Once you have been authenticated and you are in your code editor, input a username within the '**desired_name**' variable. This be the username being searched

3. **Pick A Username From Results:**

   After sending of your input, a list of names will be returned that have been found on the roblox website.

   Use the '**formatted_names**' variable index to choose one of these names

   > **Note**
   > Idex will return the desired result from the list, starting from an index of 0 up until the final result

4. **Let the Code Do It's Thing:**

   Let the code run, ensuring you are logged in on the <a href="https://open.spotify.com/">Spotify</a> homepage



## Credits

Huge thanks to:

- [ro.py](https://ro.py.jmk.gg/v2.0.0/)
- [spotipy](https://spotipy.readthedocs.io/en/2.24.0/)
