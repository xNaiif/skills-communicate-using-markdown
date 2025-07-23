# Daily Learning
## Morning Planning
<img alt="Cloudy morning" src="./images/cloud.jpg" width="100" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
# The following ffmpeg command applies a series of filters to the input video:
# - negate: Inverts the colors of the video.
# - hue=h=180: Shifts the hue by 180 degrees, effectively rotating the color wheel.
# - eq=contrast=1.2:saturation=1.1: Adjusts the contrast (1.2x) and saturation (1.1x) of the video.
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
