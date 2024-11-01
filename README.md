:octocat: Hi,  I'm preparing a guide on ML concepts [here](https://github.com/fatemehsrz/ML_Concepts) <br>
:octocat: More about me on my homepage [here](https://fatemehsrz.github.io/) 

 <button id="btn">Click Here!</button>
    <p>
        Button Clicked <span id="display">0</span> Times
    </p>
    <script type="text/javascript">
        let count = 0;
        let btn = document.getElementById("btn");
        let disp = document.getElementById("display");
         
        btn.onclick = function () {
                    count++;
        disp.innerHTML = count;
        }
    </script>




