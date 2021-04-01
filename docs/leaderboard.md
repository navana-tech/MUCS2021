<style>
* {
  box-sizing: border-box;
}

.row {
  margin-left:-5px;
  margin-right:-5px;
}
  
.column {
  float: left;
  width: 50%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}

.vl {
  border-left: 6px solid green;
  height: 500px;
}


<style>
body {font-family: Arial;}

/* Style the tab */
.tab {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 17px;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #ddd;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #ccc;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
.tabcontent2 {
  display: none;
  padding: 6px 12px;
  border: 1px solid #ccc;
  border-top: none;
}
</style>


</style>


<br>
<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Leaderboard (Updated 31/03/2021 20:55 IST)</h1>
  </div>
</div>

<br>

<div class="tab">
  <button class="tablinks" onclick="openCity(event, 'subtask1')">Subtask1</button>
  <button class="tablinks" onclick="openCity(event, 'subtask2')">Subtask2</button>
</div>

<div id="subtask1" class="tabcontent">
<h3>Subtask1</h3>

<div class="tab">
  <button class="tablinks2" onclick="openCity2(event, 'subtask1_l1')">Leaderboard 1</button>
  <button class="tablinks2" onclick="openCity2(event, 'subtask1_l2')">Leaderboard 2</button>
</div>

<div id="subtask1_l1" class="tabcontent2">
<p style="font-size:16.5px;">Ranks are determined on the basis of average WER.:</p>

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>#</th>
      <th>Team Name</th>
      <th>Hindi (% WER)</th>
      <th>Marathi (% WER)</th>
      <th>Oriya (% WER)</th>
      <th>Tamil (% WER)</th>
      <th>Telugu (% WER)</th>
      <th>Gujarati (% WER)</th>
      <th>Average (% WER)</th>
    </tr>
    <tr>
      <td>1</td>
      <td>EthereumMiner</td>
      <td>17.54</td>
      <td>20.15</td>
      <td>19.99</td>
      <td>28.52</td>
      <td>26.08</td>
      <td>20.11</td>
      <td>22.06</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Uniphore</td>
      <td>24.35</td>
      <td>18.58</td>
      <td>28.67</td>
      <td>18.58</td>
      <td>29.26</td>
      <td>23.48</td>
      <td>23.82</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Ekstep</td>
      <td>12.24</td>
      <td>39.74</td>
      <td>27.1</td>
      <td>27.2</td>
      <td>22.43</td>
      <td>30.65</td>
      <td>26.56</td>
    </tr>
    <tr>
      <td>4</td>
      <td>GoVivace</td>
      <td>25.93</td>
      <td>28.45</td>
      <td>33.73</td>
      <td>31.99</td>
      <td>28.69</td>
      <td>23.97</td>
      <td>28.79</td>
    </tr>
    <tr>
      <td>5</td>
      <td>TCS-SpeechNLP</td>
      <td>19.8</td>
      <td>37.09</td>
      <td>35.33</td>
      <td>26.49</td>
      <td>27.06</td>
      <td>28.75</td>
      <td>29.09</td>
    </tr>
    <tr>
      <td>6</td>
      <td>IIITHSPL</td>
      <td>31.11</td>
      <td>33.8</td>
      <td>37.19</td>
      <td>35.03</td>
      <td>17.0</td>
      <td>26.94</td>
      <td>30.18</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Lottery</td>
      <td>19.81</td>
      <td>58.84</td>
      <td>20.61</td>
      <td>30.87</td>
      <td>28.36</td>
      <td>23.25</td>
      <td>30.29</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Bhavik Vachhani</td>
      <td>27.78</td>
      <td>33.05</td>
      <td>34.57</td>
      <td>33.01</td>
      <td>30.08</td>
      <td>28.22</td>
      <td>31.12</td>
    </tr>
    <tr>
      <td>9</td>
      <td>TUTU</td>
      <td>32.35</td>
      <td>43.88</td>
      <td>34.16</td>
      <td>27.7</td>
      <td>30.25</td>
      <td>25.32</td>
      <td>32.27</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>10</td>
      <td>Baseline</td>
      <td>37.2</td>
      <td>29.04</td>
      <td>38.46</td>
      <td>34.09</td>
      <td>31.44</td>
      <td>26.15</td>
      <td>32.73</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Jio Speech</td>
      <td>35.53</td>
      <td>36.33</td>
      <td>38.55</td>
      <td>33.69</td>
      <td>31.14</td>
      <td>24.79</td>
      <td>33.34</td>
    </tr>
    <tr>
      <td>12</td>
      <td>Nuronics</td>
      <td>38.02</td>
      <td>39.12</td>
      <td>48.4</td>
      <td>34.89</td>
      <td>33.11</td>
      <td>29.68</td>
      <td>37.23</td>
    </tr>
    <tr>
      <td>13</td>
      <td>Bytedance-SA</td>
      <td>27.63</td>
      <td>86.64</td>
      <td>27.45</td>
      <td>33.8</td>
      <td>31.78</td>
      <td>23.11</td>
      <td>38.4</td>
    </tr>
    <tr>
      <td>14</td>
      <td>SRI-B</td>
      <td>32.47</td>
      <td>76.27</td>
      <td>47.72</td>
      <td>27.97</td>
      <td>29.13</td>
      <td>30.17</td>
      <td>40.62</td>
    </tr>
    <tr>
      <td>15</td>
      <td>IITM-SMT-Lab</td>
      <td>17.8</td>
      <td>111.78</td>
      <td>32.21</td>
      <td>27.12</td>
      <td>28.11</td>
      <td>29.8</td>
      <td>41.14</td>
    </tr>
    <tr>
      <td>16</td>
      <td>Dheeyantra</td>
      <td>36.88</td>
      <td>42.7</td>
      <td>40.31</td>
      <td>64.02</td>
      <td>40.62</td>
      <td>33.6</td>
      <td>43.02</td>
    </tr>
    <tr>
      <td>17</td>
      <td>HAL101</td>
      <td>20.74</td>
      <td>96.75</td>
      <td>36.07</td>
      <td>37.95</td>
      <td>34.79</td>
      <td>34.08</td>
      <td>43.4</td>
    </tr>
    <tr>
      <td>18</td>
      <td>INDIGO-IITG</td>
      <td>62.26</td>
      <td>109.09</td>
      <td>51.44</td>
      <td>117.88</td>
      <td>119.72</td>
      <td>102.9</td>
      <td>93.88</td>
    </tr>
  </tbody>
</table>
</div>
<div id="subtask1_l2" class="tabcontent2">

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>#</th>
      <th>Team Name</th>
      <th>Hindi (% WER)</th>
      <th>Oriya (% WER)</th>
      <th>Tamil (% WER)</th>
      <th>Telugu (% WER)</th>
      <th>Gujarati (% WER)</th>
      <th>Average (% WER)</th>
    </tr>
    <tr>
      <td>1</td>
      <td>EthereumMiner</td>
      <td>17.54</td>
      <td>19.99</td>
      <td>28.52</td>
      <td>26.08</td>
      <td>20.11</td>
      <td>22.45</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Ekstep</td>
      <td>12.24</td>
      <td>27.1</td>
      <td>27.2</td>
      <td>22.43</td>
      <td>30.65</td>
      <td>23.92</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Lottery</td>
      <td>19.81</td>
      <td>20.61</td>
      <td>30.87</td>
      <td>28.36</td>
      <td>23.25</td>
      <td>24.58</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Uniphore</td>
      <td>24.35</td>
      <td>28.67</td>
      <td>18.58</td>
      <td>29.26</td>
      <td>23.48</td>
      <td>24.87</td>
    </tr>
    <tr>
      <td>5</td>
      <td>IITM-SMT-Lab</td>
      <td>17.8</td>
      <td>32.21</td>
      <td>27.12</td>
      <td>28.11</td>
      <td>29.8</td>
      <td>27.01</td>
    </tr>
    <tr>
      <td>6</td>
      <td>TCS-SpeechNLP</td>
      <td>19.8</td>
      <td>35.21</td>
      <td>26.49</td>
      <td>27.06</td>
      <td>28.75</td>
      <td>27.46</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Bytedance-SA</td>
      <td>27.63</td>
      <td>27.45</td>
      <td>33.8</td>
      <td>31.78</td>
      <td>23.11</td>
      <td>28.75</td>
    </tr>
    <tr>
      <td>8</td>
      <td>JHU-CLSP/GoVivace</td>
      <td>25.93</td>
      <td>33.73</td>
      <td>31.99</td>
      <td>28.69</td>
      <td>23.97</td>
      <td>28.86</td>
    </tr>
    <tr>
      <td>9</td>
      <td>TUTU</td>
      <td>26.68</td>
      <td>36.16</td>
      <td>27.7</td>
      <td>30.25</td>
      <td>25.32</td>
      <td>29.22</td>
    </tr>
    <tr>
      <td>10</td>
      <td>IIITHSPL</td>
      <td>31.11</td>
      <td>37.19</td>
      <td>35.03</td>
      <td>17.0</td>
      <td>26.94</td>
      <td>29.45</td>
    </tr>
    <tr>
      <td>11</td>
      <td>Bhavik Vachhani</td>
      <td>27.78</td>
      <td>34.57</td>
      <td>33.01</td>
      <td>30.08</td>
      <td>28.22</td>
      <td>30.73</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HAL101</td>
      <td>21.42</td>
      <td>34.66</td>
      <td>37.92</td>
      <td>33.92</td>
      <td>34.37</td>
      <td>32.46</td>
    </tr>
    <tr>
      <td>13</td>
      <td>Jio Speech</td>
      <td>35.53</td>
      <td>38.55</td>
      <td>33.69</td>
      <td>31.14</td>
      <td>24.79</td>
      <td>33.34</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>14</td>
      <td>Baseline</td>
      <td>37.2</td>
      <td>38.46</td>
      <td>34.09</td>
      <td>31.44</td>
      <td>26.15</td>
      <td>33.47</td>
    </tr>
    <tr>
      <td>15</td>
      <td>SRI-B</td>
      <td>32.47</td>
      <td>47.72</td>
      <td>27.97</td>
      <td>29.13</td>
      <td>30.17</td>
      <td>33.49</td>
    </tr>
    <tr>
      <td>16</td>
      <td>Nuronics</td>
      <td>38.02</td>
      <td>48.4</td>
      <td>34.89</td>
      <td>33.11</td>
      <td>29.68</td>
      <td>36.82</td>
    </tr>
    <tr>
      <td>17</td>
      <td>Dheeyantra</td>
      <td>36.88</td>
      <td>40.31</td>
      <td>64.02</td>
      <td>40.62</td>
      <td>33.6</td>
      <td>43.09</td>
    </tr>
    <tr>
      <td>18</td>
      <td>INDIGO-IITG</td>
      <td>62.26</td>
      <td>51.44</td>
      <td>117.88</td>
      <td>119.72</td>
      <td>102.9</td>
      <td>90.84</td>
    </tr>
  </tbody>
</table>




</div>

</div>


<div id="subtask2" class="tabcontent">
<h3>Subtask2</h3>



<div class="row">
  <div class="column">
<h4>Ranks are determined on the basis of average WER.:</h4>

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>#</th>
      <th>Team Name</th>
      <th>Hindi-English (% WER)</th>
      <th>Bengali-English (% WER)</th>
      <th>Average (% WER)</th>
    </tr>
    <tr>
      <td>1</td>
      <td>JHU-CLSP</td>
      <td>17.84</td>
      <td>28.78</td>
      <td>23.31</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Sayint</td>
      <td>20.85</td>
      <td>26.72</td>
      <td>23.79</td>
    </tr>
    <tr>
      <td>3</td>
      <td>KARI</td>
      <td>22.49</td>
      <td>25.79</td>
      <td>24.14</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Ekstep</td>
      <td>21.77</td>
      <td>28.27</td>
      <td>25.02</td>
    </tr>
    <tr>
      <td>5</td>
      <td>TUTU</td>
      <td>23.96</td>
      <td>29.63</td>
      <td>26.8</td>
    </tr>
    <tr>
      <td>6</td>
      <td>MCSASR</td>
      <td>24.55</td>
      <td>29.89</td>
      <td>27.22</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Bytedance-SA</td>
      <td>24.89</td>
      <td>30.64</td>
      <td>27.76</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>8</td>
      <td>Baseline</td>
      <td>25.53</td>
      <td>32.81</td>
      <td>29.17</td>
    </tr>
    <tr>
      <td>9</td>
      <td>Jio Speech</td>
      <td>27.69</td>
      <td>32.59</td>
      <td>30.14</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Bhavik Vachhani</td>
      <td>28.25</td>
      <td>34.21</td>
      <td>31.23</td>
    </tr>
  </tbody>
</table>
</div>

  <div class="column">


<h4>Ranks are determined on the basis of average Transliterated WER.:</h4>

<table style="font-size:16.5px;" id="tablePreview" class="table table-striped table-sm">
  
  <!--Table head-->
  <!--Table body-->
  <tbody>
    <tr>
      <th>#</th>
      <th>Team Name</th>
      <th>Hindi-English (% WER)</th>
      <th>Bengali-English (% WER)</th>
      <th>Average (% WER)</th>
    </tr>
    <tr>
      <td>1</td>
      <td>Sayint</td>
      <td>18.78</td>
      <td>25.08</td>
      <td>21.93</td>
    </tr>
    <tr>
      <td>2</td>
      <td>JHU-CLSP</td>
      <td>17.14</td>
      <td>26.96</td>
      <td>22.05</td>
    </tr>
    <tr>
      <td>3</td>
      <td>KARI</td>
      <td>20.6</td>
      <td>24.54</td>
      <td>22.57</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Ekstep</td>
      <td>20.75</td>
      <td>26.96</td>
      <td>23.85</td>
    </tr>
    <tr>
      <td>5</td>
      <td>TUTU</td>
      <td>22.3</td>
      <td>28.33</td>
      <td>25.31</td>
    </tr>
    <tr>
      <td>6</td>
      <td>MCSASR</td>
      <td>22.58</td>
      <td>28.65</td>
      <td>25.61</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Bytedance-SA</td>
      <td>23.02</td>
      <td>29.25</td>
      <td>26.13</td>
    </tr>
    <tr>
      <td>8</td>
      <td>Jio Speech</td>
      <td>23.83</td>
      <td>30.15</td>
      <td>26.99</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>9</td>
      <td>Baseline</td>
      <td>23.8</td>
      <td>31.7</td>
      <td>27.75</td>
    </tr>
    <tr>
      <td>10</td>
      <td>Bhavik Vachhani</td>
      <td>25.1</td>
      <td>32.48</td>
      <td>28.79</td>
    </tr>
  </tbody>
</table>
  </div>
</div>
</div>


<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

function openCity2(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent2");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablinks2");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>