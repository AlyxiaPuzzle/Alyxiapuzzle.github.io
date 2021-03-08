# CountDown to Alyxia CTF

<p id="demo"></p>

<script>
var countDownDate = new Date("Mar 22, 2021 13:00:00").getTime();

var x = setInterval(function() {

  var now = new Date().getTime();

  var distance = countDownDate - now;

  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "Alyxia CTF Will Start Soon. Please refresh the page to get access. Also join our discord:";
  }
}, 1000);
</script>
