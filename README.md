# Slider-Smooth-Animation
Slider Smooth Animation
A smooth collection slider with fade-in animation and hover interaction. Built with vanilla HTML, CSS, and JavaScript.
Live Demo: View Live

<table>
  <tr>
    <td><img src="./git-details/screenshot1.png" alt="slider screenshot"/></td>
    <td><img src="./git-details/screenshot2.png" alt="slider screenshot"/></td>
  </tr>
</table>

Features

Auto-sliding every 3 seconds
Smooth fade-in animation with slight slide effect
Hover on list pauses the slider
Hover on individual item activates that item and its image
Active item highlighted with full color

Tech Stack

HTML
CSS (keyframe animation, nth-child sizing)
Vanilla JavaScript (setInterval, classList, DOM manipulation)

How to Use
bashgit clone https://github.com/mdsibgatullah/Slider-Smooth-Animation.git
cd Slider-Smooth-Animation
Then open index.html in your browser.
How It Works
Page load → 4th item active → slider starts
    ↓
Every 3s → first item moves to end → 4th item stays active
    ↓
Mouse enter list → slider pauses
    ↓
Hover on item → that item + image becomes active
    ↓
Mouse leave list → slider resumes