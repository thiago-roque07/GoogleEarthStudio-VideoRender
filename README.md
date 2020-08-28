# Google Earth Studio  Video Render and Logomark Remover

### Welcome!
##### Google Earth Studio is an amazing new tool from Google where you can create amazing animated videos using Google Earth framework
##### If you want to learn more, you might checkout this amazing introductory video: https://www.youtube.com/watch?v=OYg7dH2UbOU

Google Earth Studio (GES) renders your animation into a set of images (frames) where it is up to you to transform this set of frames into a single video.

Another point is the Google Earth logomark stamped in every frame.
Luckly, GES alows you to decide where do you want the logomark to stay (top lefth, centered, botton right, etc...)

Thinking about that, I made this simple Jupyter Notebook that takes two sets of rendered images and combine them in certain way to remove the logomark and then, render all images into a .mp4 video.

#### Instructions:
- Render your GES animation setting the logomark to "top left"
- Render again the same animation with the logomark set to a different position (like "botton right")
- Save both sets of images to the same folder
- Change the folder path, file names and number of frames in the Jupyter Notebook
- Enjoy!

