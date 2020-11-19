---
title: Overview
permalink: /about/overview/
---
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Accordion Test Page</title>
</head>

<body style="margin: 1em;">
    
<main>
    
<!-- Accordion Custom Element -->          
<div class="accordion" role="tablist">
    <button role="tab">Accordion Title 1</button>
    <section role="tabpanel">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </section>
</div>
    
<hr>
    
<div class="accordion" role="tablist">
    <button role="tab">Accordion Title 2</button>
    <section role="tabpanel">
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </section>
</div>
    
</main>
      
<script async>
    
// Accordion Style Element, use class="accordion"
(function(){
    var acc = document.getElementsByClassName("accordion"), l = acc.length;
    for (let i = 0; i < l; i++) {
        acc[i].firstChild.nextSibling.onclick = function () {
            this.classList.toggle("active");
            var panel = this.nextSibling.nextSibling;
            if (panel.style.maxHeight) {
                panel.style.maxHeight = null;
            } else {
                panel.style.maxHeight = panel.scrollHeight + "px";
            } 
        }
    }
    
	// Stylesheet
	let st = document.createElement("style");
	st.textContent = (`
	.accordion > button {
		width: 100%;
		text-align: left;
		background: transparent;
		border: 0;
		border-top: 1px solid #eee;
		font-size: 1.2em;
		line-height: 1em;
		padding: 0.55em;
	}
	.accordion > button::before {
		content: url("data:image/svg+xml;charset=utf-8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='16' height='16'%3E%3Cpath d='M16 9H9v7H7V9H0V7h7V0h2v7h7z'/%3E%3C/svg%3E");
		margin: 0 0.5em 0 0;
		display: inline-block;
		transition: transform 0.4s ease-in-out 0s;
		transform-origin: 50% 50%;
		will-change: transform;
	}
	.accordion > button.active::before {
		-webkit-transform: rotate(135deg);
		transform: rotate(135deg);
	}
	.accordion > section {
		padding: 0 1em;
		max-height: 0;
		overflow: hidden;
		transition: max-height 0.2s ease-out;
		border-bottom: 1px solid #eee;
		will-change: auto;
	}
	`);
	document.body.appendChild(st); 		
}());
	
</script>
</body>
</html>

