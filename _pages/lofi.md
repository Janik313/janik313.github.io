---
layout: default
title: "LoFi Stream"
permalink: /lofi/
author_profile: false
---
<html lang="en-US">
<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-157295670-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-157295670-1');
</script>
<br>
<br>
<center><iframe src="https://www.youtube.com/embed/5qap5aO4i9A?autoplay=1"
   width="560" height="315" frameborder="0" allowfullscreen></iframe></center>
<br>
<center><br>You spend</center> 
<center><br></center>
<center><span id="seconds"></span></center>
<center><br>seconds listening to this lofi stream.</center>

<script>
var sec = 0;
    function pad ( val ) { return val > 9 ? val : "0" + val; }
    setInterval( function(){
        document.getElementById("seconds").innerHTML=pad(++sec%9999999999999999999999999999999);
    }, 1000);
</script>