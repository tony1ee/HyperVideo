# HyperVideo
Video, but with hyperlink!

## Idea
The idea of HyperVideo is adding non-linear playback functionality to normal video, by using hyperlinks inside video.
## HyperVideo Editor
![](editor.gif)
- Import primary and secondary video
- create hyperlink on secondary video at specified frame No. 
- link spatiotemporal area on primary video to hyperlink
  - draw first bounding box at first appearance
  - draw last bounding box at last appearance
  - bounding boxes in between will be interpolated automatically

## HyperVideo Player
![](player.gif)
1. click on the bounding boxes (hyperlinks) when playing video
2. target video at target frame will start playing
