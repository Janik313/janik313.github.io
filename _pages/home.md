---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
---
On this website you can download my self-made programs.
<br>There's nothing more to do here, but you can look at this thing and listen to the Nyan Cat Theme.
<br>You wastend
  <span id="seconds">0</span>

  <script>
    const seconds = document.querySelector("#seconds")
    let count = 0;

    const renderTimer = () => {
      count += 1;
      seconds.innerHTML = (count % 99999999999999999999999999999999999999999999999999999999999999999999999999).toString().padStart(1, "0");
    }

    const timer = setInterval(renderTimer, 1000)
  </script>
  seconds of your life on this website.
<br><img src="/files/wabbl.gif" alt="Wabbl" width="320" height="229">
<br>
<audio controls>
  <source src="/files/nyan.mp3" type="audio/mp3">
  <source src="/files/nyan.mp3" type="audio/mp3">
Your browser does not support the audio element.
</audio>