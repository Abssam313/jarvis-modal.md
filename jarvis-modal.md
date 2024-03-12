# Jarvis Modal

<div id="modal-jarvis" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h2>Jarvis Project</h2>
    <p>Jarvis is an open-source voice assistant project built with Python and TensorFlow.</p>
    <h3>Features</h3>
    <ul>
      <li>Speech recognition and synthesis</li>
      <li>Natural language processing</li>
      <li>Integration with various APIs and services</li>
    </ul>
    <h3>Getting Started</h3>
    <p>To get started with the Jarvis project, follow these steps:</p>
    <ol>
      <li>Clone the repository to your local machine</li>
      <li>Install the required dependencies</li>
      <li>Configure the project settings</li>
      <li>Run the project</li>
    </ol>
    <p>For more information, check out the <a href="https://github.com/jarvis-org/jarvis/blob/main/README.md">README file</a>.</p>
  </div>
</div>

<script>
  // Get the modal element
  var modal = document.getElementById("modal-jarvis");

  // Get the <span> element that closes the modal
  var span = document.getElementsByClassName("close")[0];

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

<style>
  /* The Modal (background) */
  .modal {
    display: none; /* Hidden by default */
    position: fixed; /* Stay in place */
    z-index: 1; /* Sit on top */
    padding-top: 100px; /* Location of the box */
    left: 0;
    top: 0;
    width: 100%; /* Full width */
    height: 100%; /* Full height */
    overflow: auto; /* Enable scroll if needed */
    background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
  }

  /* Modal Content */
  .modal-content {
    background-color: #fefefe;
    margin: auto;
    padding: 20px;
    border: 1px solid #888;
    width: 80%;
    max-width: 800px;
  }

  /* The Close Button */
  .close {
    color: #aaa;
    float: right;
    font-size: 28px;
    font-weight: bold;
  }

  .close:hover,
  .close:focus {
    color: black;
    text-decoration: none;
    cursor: pointer;
  }
</style>
