---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
---

<head>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-157295670-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-157295670-1');
</script>
</head>


<center><br>You wastend</center> 
<center><br></center>
<center><span id="seconds"></span></center>
<center><br>seconds of your life on this website.</center>


<script>
var sec = 0;
    function pad ( val ) { return val > 9 ? val : "0" + val; }
    setInterval( function(){
        document.getElementById("seconds").innerHTML=pad(++sec%9999999999999999999999999999999);
    }, 1000);
</script>
  
  
<center><br><img src="/files/wabbl.gif" alt="Wabbl" width="320" height="229"></center>
<br>
<audio controls loop>
  <source src="/files/nyan.mp3" type="audio/mp3">
  <source src="/files/nyan.mp3" type="audio/mp3">
Your browser does not support the audio element.
</audio>



