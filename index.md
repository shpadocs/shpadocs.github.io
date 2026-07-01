---
layout: default
title: "home"
---

## About me
Currently a PhD student at IMT School of Advanced Studies Lucca, Italy, supervised by [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Coming from a bachelor's in Philosophy and a master's in Logic -- see [here](https://www.linkedin.com/in/stella-spadoni-152926290/) for more.

## Publications
- [Cutting Out the Middle Man: A Game-Theoretic Analysis
in Computability Logic of the Needham-Schroeder Protocol](https://ceur-ws.org/Vol-4198/paper57.pdf)

  Joint work with [Cosimo Perini Brogi](https://logicosimo.gitlab.io/).

  Cryptographic protocols constitute the cornerstone of secure communication in open
distributed systems. The systematic formal verification of such protocols gained prominence following Gavin Lowe’s 1995 discovery of a structural flaw in the classical Needham-Schroeder Public Key protocol from 1978. This paper presents a novel formal analysis of
such protocol through Computability Logic (CoL), a game-theoretic semantics and reasoning system that models interaction between an honest agent and a hostile environment. By formalising the protocol’s execution as a game specified in the CoL fragment CL4, we demonstrate that the original vulnerability allows the environment to employ a successful Copycat Strategy isomorphic to the standard Man-in-the-Middle attack (MitM). Conversely, we prove that the revised protocol including Lowe’s fix effectively breaks this
adversarial advantage, guaranteeing security against the MitM.

  Presented at [ITASEC-SERICS 2026 - Joint National Conference on CyberSecurity](https://itasec.it/).


## Master's thesis
- [The Fertile Steppe: Computability Logic and the decidability of one of its fragments](https://arxiv.org/pdf/2503.05826)
  
  The present work is devoted to Computability Logic (CoL), the young and volcanic research-project developed by Giorgi Japaridze. Our main goal is to provide the reader with a clear panoramic view of this vast new land, starting from its core knots and making our way towards the outer threads, in a somewhat three-dimensional, spacial gait. Furthermore, through the present work, we provide a tentative proof for the decidability of one of CoL's numerous axiomatisations, namely CL15. Thus, our expedition initially takes off for an aerial, perusal overview of this fertile steppe. The first chapter introduces CoL in a philosophical fashion, exposing and arguing its main key points. We then move over to unfold its semantics and syntax profiles, allowing the reader to become increasingly more familiar with this new environment. Landing on to the second chapter, we thoroughly introduce Cirquent Calculus, the new deductive system Japaridze has developed in order to axiomatise Computability Logic. Indeed, this new proof-system can also be a useful tool for many other logics. We then review each of the 17 axiomatisations found so far. The third chapter zooms-in on CL15, in order to come up with a possible solution to its open problem. We outline its soundness and completeness proofs; then provide some few deductive examples; and, finally, build a tentative proof of its decidability. Lastly, the fourth chapter focuses on the potential and actual applications of Computability Logic, both in arithmetic (clarithmetic) and in Artificial Intelligence systems (meaning knowledgebase and planning-and-action ones). We close our journey with some final remarks on the richness of this framework and, hence, the research-worthiness it entails.


## Conference talks
- "On decidability and bounded proofs in fragments of computability logic", S. Spadoni, [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Presented at the Logic Colloquium 2026 (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "On protocol security via computability logic", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni, [R. De Nicola](https://scholar.google.com/citations?user=Meb6JFkAAAAJ&hl=en). Presented at the Logic Colloquium 2026 (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "Cutting Out the Middle Man: A Game-Theoretic Analysis in Computability Logic of the Needham-Schroeder Protocol", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni. Presented at ITASEC-SERICS 2026 - Joint National Conference on CyberSecurity, 9 – 13 February 2026, Cagliari, Facoltà di Ingegneria e Architettura, Piazza D’Armi, Sardinia, Italy.

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
