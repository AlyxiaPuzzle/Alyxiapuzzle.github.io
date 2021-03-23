---
layout: default
center: true
---

![banner](https://cdn.discordapp.com/attachments/823505640558952448/823507827465256990/Alyxia.jpg)
---
##### Alyxia Starts on March 22

<h2 id="demo"></h2>


<script>
var countDownDate = new Date("Mar 23, 2021 13:00:00").getTime();

var x = setInterval(function() {

  var now = new Date().getTime();

  var distance = countDownDate - now;

  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("demo").innerHTML = "Alyxia will start in " + days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "Alyxia has started! Go to <a>https://alyxiapuzzle.github.io/docs</a> to get started";
  }
}, 1000);
</script>
<footer>
  <p>Author: Alyxia Contributors</p>
  <p><a href="mailto:alyxiacontest@gmail.com">AlyxiaContest@gmail.com</a></p>
</footer>
