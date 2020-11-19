---
title: Overview
permalink: /about/overview/
---
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
</style>

<body>
<p>Singapore provides one of the world’s most robust regimes for the protection of a company’s intellectual property (IP).</p>
<p>International surveys consistently rank Singapore’s Intellectual Property (IP) regime as one of the best in the world. For example, Singapore is ranked second in the world and top in Asia for having the best IP protection in the World Economic Forum’s Global Competitiveness Report. For more information on Singapore’s IP rankings, please click here.</p>
<p>Singapore’s business-friendly IP regime has helped bolster the confidence of leading global companies such as P&G, Continental, and Mead Johnson, all of whom have selected Singapore as their location of choice for investments in business and R&D, citing the country’s strong protection of IP rights as a factor in their decisions.</p>

  <button class="accordion">Categories of IP Protection</button>
<div class="panel"><p>test</p>
</div>

<button class="accordion">Key Strengths of Singapore’s IP Regime</button>
<div class="panel"><p>test</p>
</div>

<button class="accordion">Different Ways of Resolving IP Disputes</button>
<div class="panel">
  <p>test</p>
</div>

<button class="accordion">Why Resolve IP Disputes in Singapore</button>
<div class="panel">
  <p>I</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>
</body>
</html>
