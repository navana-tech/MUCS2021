---
layout: workshop      # DON'T CHANGE THIS.
# More detailed instructions (including how to fill these variables for an
# online workshop) are available at
# https://carpentries.github.io/workshop-template/customization/index.html
venue: "MUCS 2021 "        # brief name of the institution that hosts the workshop without address (e.g., "Euphoric State University")
address: ""      # full street address of workshop (e.g., "Room A, 123 Forth Street, Blimingen, Euphoria"), videoconferencing URL, or 'online'
country: "in"      # lowercase two-letter ISO country code such as "fr" (see https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes) for the institution that hosts the workshop
language: "in"     # lowercase two-letter ISO language code such as "fr" (see https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for the
latitude: "45"        # decimal latitude of workshop venue (use https://www.latlong.net/)
longitude: "-1"       # decimal longitude of the workshop venue (use https://www.latlong.net)
humandate: ""    # human-readable dates for the workshop (e.g., "Feb 17-18, 2020")
humantime: ""    # human-readable times for the workshop (e.g., "9:00 am - 4:30 pm")
startdate:       # machine-readable start date for the workshop in YYYY-MM-DD format like 2015-01-01
enddate:         # machine-readable end date for the workshop in YYYY-MM-DD format like 2015-01-02
# instructor:  # boxed, comma-separated list of instructors' names as strings, like ["Kay McNulty", "Betty Jennings", "Betty Snyder"]
helper:      # boxed, comma-separated list of helpers' names, like ["Marlyn Wescoff", "Fran Bilas", "Ruth Lichterman"]
email: ["is21ss.indicasrchallenge@gmail.com"]    # boxed, comma-separated list of contact email addresses for the host, lead instructor, or whoever else is handling questions, like ["marlyn.wescoff@example.org", "fran.bilas@example.org", "ruth.lichterman@example.org"]
collaborative_notes:  # optional: URL for the workshop collaborative notes, e.g. an Etherpad or Google Docs document (e.g., https://pad.carpentries.org/2015-01-01-euphoria)
eventbrite:           # optional: alphanumeric key for Eventbrite registration, e.g., "1234567890AB" (if Eventbrite is being used)
---

<style>
* {
  box-sizing: border-box;
}

/* Create two unequal columns that floats next to each other */
.column {
  float: left;
  padding: 10px;
  height: 300px; /* Should be removed. Only for demonstration */
}

.left {
  width: 100%;
}

.right {
  width: 25%;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
</style>

<br>
<div class="widewrapper pagetitle">
  <div class="container" style="background-color:#617863">
    <h1 style="color:white;">Keynotes</h1>
  </div>
</div>
<br>


<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<p>A Collapsible:</p>
<button class="collapsible">Anurag Dwarakanath (amazon) - Spoken Language Understanding for the Indic Region</button>
<div class="content">
  <p>Title: Spoken Language Understanding for the Indic Region.</p>
  <p>Abstract. In this talk, we will touch upon some of the key challenges in building Spoken Language Understanding systems for the Indic region. We begin with an insight on the usage of code-mixed multi-lingual utterances where many Indic languages (beyond Hindi) are freely used. We show how such Indic language usage gets represented in Latin script in a transliterated form and current state of the art multi-lingual language models (such as XLM-R, mBERT) surprisingly do not build common representations of transliterated text and that in the original language. We then introduce research in Continual Language Learning as an emerging area to bridge this gap. The Indic region also sees wide variety of spoken language variations including grammatical errors and ambiguous utterances leading to noise in data. We present recent progress in the area of Robust Machine Learning that aims to build learning algorithms that are resilient to noise in data. 

 

Bio. Anurag Dwarakanath is an applied science manager in Alexa AI and leads a team of scientists building machine learning and statistical models for the Natural Language Understanding components of Alexa. His interests include multi-lingual natural language processing, robustness in deep learning and verification & validation of deep learning systems. Anurag holds a PhD from Indian Institute of Management Calcutta where he studied the application of Graph Theory in Wireless Sensor Networks. Anurag has over 20 publications and 15 patents. 
</p>
</div>

<p>Collapsible Set:</p>
<button class="collapsible">Open Section 1</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button class="collapsible">Open Section 2</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button class="collapsible">Open Section 3</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>

</body>


