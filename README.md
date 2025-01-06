# Simple Music Player

A simple, stylish, and responsive music player built using HTML, CSS, and JavaScript. It allows users to play and control music streams with a beautiful & simple UI and useful features.

## Features

- **Play/Pause Control:** 
  - Users can easily play and pause the current track using a single button. 
  - The button changes dynamically to reflect the current state of the player (Play or Pause).

- **Track Navigation:**
  - **Next Track:** Users can skip to the next track in the playlist.
  - **Previous Track:** Users can go back to the previous track in the playlist.
  
- **Volume Control:**
  - **Volume Slider:** Users can adjust the volume using a slider, with smooth volume transitions.

- **Responsive Design:**
  - The player is fully responsive, meaning it adjusts to different screen sizes, ensuring it works well on both desktop and mobile devices.

- **Track Information Display:**
  - The current track's title is displayed dynamically.
  - The track's thumbnail image is shown and changes automatically when switching tracks.

- **Customizable Playlist:**
  - The music player can handle multiple tracks, and you can easily add or change tracks in the JavaScript array(explained below).

- **Styled with Background and Buttons:**
  - The player has a custom background with a blur effect and styled buttons for a modern look.
  - The buttons and volume slider are designed with smooth transitions and hover effects to improve user interaction.

## How to Use

1. Download the repository.
2. Open the `index.html` file in your preferred web browser to start using the music player.
3. Use the control buttons to play, pause, skip, or go back to the previous track.
4. Adjust the volume with the slider, click the volume icon to mute/unmute.

## How to Add New Tracks

To add new tracks to the playlist:
1. Open the `index.html` file.
2. Find the `tracks` array in the JavaScript section.
3. Add a new track object to the array with the `title`, `src` (audio stream URL), and `thumbnail` (image URL).

Example:
```javascript
{
    title: "New Track Name",
    src: "http://yourstreamurl.com/track.mp3",
    thumbnail: "http://yourimageurl.com/thumbnail.jpg"
},
```
## Technologies Used

- **HTML:** For creating the structure of the player.
- **CSS:** For styling the player and making it responsive.
- **JavaScript:** For adding functionality like play/pause, track navigation, volume control, and more.
