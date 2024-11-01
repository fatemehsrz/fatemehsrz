:octocat: Hi,  I'm preparing a guide on ML concepts [here](https://github.com/fatemehsrz/ML_Concepts) <br>
:octocat: More about me on my homepage [here](https://fatemehsrz.github.io/) 

<script>
function clickCounter() {
  if (typeof(Storage) !== "undefined") {
    if (localStorage.clickcount) {
      localStorage.clickcount = Number(localStorage.clickcount)+1;
    } else {
      localStorage.clickcount = 1;
    }
    document.getElementById("result").innerHTML = "You have clicked the button " + localStorage.clickcount + " time(s).";
  } else {
    document.getElementById("result").innerHTML = "Sorry, your browser does not support web storage...";
  }
}
</script>






