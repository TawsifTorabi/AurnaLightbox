


# Aurna Lightbox

#### Simple HTML Lightbox for Iframes, HTML and Confirm Dialogue Boxes. 
A Simple Javascript HTML Dynamic Lightbox for Webpages to Show Images, Iframes. No library Required.

#### No JQuery required, simple and lite script. Easy to Use.

**Responses to Keyboard Events (Pressing ESC will hide Light Box)**  
Hiding an Iframe will continue to run the Iframe in the background untill a new`aurnaIframe()` is called. This might sounds like a bug, but some people might want to process Ajax Form Submission or other processes run in the background untill it is completed. If you have control over the Iframed page, than you can call `parent.hideIframe()` to call the parent page to hide the Iframe.

## Demo

Demo

Code

Click This Button to open CNN Lite!

```
<button onclick="aurna('https://lite.cnn.com/en')">Click Me to open CNN Lite!</button>
```

[Click This Anchor to open CNN Lite!](javascript:aurnaIframe('https://lite.cnn.com/en'))  

```
<a href="javascript:aurna('https://lite.cnn.com/en')">Click This Anchor to open CNN Lite!</a>
```

[Click This Anchor to open Demo with Hide Button!](javascript:aurnaIframe('demo.html'))

```
<a href="javascript:aurna('https://lite.cnn.com/en')">Click This Anchor to open CNN Lite!</a>
```
