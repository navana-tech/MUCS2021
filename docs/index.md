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
  padding: 12px;
  width: 100%;
  height: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 16.5px;
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
  font-size: 16.5px;
}
</style>



<button class="collapsible"><img style="height: 120px; width:auto;padding:1px;"  src="./assets/img/persons/placeholder.jpg">Anurag Dwarakanath (amazon) - Spoken Language Understanding for the Indic Region</button>
<div class="content">
  <p>Title: Spoken Language Understanding for the Indic Region.</p>
  <p>Abstract. In this talk, we will touch upon some of the key challenges in building Spoken Language Understanding systems for the Indic region. We begin with an insight on the usage of code-mixed multi-lingual utterances where many Indic languages (beyond Hindi) are freely used. We show how such Indic language usage gets represented in Latin script in a transliterated form and current state of the art multi-lingual language models (such as XLM-R, mBERT) surprisingly do not build common representations of transliterated text and that in the original language. We then introduce research in Continual Language Learning as an emerging area to bridge this gap. The Indic region also sees wide variety of spoken language variations including grammatical errors and ambiguous utterances leading to noise in data. We present recent progress in the area of Robust Machine Learning that aims to build learning algorithms that are resilient to noise in data. </p>

<p>Bio. Anurag Dwarakanath is an applied science manager in Alexa AI and leads a team of scientists building machine learning and statistical models for the Natural Language Understanding components of Alexa. His interests include multi-lingual natural language processing, robustness in deep learning and verification & validation of deep learning systems. Anurag holds a PhD from Indian Institute of Management Calcutta where he studied the application of Graph Theory in Wireless Sensor Networks. Anurag has over 20 publications and 15 patents. 
</p>
</div>
 <hr>

<button class="collapsible">Shinji Watanabe</button>
<div class="content">
  <p>Speakers: Shinji Watanabe and Pengcheng Guo</p>
  <p>Title: Introduction of ESPnet, End-to-End Speech Processing Toolkit</p>

<p>Abstract: An end-to-end neural approach has become a popular alternative to conventional modular approaches in various speech applications including speech recognition and synthesis.
One of the benefits of this end-to-end neural framework is that we can use a unified framework for different speech processing problems based on sequence-to-sequence modeling. This tutorial aims to introduce various end-to-end speech processing applications by focusing on the above unified framework within an open source toolkit named ESPnet (End-to-end speech processing toolkit https://github.com/espnet/espnet). We will explain the recent advance of ESPnet, including conformer: convolution-augmented transformer, and show an example of making an ESPnet recipe to build a state-of-the-art ASR system. </p>
<p>Short bio:</p>
<p>Shinji Watanabe</p>
<p>Shinji Watanabe is an Associate Professor at Carnegie Mellon University, Pittsburgh, PA. He received his B.S., M.S., and Ph.D. (Dr. Eng.) degrees from Waseda University, Tokyo, Japan. He was a research scientist at NTT Communication Science Laboratories, Kyoto, Japan, from 2001 to 2011, a visiting scholar in Georgia institute of technology, Atlanta, GA in 2009, and a senior principal research scientist at Mitsubishi Electric Research Laboratories (MERL), Cambridge, MA USA from 2012 to 2017. Prior to the move to Carnegie Mellon University, he was an associate research professor at Johns Hopkins University, Baltimore, MD USA from 2017 to 2020. His research interests include automatic speech recognition, speech enhancement, spoken language understanding, and machine learning for speech and language processing. He has been published more than 200 papers in peer-reviewed journals and conferences and received several awards, including the best paper award from the IEEE ASRU in 2019. He served as an Associate Editor of the IEEE Transactions on Audio Speech and Language Processing. He was/has been a member of several technical committees, including the APSIPA Speech, Language, and Audio Technical Committee (SLA), IEEE Signal Processing Society Speech and Language Technical Committee (SLTC), and Machine Learning for Signal Processing Technical Committee (MLSP).</p>
<p>Pengcheng Guo</p>
<p>Pengcheng Guo is a Ph.D. candidate at Northwestern Polytechnical University, Xi'an, China.
His supervisors are Prof. Lei Xie and Prof. Shinji Watanabe. From Jul. 2017 to Jul. 2018, he was a research assistant at Nanyang Technology University, Singapore, collaborating with Prof. Eng Siong Chng and Prof. Haizhou Li. From Apr. 2019 to Nov. 2019, he was a research intern at ByteDance AI Lab, Beijing, China, collaborating with Dr. Yuxuan Wang (the author of Tacotron). From Jan.2020 to Jan. 2021, he joined Shinji Watanabe’s team as a visiting scholar at Johns Hopkins University, Baltimore, US. His research interests include automatic speech recognition, domain adaptation, and adversarial training. He is the main developer of ESPnet and has contributed to a lot of projects, including the Conformer architecture, various ASR benchmark recipes, etc.</p>
</div>
<br>

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

