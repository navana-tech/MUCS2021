
<br>
<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Tentative Program</h1>
  </div>
</div>
<br>
<br>
<style type="text/css">
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
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.4); /* Black w/ opacity */
}
/* Modal Content */
.modal-content {
  background-color: #fefefe;
  margin: auto;
  padding: 20px;
  border: 1px solid #888;
  width: 80%;
}
/* The Close Button */
.close {
  color: #aaaaaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
}
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-5e9u{background-color:#ffccc9;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-cvsa{background-color:#fd6864;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-t7s9{background-color:#cbcefb;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-6h8h{background-color:#34cdf9;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-gp9k{background-color:#ffce93;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-mqa1{border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-njcc{background-color:#9aff99;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-5cm8{background-color:#ffffc7;border-color:#000000;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-mqa1"></th>
    <th class="tg-mqa1">10.00-10.30</th>
    <th class="tg-mqa1">10.30-11.00</th>
    <th class="tg-mqa1">11.00-11.30</th>
    <th class="tg-mqa1">11.30-12.00</th>
    <th class="tg-mqa1">12.00-12.30</th>
    <th class="tg-mqa1">12.30-13.00</th>
    <th class="tg-mqa1">13.00-13.30</th>
    <th class="tg-mqa1">13.30-14.00</th>
    <th class="tg-mqa1">14.00-14.30</th>
    <th class="tg-mqa1">14.30-15.00</th>
    <th class="tg-mqa1">15.00-15.30</th>
    <th class="tg-mqa1">15.30-16.00</th>
    <th class="tg-mqa1">16.00-16.30</th>
    <th class="tg-mqa1">16.30-17.00</th>
    <th class="tg-mqa1">17.00-17.30</th>
    <th class="tg-mqa1">17.30-18.00</th>
    <th class="tg-mqa1">18.00-18.30</th>
    <th class="tg-mqa1">18.30-19.00</th>
    <th class="tg-mqa1">19.00-19.30</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-mqa1">12th Aug</td>
    <td class="tg-mqa1">Intro</td>
    <td onclick="myFunction(this)" id="prasanna" class="tg-6h8h" colspan="6">S R Mahadev Prasanna</td>
    <td class="tg-mqa1">BREAK</td>
    <td class="tg-t7s9" colspan="2">Sri Garimella</td>
    <td class="tg-5e9u" colspan="2">Anurag Dwarakanath</td>
    <td class="tg-mqa1">BREAK</td>
    <td class="tg-cvsa" colspan="4">Presentation by Challenge Participants - Subtask1</td>
    <td class="tg-njcc" colspan="2">Samuel Thomas</td>
  </tr>
  <tr>
    <td class="tg-mqa1">13th Aug</td>
    <td class="tg-mqa1"></td>
    <td class="tg-cvsa" colspan="4">Presentation by Challenge Participants - Subtask2</td>
    <td class="tg-mqa1">BREAK</td>
    <td class="tg-gp9k" colspan="6">S UMESH</td>
    <td class="tg-mqa1" colspan="2">Winner Announcement</td>
    <td class="tg-5cm8" colspan="5">Shinji Watanabe</td>
  </tr>
</tbody>
</table>

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
function myFunction(x) {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>