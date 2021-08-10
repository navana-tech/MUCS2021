<style>

#graph li
{
   position:absolute;	
   list-style:none;
   background:lightblue;
   width:40px;
   text-align:center;
   border:1px solid black;
   visibility: hidden;
   background-image:url(bar-shaded.png);
   background-repeat:repeat-y;
}

</style>



<br>
<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Registrations So Far!!</h1>
  </div>
</div>

<br>
<br>

<div id="graph">
  200<br /> <br /> <br /> 150 <br /> <br /> <br /> 100 <br /> <br /> <br /> 50
<ul>  
  <li>30:2007</li>
  <li>40:2008</li>
  <li>80:2009</li>
  <li>14:2010</li>
</ul>
</div>

<div id="labels">Years : </div>

<script>

function makeGraph()
{
    var container = document.getElementById("graph");
    var labels = document.getElementById("labels");
    var dnl = container.getElementsByTagName("li");
    for(var i = 0; i < dnl.length; i++)
    {
        var item = dnl.item(i);
        var value = item.innerHTML;
        var content = value.split(":");
        value = content[0];
        item.style.height=value + "px";
        item.style.top=(199 - value) + "px";
        item.style.left = (i * 50 + 20) + "px";
        item.style.height = value + "px";
        item.innerHTML = value;
        item.style.visibility="visible";	
        left = (i * 50 + 58) + "px";
        labels.innerHTML = labels.innerHTML + 
           "<span style='position:absolute;top:-16px;left:"+ 
           left+";background:blue'>year</span>";
    }	
}

window.onload=makeGraph;


</script>