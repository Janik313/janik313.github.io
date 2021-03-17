---
layout: none
title: "Sitz Florian im Moment in Unterhosen am PC?"
permalink: /Unterhose/
author_profile: false
---
<html lang="de-CH">
<head>
 <title>Sitz Florian im Moment in Unterhosen am PC?</title>
 <style type="text/css">
  .container {
   margin:0 auto; /* this will center the page */
   width:80%; /*  use your width here */
}
.responsive {
width: 100%;
height: 0;
padding-bottom: 56.25%;
position: relative;
}
.responsive iframe {
position: absolute;
width: 100%;
height: 85%;
}
 </style>
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-157295670-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}

  gtag('js', new Date());
  gtag('config', 'UA-157295670-1');
</script>
</head>
var basicTimeline = anime.timeline({
  autoplay: false
});

var pathEls = $(".check");
for (var i = 0; i < pathEls.length; i++) {
  var pathEl = pathEls[i];
  var offset = anime.setDashoffset(pathEl);
  pathEl.setAttribute("stroke-dashoffset", offset);
}

basicTimeline
  .add({
    targets: ".text",
    duration: 1,
    opacity: "0"
  })
  .add({
    targets: ".button",
    duration: 1300,
    height: 10,
    width: 300,
    backgroundColor: "#2B2D2F",
    border: "0",
    borderRadius: 100
  })
  .add({
    targets: ".progress-bar",
    duration: 2000,
    width: 300,
    easing: "linear"
  })
  .add({
    targets: ".button",
    width: 0,
    duration: 1
  })
  .add({
    targets: ".progress-bar",
    width: 80,
    height: 80,
    delay: 500,
    duration: 750,
    borderRadius: 80,
    backgroundColor: "#71DFBE"
  })
  .add({
    targets: pathEl,
    strokeDashoffset: [offset, 0],
    duration: 200,
    easing: "easeInOutSine"
  });

$(".button").click(function() {
  basicTimeline.play();
});

$(".text").click(function() {
  basicTimeline.play();
});

<link href="https://fonts.googleapis.com/css?family=Poppins:600" rel="stylesheet">


<main>
  <div class="button">
    <div class="text">Submit</div>
  </div>
  <div class="progress-bar"></div>
  <svg x="0px" y="0px"
   viewBox="0 0 25 30" style="enable-background:new 0 0 25 30;">
    <path class="check" class="st0" d="M2,19.2C5.9,23.6,9.4,28,9.4,28L23,2"/>
  </svg>
</main>
