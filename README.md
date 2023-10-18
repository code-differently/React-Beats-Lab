Welcome to your very own music studio. In this lab, we'll dance to the beats of code and melodies of React components, focusing on artists like Rod Wave, Brent, Drake, and SZA. But remember, this is your studio, so feel free to remix with your favorite tunes!

---

### **🌌 Set Up Your Studio**

1. Fire up your terminal or command prompt.
2. Navigate to your `dev` folder.
3. Initiate a new React project named `react-beats-lab`.
4. Enter your project's directory: `cd react-beats-lab`.
5. Create a `components` folder within the `src` directory to house your sound components.

---

### **Exercises**

---

**1. 📜 My Favorite Tracks**

Objective: Display a list of your favorite tracks.

Tasks:
- Inside `components`, create `Playlist.js`.
- List out a few tracks by Rod Wave, Brent, Drake, and SZA.
- Use `.map()` to showcase each track in a list format.

**Hint:** Don't forget to assign a unique `key` prop for each item when you map.

**End Result:** A list displaying something like:

```
- Rod Wave: Street Runner
- Brent: Dead Man Walking
- Drake: Laugh Now Cry Later
- SZA: Good Days
```

---

**2. 🔔 Song Request Bell**

Objective: Implement a feature to request a song.

Tasks:
- Craft `SongRequestBell.js`.
- When the button is clicked, display an alert indicating a song request.

**Hint:** Use the `onClick` event handler.

**End Result:** A button labeled "Request a Song" which, when clicked, shows an alert saying "Song request received!"

---

**3. 🎧 Headphone Sessions**

Objective: Keep track of how many times a song has been played.

Tasks:
- Design `TrackPlays.js`.
- Create a button representing a track. Each click should increase the play count.

**Hint:** You'll need to utilize the `useState` hook.

**End Result:** A button saying "Play Rod Wave: Tombstone". Each press updates the button to: "Played X times!"




## Challenge
🎵 Genre Jukebox

**Objective:** A jukebox that reveals top artists from different genres at the press of a button.

**Tasks:**

1. Craft `GenreJukebox.js` within the `components` folder.
2. Design five buttons corresponding to these genres: Rap, R&B, Pop, Country, and Afrobeats.
3. When a button is pressed, it should unveil a top artist from that genre.
   
**Hint:** Use React's state to dynamically display the artist based on the button clicked.

**End Result:** When the "Rap" button is pressed, it might reveal "Kendrick Lamar". When the "R&B" button is pressed, it could show "Usher". Pressing "Pop" might display "Ariana Grande", and "Country" will bring up "Luke Bryan". And when the "Afrobeats" button is clicked, it will reveal "Tems".

---


## Challenge
📻 Artist Radio Selector

**Objective:** Create a feature allowing users to select their favorite artist-based radio station and tune in.

**Tasks:**

1. Draft a component named `RadioSelector.js` inside the `components` folder.
2. Inside `RadioSelector`, display radio button options for artists: Rod Wave, Brent, Drake, and SZA.
3. Add a "Tune In" button beneath the radio options.
4. When the "Tune In" button is clicked, it should display the selected artist's radio station.

**Hint:** Familiarize yourself with how radio buttons work in HTML to capture the user's selection.

**End Result:** Users can choose from a set of radio buttons, each representing an artist. After selecting an artist like "Drake" and pressing the "Tune In" button, a message should display saying "Now playing: Drake Radio".
