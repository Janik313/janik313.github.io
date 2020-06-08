---
layout: none
title: "Merci Herr Adank"
permalink: /MerciAdank/
author_profile: false
---
<html lang="de-CH">
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
<center><iframe width="1280" height="720" src="https://www.youtube.com/embed/I4nnAYby8bU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
<center><br>You spent</center> 
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