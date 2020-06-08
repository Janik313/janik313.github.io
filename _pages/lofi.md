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
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=0.5">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
<br>
<br>
<div class="embed-responsive embed-responsive-16by9">
<center><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/5qap5aO4i9A?autoplay=1"
   allowfullscreen></iframe></center>
   </div>
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