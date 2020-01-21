---
permalink: /
title: "Home"
excerpt: "About me"
author_profile: true
---
On this website you can download my self-made programs.
<br>There's nothing more to do here, but you can look at this thing and listen to the Nyan Cat Theme.


<span id="count-up">0:00</span>
<script>
	  var min    = 0;
      var second = 00;
      var zeroPlaceholder = 0;
      var counterId = setInterval(function(){
                        countUp();
                      }, 1000);

      function countUp () {
          second++;
          if(second == 59){
            second = 00;
            min = min + 1;
          }
          if(second == 10){
              zeroPlaceholder = '';
          }else
          if(second == 00){
              zeroPlaceholder = 0;
          }

          document.getElementById("count-up").innerText = min+':'+zeroPlaceholder+second;
      }
</script>  
  
  
<br><img src="/files/wabbl.gif" alt="Wabbl" width="320" height="229">
<br>
<audio controls>
  <source src="/files/nyan.mp3" type="audio/mp3">
  <source src="/files/nyan.mp3" type="audio/mp3">
Your browser does not support the audio element.
</audio>

