---
layout: default
center: true
---

![banner](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/v9n347ozi23rutgapotd.jpeg)
###### Alyxia Starts on March 22
---

<h2 id="demo"></h2>


<script>
var countDownDate = new Date("Mar 22, 2021 13:00:00").getTime();

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
    document.getElementById("demo").innerHTML = "Alyxia CTF Will Start Soon. Please refresh the page to get access. Also join our discord";
  }
}, 1000);
</script>
<footer>
  <p>Author: Alyxia Contributors</p>
  <p><a href="mailto:alyxiacontest@gmail.com">AlyxiaContest@gmail.com</a></p>
</footer>
