# getUserMedia constraints test case

Uses the [WebRTC Adapter](https://github.com/webrtc/adapter) for a consistent API.

From: https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia

**"An application can request the camera and microphone capabilities it needs and wants, 
using additional constraints... The keywords min, max, and exact are inherently mandatory..."**

Unfortunately in Samsung Internet, while the ideal/max `width` constraint is observed
and can give a smaller video size (e.g. max set to 300px gives a video width of 240 
instead of default 480), the ideal and max `height` appears to be ignored.

### Chrome:

<img src="screenshot-chrome.png?raw=true" alt="Chrome Screenshot" width="400px"/>

### Samsung Internet:

<img src="screenshot-sbrowser.png?raw=true" alt="Samsung Internet Screenshot" width="400px"/>
