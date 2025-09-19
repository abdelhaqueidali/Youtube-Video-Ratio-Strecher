# YouTube Aspect Ratio Player

The YouTube Aspect Ratio Player is a web-based tool that empowers users to adjust the aspect ratio of YouTube videos, ensuring they display optimally by stretching or compressing them to fit specific ratios while filling the browser window. Unlike the standard YouTube player, which locks videos into a fixed 16:9 ratio regardless of their original dimensions, this tool offers flexibility with 16:9 (widescreen) and 4:3 (traditional TV format) options, cropping excess content as needed.

[Youtube-Video-Ratio-Stracher is Online!](https://abdelhaqueidali.github.io/Youtube-Video-Ratio-Strecher/), this player addresses the common issue of mismatched aspect ratios in video playback.

## Features

- **Custom Aspect Ratios**: Switch between 16:9 and 4:3 ratios with a single click, or reset to YouTube's default 16:9.
- **URL Loading**: Paste any YouTube URL to load a video, with support for multiple formats (e.g., `youtube.com/watch?v=`, `youtu.be/`).
- **Full-Window Display**: Videos fill the entire browser window, with excess content cropped using `overflow: hidden`.
- **Smooth Transitions**: Aspect ratio changes animate smoothly with CSS transitions.
- **Responsive Design**: Adapts to different screen sizes and devices.
- **User-Friendly Controls**: Buttons for ratio selection and an input field with Enter key support for loading videos.

## How It Works

The tool uses a simple interface where you paste a YouTube URL into an input field to load a video. Once loaded, buttons allow you to toggle between 16:9 and 4:3 aspect ratios or reset to the default. The video content scales dynamically using CSS `transform: scaleX()` and `scaleY()`, a technique, ensuring the video stretches or compresses to the selected ratio. The container’s `overflow: hidden` property handles cropping, keeping the video maximized within the browser window.

Built with HTML, CSS, and JavaScript, it leverages the [YouTube IFrame Player API](https://developers.google.com/youtube/iframe_api_reference) for video embedding and control. This approach enhances the simplicity and effectiveness seen in [Youtube-Video-Ratio-Stracher](https://github.com/abdelhaqueidali/Youtube-Video-Ratio-Stracher), adding a custom UI, reset functionality, and improved usability features.
