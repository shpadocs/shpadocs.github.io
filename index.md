---
layout: default
title: "home"
---

## About me <img src="/madotsuki.gif" style="height: 35px; vertical-align: middle; margin-left: 10px; image-rendering: pixelated;">
Currently a PhD student at [IMT School for Advanced Studies Lucca](https://www.imtlucca.it/en/homepage), Italy, supervised by [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Coming from a bachelor's in Philosophy and a master's in Logic -- see [here](https://www.linkedin.com/in/stella-spadoni-152926290/) for more.

## Publications
- [Cutting Out the Middle Man: A Game-Theoretic Analysis
in Computability Logic of the Needham-Schroeder Protocol](https://ceur-ws.org/Vol-4198/paper57.pdf)

  Joint work with [Cosimo Perini Brogi](https://logicosimo.gitlab.io/).

  Cryptographic protocols constitute the cornerstone of secure communication in open
distributed systems. The systematic formal verification of such protocols gained prominence following Gavin Lowe’s 1995 discovery of a structural flaw in the classical Needham-Schroeder Public Key protocol from 1978. This paper presents a novel formal analysis of
such protocol through Computability Logic (CoL), a game-theoretic semantics and reasoning system that models interaction between an honest agent and a hostile environment. By formalising the protocol’s execution as a game specified in the CoL fragment CL4, we demonstrate that the original vulnerability allows the environment to employ a successful Copycat Strategy isomorphic to the standard Man-in-the-Middle attack (MitM). Conversely, we prove that the revised protocol including Lowe’s fix effectively breaks this
adversarial advantage, guaranteeing security against the MitM.

  Presented at [ITASEC-SERICS 2026 - Joint National Conference on CyberSecurity](https://itasec.it/).

<div style="border: 4px double #cccccc; background-color: #111111; padding: 15px; font-family: 'VT323', monospace; margin: 20px 0; border-radius: 5px;">
  
  <div style="border-bottom: 2px dashed #444444; padding-bottom: 10px; margin-bottom: 10px; color: #ffffff; min-height: 25px;">
    <a href="[https://www.youtube.com/watch?v=EfdYDE7PfmE&list=RDEfdYDE7PfmE&start_radio=1]" target="_blank" style="color: #ffffff; text-decoration: underline; cursor: pointer;"><strong>BATTLE LOG:</strong></a> <span id="battle-text" style="color: #ffffaa;">A hostile Environment appeared!</span>
  </div>

  <table style="width: 100%; text-align: left; border-collapse: collapse;">
    <tr>
      <th style="padding: 5px; color: #cc99ff;">[ Machine (A, B) ]</th>
      <th style="padding: 5px; color: #ff3366;">[ Environment (MitM) ]</th>
    </tr>
    <tr>
      <td style="padding: 5px;">
        <span style="cursor: pointer; color: #ffffff;" onmouseover="document.getElementById('battle-text').innerText='> A initialises Needham-Schroeder Protocol...'">> Initialise Protocol</span>
      </td>
      <td style="padding: 5px;">
        <span style="cursor: pointer; color: #ffffff;" onmouseover="document.getElementById('battle-text').innerText='> I uses Copycat Strategy! It is super effective!'">> Copycat Strategy</span>
      </td>
    </tr>
    <tr>
      <td style="padding: 5px;">
        <span style="cursor: pointer; color: #ffffff;" onmouseover="document.getElementById('battle-text').innerText='> B applies Lowe&apos;s Fix! Adversarial advantage broken.'">> Apply Lowe's Fix</span>
      </td>
      <td style="padding: 5px;">
        <span style="cursor: pointer; color: #ffffff;" onmouseover="document.getElementById('battle-text').innerText='> I attempts attack... Blocked by Lowe&apos;s Fix!'">> Intercept</span>
      </td>
    </tr>
  </table>
</div>

## Master's thesis
- [The Fertile Steppe: Computability Logic and the decidability of one of its fragments](https://arxiv.org/pdf/2503.05826)
  
  The present work is devoted to Computability Logic (CoL), the young and volcanic research-project developed by Giorgi Japaridze. Our main goal is to provide the reader with a clear panoramic view of this vast new land, starting from its core knots and making our way towards the outer threads, in a somewhat three-dimensional, spacial gait. Furthermore, through the present work, we provide a tentative proof for the decidability of one of CoL's numerous axiomatisations, namely CL15. Thus, our expedition initially takes off for an aerial, perusal overview of this fertile steppe. The first chapter introduces CoL in a philosophical fashion, exposing and arguing its main key points. We then move over to unfold its semantics and syntax profiles, allowing the reader to become increasingly more familiar with this new environment. Landing on to the second chapter, we thoroughly introduce Cirquent Calculus, the new deductive system Japaridze has developed in order to axiomatise Computability Logic. Indeed, this new proof-system can also be a useful tool for many other logics. We then review each of the 17 axiomatisations found so far. The third chapter zooms-in on CL15, in order to come up with a possible solution to its open problem. We outline its soundness and completeness proofs; then provide some few deductive examples; and, finally, build a tentative proof of its decidability. Lastly, the fourth chapter focuses on the potential and actual applications of Computability Logic, both in arithmetic (clarithmetic) and in Artificial Intelligence systems (meaning knowledgebase and planning-and-action ones). We close our journey with some final remarks on the richness of this framework and, hence, the research-worthiness it entails.


## Conference talks
- "On decidability and bounded proofs in fragments of computability logic", S. Spadoni, [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Presented at the Logic Colloquium 2026 (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "On protocol security via computability logic", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni, [R. De Nicola](https://scholar.google.com/citations?user=Meb6JFkAAAAJ&hl=en). Presented at the Logic Colloquium 2026 (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "Cutting Out the Middle Man: A Game-Theoretic Analysis in Computability Logic of the Needham-Schroeder Protocol", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni. Presented at ITASEC-SERICS 2026 - Joint National Conference on CyberSecurity, 9 – 13 February 2026, Cagliari, Facoltà di Ingegneria e Architettura, Piazza D’Armi, Sardinia, Italy.

<button id="wake-up" style="position: fixed; bottom: 20px; right: 20px; z-index: 100; background-color: #050505; border: 2px solid #ff3366; color: #ff3366; font-family: 'VT323', monospace; font-size: 18px; padding: 10px 15px; cursor: pointer;">Pinch Cheek</button>

<script>
let isAwake = false;

document.getElementById("wake-up").addEventListener("click", function() {
    
    let headers = document.querySelectorAll("h1, h2, h3");

    if (!isAwake) {
        
        document.body.style.backgroundColor = "#fafafa"; 
        document.body.style.color = "#000000"; 
        
        
        headers.forEach(function(header) {
            header.style.color = "#000000";
        });
        
        
        document.body.style.fontFamily = "'VT323', monospace";
        document.body.style.fontSize = "18px";
        
        
        this.innerText = "Go to sleep.";
        this.style.border = "1px solid #cccccc";
        this.style.color = "#888888";
        this.style.backgroundColor = "#eeeeee";
        
        isAwake = true; 
    } else {
        
        document.body.style.backgroundColor = "#050505"; 
        document.body.style.color = "#cc99ff"; 
        
        
        headers.forEach(function(header) {
            header.style.color = "#ffffff";
        });
        
        
        this.innerText = "Pinch Cheek";
        this.style.border = "2px solid #ff3366";
        this.style.color = "#ff3366";
        this.style.backgroundColor = "#050505";
        
        isAwake = false; 
    }
});
</script>
<br><br><br>
<hr>
<div style="text-align: center;">
  <span id="light-switch" style="font-size: 30px; cursor: pointer;">💡</span>
  <p style="font-size: 14px;">(Don't turn off the lights)</p>
</div>

<script>
document.getElementById("light-switch").addEventListener("click", function() {
    // There is a 50% chance Uboa appears!
    if (Math.random() < 0.5) { 
        document.body.style.backgroundColor = "white"; // Flashes white
        document.body.innerHTML = "<div style='text-align:center; margin-top:20%; font-family:sans-serif;'><h1>UBOA</h1><p>You shouldn't have done that.</p></div>";
    } else {
        document.body.style.backgroundColor = "#222"; // Just makes the room slightly darker
    }
});
</script>

<script>

console.log("%c[SYSTEM ACCESS GRANTED]", "color: #ff3366; font-size: 16px; font-weight: bold; font-family: monospace;");
console.log("%cWelcome to the Nexus. If you're reading this, you either know your way around DevTools or you're lost. Feel free to check out my GitHub repos for the raw code.", "color: #cc99ff; font-family: monospace;");
</script>

<img id="sidebar-gif" src="/interface-umami.gif" alt="umami GIF" style="display: none; max-width: 100%; margin-top: 25px; image-rendering: pixelated;">

<script>
document.addEventListener("DOMContentLoaded", function() {
    
    var sidebar = document.querySelector("header");
    var gif = document.getElementById("sidebar-gif");
    
    
    if (sidebar && gif) {
        gif.style.display = "block"; 
        sidebar.appendChild(gif); 
    }
});
</script>
