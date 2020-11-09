<!DOCTYPE HTML>
<html>

<body>

  <p>Before the script...</p>

  <script>
    alert( 'Welcome to ALS!' );
  </script>

<p id="AlicesBoard"> Alice's board </p>
<p id="theatres">Theatres: </p>
<p id="BobsBoard"> Bob's board </p>

<p id="BobsHand"> Bob's hand </p>

  <button onclick="startFunc()"> Start </button>

  <script> 
    function startFunc(){
        document.getElementById("theatres").innerHTML = "AIR \t | \t LAND \t | \t SEA";
        document.getElementById("BobsHand").innerHTML = "[6 cards]";
    }
    </script>

</body>

</html>
