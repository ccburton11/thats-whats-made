# That's What's Made

A party game for any number of players. Watch a muted, random clip from a
*How It's Made* compilation and shout out what's being manufactured. First to
guess right gets the point &mdash; first to the target score wins.

**[Play it here](https://YOUR_USERNAME.github.io/thats-whats-made/)** *(update this link after GitHub Pages is enabled)*

## How to play

1. Paste a YouTube link to a *How It's Made* compilation (a long compilation
   works best &mdash; the default is an 8-hour one). Add your players and pick
   a points-to-win target.
2. Hit **Start Game**. The clip plays muted from a random moment.
3. Whoever shouts the correct answer first gets pointed to by the scorekeeper
   &mdash; tap their name on the scoreboard to award the point.
4. Hit **Reveal Sound** any time to unmute and let the narrator confirm the
   answer.
5. **Skip** jumps to a new random moment with no point awarded, if nobody can
   guess. **Next** appears after a point is awarded and moves on to a new
   segment.
6. First player to the target score wins. **Play Again** keeps the same
   players and video; **New Game** starts fresh.

Each new segment is chosen so it's at least 400 seconds away from every
previously used moment in that game, so you won't land back inside a segment
you've already seen.

## Notes

- One shared screen, no backend &mdash; pure static site (`index.html`) using
  the YouTube IFrame Player API. Refreshing the page resumes the game in
  progress.
- Clips are streamed live from YouTube; nothing is downloaded or re-hosted.
  All video content belongs to the Science Channel and *How It's Made*.
- Because the YouTube IFrame API requires HTTPS, this only works when served
  over a real web server (e.g. GitHub Pages) &mdash; not by opening
  `index.html` directly from disk.
