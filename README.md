<hmtl>
  
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> Jyrin Galleria </title> 
  <link rel="stylesheet" href="style.css">
  


  <h1> Jyrtsi's Galleria </h1>

<body>
      <a href="https://twitter.com/15G_Priced_Lamp"> Twitter </a>
      <a href="https://www.instagram.com/jyrtsiii/"> Instagram </a>
      <a href="https://www.twitch.tv/jyrtsiii"> Twitch </a>
      
      
    
     <div id="box1">
       <a href="https://twitter.com/15G_Priced_Lamp" target="_blank"><img src="../Jyrin-Galleria/twitterlogo.png" alt="Twitter"></a>
      </div>
      
    <div id="box2">
      <a href="https://www.instagram.com/jyrtsiii/" target="_blank"><img src="../Jyrin-Galleria/instagramlogo.png" alt="instagram"></a>
      </div>
      
    <div id="box3">
      <a href="https://www.twitch.tv/jyrtsiii" target="_blank"><img src="../Jyrin-Galleria/twitchlogo.jpg" alt="Twitch"></a>
      </div>

  
  
  
  <h2>Modal Example</h2>

<!-- Trigger/Open The Modal -->
<button id="myBtn">Open Modal</button>

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- Modal content -->
  <div class="modal-content">
    <span class="close">&times;</span>
    <p>Some text in the Modal..</p>
  </div>

</div>

<script>
// Get the modal
var modal = document.getElementById("myModal");

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal 
btn.onclick = function() {
  modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>


</body>
  
</hmtl>
