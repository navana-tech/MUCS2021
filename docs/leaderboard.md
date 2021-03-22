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
</style>


<br>
<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Leaderboard</h1>
  </div>
</div>

<br>

<h3>Subtask1</h3>

<p style="font-size:16.5px;">Leaderboard for Subtask1. Ranks are determined on the basis of average WER.:</p>

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
      <td>Ekstep</td>
      <td>12.24</td>
      <td>39.74</td>
      <td>27.1</td>
      <td>27.2</td>
      <td>22.43</td>
      <td>30.65</td>
      <td>26.56</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>2</td>
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
      <td>3</td>
      <td>HAL101</td>
      <td>20.74</td>
      <td>96.75</td>
      <td>36.07</td>
      <td>37.95</td>
      <td>34.79</td>
      <td>34.08</td>
      <td>43.4</td>
    </tr>
  </tbody>
</table>


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
      <td>MCSASR</td>
      <td>24.55</td>
      <td>29.89</td>
      <td>27.22</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Ekstep</td>
      <td>24.4</td>
      <td>31.26</td>
      <td>27.83</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>3</td>
      <td>Baseline</td>
      <td>25.53</td>
      <td>32.81</td>
      <td>29.17</td>
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
      <td>MCSASR</td>
      <td>22.58</td>
      <td>28.65</td>
      <td>25.61</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Ekstep</td>
      <td>22.27</td>
      <td>30.2</td>
      <td>26.23</td>
    </tr>
    <tr style="background-color:#d3c7f0">
      <td>3</td>
      <td>Baseline</td>
      <td>23.8</td>
      <td>31.7</td>
      <td>27.75</td>
    </tr>
  </tbody>
</table>
  </div>
</div>