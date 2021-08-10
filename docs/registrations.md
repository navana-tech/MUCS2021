<script src="https://cdn.anychart.com/releases/8.0.0/js/anychart-base.min.js"></script>
<br>
<br>
<br>
<br>
<br>



<div id="container"></div>

<style>
html, body, #container {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
}
</style>

<script>

anychart.onDocumentReady(function() {

  // set the data
  var data = {
    header: ["Designation", "No. of registrations"],
    rows: [
      ["Students", 216],
      ["Faculty", 86],
      ["Industry", 21]
  ]};

  // create the chart
  var chart = anychart.column();

  // add data
  chart.data(data);

  // set the chart title
  chart.title("Total No. of Registrations so far!");

  // draw
  chart.container("container");
  chart.draw();
});

</script>