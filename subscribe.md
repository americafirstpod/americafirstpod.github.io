---
layout: default
title: Subscribe to the America First Podcast
description: Instructions to subscribe to the America First Podcast
---


## To Listen to America First on your Favorite Podcasting App:

1.  <button style="color: rgba(0, 0, 255, 1); background-color: rgba(0, 0, 0, 1); border-color: rgba(0, 0, 0, 0); margin-bottom: 0; margin-left: 0; padding: 0.1rem; margin-top: 0;" id="copyButton" data-text="https://americafirstpod.github.io/feed.xml"><u>Click here</u></button> to copy the RSS feed link
2.  Open your preferred podcasting app
3.  Paste the RSS feed link in the RSS feed subscription feature
<br>
<br>
<br>
<br>
<br>
### FAQs:
*  RSS link subscription is available on most major podcast apps, including Apple Podcasts, Overcast, and Pocket Casts.
*  RSS link subscription is not possible on Spotify.
*  The raw RSS feed is available [here]("./feed.xml").

[back](./)

<script>
document.getElementById("copyButton").addEventListener("click", function() {
  const textToCopy = this.getAttribute("data-text");

  // Modern clipboard API
  navigator.clipboard.writeText(textToCopy).then(() => {
    alert("Copied to clipboard!");
  }).catch(err => {
    console.error("Failed to copy: ", err);
  });
});
</script>
