# video_streamer
To use:
- Create a folder "videos"
- drop a video in it
- Update line 14-15 (in index.js) with the proper file name: 
const videoPath = "videos/finalEdit.mp4";
const videoSize = fs.statSync("videos/finalEdit.mp4").size;
- type $npm i
- type $npm start

Enjoy the show