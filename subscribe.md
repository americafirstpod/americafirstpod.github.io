---
layout: default
title: Subscribe to the America First Podcast
description: Instructions to subscribe to the America First Podcast
---

## To Listen to America First on your Favorite Podcasting App:

1.  <button style="margin-bottom: 0; margin-left: 0; padding: 0.1rem; margin-top: 0;" id="copyButton" data-text="https://americafirstpod.github.io/feed.xml">Click here</button> to copy the RSS feed link
2.  Open your preferred podcasting app
3.  Paste the RSS feed link in the RSS feed subscription feature

<a href="https://americafirstpod.github.io/feed.xml" class="btn">Subscribe to the America First Podcast</a>

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
