---
title: Overview
permalink: /about/overview/
---
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
</head>
<body>

<button class="accordion">Key Strengths of Singapore’s IP Regime</button>
<div class="panel"><p>•	International Treaties
o	Singapore is a signatory to major multilateral IP agreements such as the Patent Cooperation Treaty, the Madrid Protocol, the Hague Agreement, and the Berne Convention. This allows, for example, a Singapore resident to seek patent, trade mark, or registered design protection in several countries simultaneously via a single application.
•	International Searching and Preliminary Examining Authority (ISA/IPEA)
o	IPOS is the first IP office in Southeast Asia to be recognised as an ISA/IPEA under the WIPO Patent Cooperation Treaty (PCT). Patent applicants in more than 10 jurisdictions, including the US, Japan, and Korea, can elect IPOS to perform the International Search and Preliminary Examination in order to obtain patent protection in any of the PCT’s over 150 contracting states.
•	Acceleration Programmes
o	Patent Prosecution Highway (PPH) and ASEAN Patent Examination Co-operation (ASPEC). Through IPOS’ network of work-sharing programmes, patent applications can rely on a Singapore patent report to expedite the patent application process in more than 30 jurisdictions, including the US, Japan, Korea, China, Europe and eight other Southeast Asia countries. Furthermore, under the ASPEC Acceleration for Industry 4.0 Infrastructure and Manufacturing (ASPEC AIM) programme, Industry 4.0 patent applications (e.g. in the field of AI) are prioritised.
o	Under the SG IP Fast Track, patent applications in all technology fields which are first filed in Singapore can be granted in as fast as six months. Related trade mark and registered design applications can also be accelerated, to be registered in as fast as three months and one month respectively.
o	More information on acceleration programmes can be found here.
•	Forward-looking Registry that is Customer Centric
o	The IPOS GO mobile app allows users to conveniently file trade mark applications, and renew patents, trade marks and registered designs, on the go. 
o	More information can be found here.
•	Strong Ecosystem
o	Singapore is home to a strong ecosystem of legal and IP firms, including law firms, patent firms, intermediaries and consulting firms.
To find out more about the role of IP in spurring innovation, how you can protect your intellectual property, and how you can grow your business with IP, please click here.
 
</p>
</div>

<button class="accordion">Different Ways of Resolving IP Disputes</button>
<div class="panel">
  <p>IP disputes may be encountered in the course of managing your IP portfolio or doing business in connection with Singapore. The main routes of resolving IP disputes are litigation, arbitration, mediation and negotiation.</p>
</div>

<button class="accordion">Why Resolve IP Disputes in Singapore</button>
<div class="panel">
  <p>In addition to the advantages for dispute resolution in general, Singapore also has several compelling advantages for resolving intellectual property disputes.

·       IP Specialists

o   The High Court has a specialised list of judges who hear IP and IT cases.

o   The Singapore International Commercial Court (SICC) has specialist international judges to hear IP and technology cases.

o   The Singapore International Arbitration Centre (SIAC) maintains a specialist Panel of Arbitrators for IP disputes.

·       Arbitrability of IP Disputes

o   In 2019, the International Arbitration Act and Arbitration Act were amended to clarify that IP disputes are arbitrable in Singapore

·       World Intellectual Property Organization (WIPO) Arbitration and Mediation Center

o   Singapore is home to the only office of WIPO’s Arbitration and Mediation Center outside of Geneva.

·       Availability of IP Insurance

o   IP insurance is available for legal fees and costs awarded against you relating to IP infringement proceedings and disputes between licensor and licensee

·       Strong Ecosystem

o   Singapore is home to a strong ecosystem of dispute resolution practices which are experienced in IP, as well as a network of technical experts in STEM fields who can be called upon as expert witnesses.

·       Publicly Available Information on Registrable IP Rights

o   For disputes on IP rights that are registrable with the Intellectual Property Office of Singapore (IPOS), all publicly information relating to the IP rights may be accessed on IP²SG, the e-services portal maintained by IPOS. Through this portal, anyone may conduct searches on the various Registers (e.g. to ascertain whether a competitor’s trade mark is registered or patent is granted).</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

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
