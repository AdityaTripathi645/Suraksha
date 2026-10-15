SURAKSHA NER - preview page

Files
  index.html        the whole page (CSS inside, no build step)
  assets/poster.jpeg  poster image linked from the footer

Hosting
  Upload both items to the web root of the URL on the poster.

Replacing it with the real project later
  1. Build the real app (npm run build).
  2. Delete index.html and the assets folder from the host.
  3. Upload the contents of the app's dist/ folder to the same location.
  The URL stays the same, so the poster QR code keeps working.

Changing the video
  In index.html, find "youtube-nocookie.com/embed/" and change the video ID.
