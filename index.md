---
layout: default
title: "Home"
---

## About me ![Madotsuki spinning](/madotsuki.gif)
Currently a PhD student at [IMT School for Advanced Studies Lucca](https://www.imtlucca.it/en/homepage), Italy, supervised by [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Coming from a bachelor's in Philosophy and a master's in Logic -- see [here](https://www.linkedin.com/in/stella-spadoni-152926290/) for more.

<div id="save-screen" style="font-family: 'VT323', monospace; margin: 30px 0;">
    
    <h2 id="save-title" style="color: #ffffff; border-bottom: 2px dashed #444444; padding-bottom: 10px; margin-bottom: 15px;">💾 MEMORY CARD:</h2>
    <div class="save-slot" style="border: 2px solid #cc99ff; background-color: #050505; padding: 15px; margin-bottom: 12px; border-radius: 4px; box-shadow: 4px 4px 0px #220033;">
        <div style="display: flex; justify-content: space-between; align-items: center;">
            <span class="save-header" style="color: #ff3366; font-size: 22px; font-weight: bold;">FILE 03: PhD SYSTEMS SCIENCE (SOFTWARE QUALITY)</span>
            <span style="color: #55ff55; font-size: 16px; border: 1px solid #55ff55; padding: 2px 6px; border-radius: 3px;">STILL LOADING</span>
        </div>
        <div class="save-details" style="color: #aaaaaa; margin-top: 10px; font-size: 18px; line-height: 1.4;">
            • <strong style="color: #ffffff;" class="save-label">LOCATION:</strong> IMT School for Advanced Studies Lucca <br>
            • <strong style="color: #ffffff;" class="save-label">PLAY TIME:</strong> 2025 - 2028<br>
            • <strong style="color: #ffffff;" class="save-label">LAST LOG:</strong> Ongoing.
        </div>
    </div>
    
    <div class="save-slot" style="border: 2px solid #cc99ff; background-color: #050505; padding: 15px; margin-bottom: 12px; border-radius: 4px; box-shadow: 4px 4px 0px #220033;">
        <div style="display: flex; justify-content: space-between; align-items: center;">
            <span class="save-header" style="color: #ff3366; font-size: 22px; font-weight: bold;">FILE 02: MSc LOGIC, PHILOSOPHY AND HISTORY OF SCIENCE</span>
            <span style="color: #55ff55; font-size: 16px; border: 1px solid #55ff55; padding: 2px 6px; border-radius: 3px;">LOAD COMPLETED</span>
        </div>
        <div class="save-details" style="color: #aaaaaa; margin-top: 10px; font-size: 18px; line-height: 1.4;">
            • <strong style="color: #ffffff;" class="save-label">LOCATION:</strong> University of Florence <br>
            • <strong style="color: #ffffff;" class="save-label">PLAY TIME:</strong> 2022 - 2024<br>
            • <strong style="color: #ffffff;" class="save-label">LAST LOG:</strong> THE FERTILE STEPPE: COMPUTABILITY LOGIC AND THE DECIDABILITY OF ONE OF ITS FRAGMENTS. Supervisor: Pierluigi Minari. Co-supervisor: Andrea Cantini.
        </div>
    </div>

    <div class="save-slot" style="border: 2px solid #cc99ff; background-color: #050505; padding: 15px; margin-bottom: 12px; border-radius: 4px; box-shadow: 4px 4px 0px #220033;">
        <div style="display: flex; justify-content: space-between; align-items: center;">
            <span class="save-header" style="color: #ff3366; font-size: 22px; font-weight: bold;">FILE 01: BSc PHILOSOPHY</span>
            <span style="color: #55ff55; font-size: 16px; border: 1px solid #55ff55; padding: 2px 6px; border-radius: 3px;">LOAD COMPLETED</span>
        </div>
        <div class="save-details" style="color: #aaaaaa; margin-top: 10px; font-size: 18px; line-height: 1.4;">
            • <strong style="color: #ffffff;" class="save-label">LOCATION:</strong> University of Florence <br>
            • <strong style="color: #ffffff;" class="save-label">PLAY TIME:</strong> 2019 - 2022 <br>
            • <strong style="color: #ffffff;" class="save-label">LAST LOG:</strong> "THE ELEGANT VERSATILE BRAIN": A LOGICAL AND PHILOSOPHICAL TAKE ON THE UNIVERSAL TURING MACHINE. Supervisor: Andrea Cantini. Co-supervisor: Sergio Bernini.
        </div>
    </div>

</div>

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
- "On decidability and bounded proofs in fragments of computability logic", S. Spadoni, [Cosimo Perini Brogi](https://logicosimo.gitlab.io/). Presented at the [Logic Colloquium 2026](https://logiccolloquium2026.github.io/) (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "On protocol security via computability logic", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni, [R. De Nicola](https://scholar.google.com/citations?user=Meb6JFkAAAAJ&hl=en). Presented at the [Logic Colloquium 2026](https://logiccolloquium2026.github.io/) (in conjunction with the British Logic Colloquium 2026), 29 June - 3 July 2026, Swansea University, Wales, UK;
- "Cutting Out the Middle Man: A Game-Theoretic Analysis in Computability Logic of the Needham-Schroeder Protocol", [Cosimo Perini Brogi](https://logicosimo.gitlab.io/), S. Spadoni. Presented at [ITASEC-SERICS 2026 - Joint National Conference on CyberSecurity](https://itasec.it/), 9 – 13 February 2026, Cagliari, Facoltà di Ingegneria e Architettura, Piazza D’Armi, Sardinia, Italy.

<button id="wake-up" style="position: fixed; bottom: 20px; right: 20px; z-index: 100; background-color: #050505; border: 2px solid #ff3366; color: #ff3366; font-family: 'VT323', monospace; font-size: 18px; padding: 10px 15px; cursor: pointer;">Pinch Cheek</button>

<script>
let isAwake = false;

document.getElementById("wake-up").addEventListener("click", function() {
    let headers = document.querySelectorAll("h1, h2, h3");
    
    // Lore Box elements
    let loreBox = document.getElementById("lore-box");
    let loreTitle = document.getElementById("lore-title");
    let loreSummaries = document.querySelectorAll(".lore-summary");
    let loreContents = document.querySelectorAll(".lore-content");
    
    // Save Slot elements
    let saveTitle = document.getElementById("save-title");
    let saveSlots = document.querySelectorAll(".save-slot");
    let saveHeaders = document.querySelectorAll(".save-header");
    let saveLabels = document.querySelectorAll(".save-label");
    let saveDetails = document.querySelectorAll(".save-details");
    let saveStatuses = document.querySelectorAll(".save-status");

    // CV System Terminal elements
    let cvBox = document.getElementById("cv-box");
    let cvTitle = document.getElementById("cv-title");
    let cvText = document.getElementById("cv-text");
    let cvButton = document.getElementById("cv-button");
    let cvMetaLeft = document.getElementById("cv-meta-left");
    let cvMetaRight = document.getElementById("cv-meta-right");
    let cvStats = document.getElementById("cv-stats");
    let cvStatRows = document.querySelectorAll(".cv-stat-row");

    if (!isAwake) {
        // --- WAKING UP (STARK / INDUSTRIAL / CINEMATIC LIGHT) ---
        document.body.style.backgroundColor = "#e5e5e5"; // Slate/industrial off-white
        document.body.style.color = "#111111"; 
        
        headers.forEach(function(header) { header.style.color = "#111111"; });
        if (saveTitle) { saveTitle.style.color = "#111111"; }
        
        // 1. Transform Lore Box
        if (loreBox) {
            loreBox.style.backgroundColor = "#dddddd";
            loreBox.style.borderColor = "#666666";
            loreBox.style.boxShadow = "5px 5px 0px #bbbbbb";
        }
        if (loreTitle) { loreTitle.style.color = "#111111"; }
        loreSummaries.forEach(function(s) { s.style.color = "#8a1c32"; });
        loreContents.forEach(function(c) { 
            c.style.backgroundColor = "#ffffff";
            c.style.color = "#222222";
            c.querySelector("em").style.color = "#555555";
        });

        // 2. Transform Save Slots
        saveSlots.forEach(function(slot) {
            slot.style.backgroundColor = "#dddddd";
            slot.style.borderColor = "#666666";
            slot.style.boxShadow = "4px 4px 0px #bbbbbb";
        });
        saveHeaders.forEach(function(sh) { sh.style.color = "#8a1c32"; });
        saveLabels.forEach(function(sl) { sl.style.color = "#111111"; });
        saveDetails.forEach(function(sd) { sd.style.color = "#333333"; });
        saveStatuses.forEach(function(status) {
            status.style.color = "#115511";
            status.style.borderColor = "#115511";
        });

        // 3. Transform CV Terminal Box (Minimalist Cinematic/Clinical Layout)
        if (cvBox) {
            cvBox.style.backgroundColor = "#dddddd";
            cvBox.style.borderColor = "#444444";
            cvBox.style.boxShadow = "0 0 0 4px #dddddd, 6px 6px 0px #bbbbbb";
        }
        if (cvTitle) { cvTitle.style.color = "#111111"; }
        if (cvText) { cvText.style.color = "#333333"; }
        if (cvMetaLeft) { cvMetaLeft.style.color = "#777777"; }
        if (cvMetaRight) { cvMetaRight.style.color = "#8a1c32"; }
        if (cvStats) {
            cvStats.style.backgroundColor = "#e0e0e0";
            cvStats.style.borderColor = "#aaaaaa";
            cvStats.style.color = "#111111";
            cvStats.querySelector("div").style.color = "#444444";
        }
        cvStatRows.forEach(row => {
            row.style.color = "#444444";
            row.querySelector("span").style.color = "#111111";
        });
        if (cvButton) {
            cvButton.style.backgroundColor = "#8a1c32"; // Deadpan muted red
            cvButton.style.color = "#ffffff";
            cvButton.style.borderColor = "#8a1c32";
        }

        // Main Button Changes
        this.innerText = "Go to sleep.";
        this.style.border = "1px solid #aaaaaa";
        this.style.color = "#555555";
        this.style.backgroundColor = "#dddddd";
        
        isAwake = true;
    } else {
        // --- GOING BACK TO SLEEP (DARK SYSTEM / YUME NIKKI GLORY) ---
        document.body.style.backgroundColor = "#050505"; 
        document.body.style.color = "#cc99ff"; 
        
        headers.forEach(function(header) { header.style.color = "#ffffff"; });
        if (saveTitle) { saveTitle.style.color = "#ffffff"; }
        
        // 1. Restore Lore Box
        if (loreBox) {
            loreBox.style.backgroundColor = "#050505";
            loreBox.style.borderColor = "#cc99ff";
            loreBox.style.boxShadow = "5px 5px 0px #220033";
        }
        if (loreTitle) { loreTitle.style.color = "#ff3366"; }
        loreSummaries.forEach(function(s) { s.style.color = "#ffffaa"; });
        loreContents.forEach(function(c) { 
            c.style.backgroundColor = "#111111";
            c.style.color = "#cc99ff";
            c.querySelector("em").style.color = "#ffffff";
        });

        // 2. Restore Save Slots
        saveSlots.forEach(function(slot) {
            slot.style.backgroundColor = "#050505";
            slot.style.borderColor = "#cc99ff";
            slot.style.boxShadow = "4px 4px 0px #220033";
        });
        saveHeaders.forEach(function(sh) { sh.style.color = "#ff3366"; });
        saveLabels.forEach(function(sl) { sl.style.color = "#ffffff"; });
        saveDetails.forEach(function(sd) { sd.style.color = "#aaaaaa"; });
        saveStatuses.forEach(function(status) {
            status.style.color = "#55ff55";
            status.style.borderColor = "#55ff55";
        });

        // 3. Restore CV Terminal Box
        if (cvBox) {
            cvBox.style.backgroundColor = "#000000";
            cvBox.style.borderColor = "#ff3366";
            cvBox.style.boxShadow = "0 0 0 4px #000000, 6px 6px 0px #220033";
        }
        if (cvTitle) { cvTitle.style.color = "#ffffff"; }
        if (cvText) { cvText.style.color = "#aaaaaa"; }
        if (cvMetaLeft) { cvMetaLeft.style.color = "#666666"; }
        if (cvMetaRight) { cvMetaRight.style.color = "#ff3366"; }
        if (cvStats) {
            cvStats.style.backgroundColor = "#050505";
            cvStats.style.borderColor = "#333333";
            cvStats.querySelector("div").style.color = "#ffffaa";
        }
        cvStatRows.forEach(row => {
            row.style.color = "#cc99ff";
            row.querySelector("span").style.color = "#ffffff";
        });
        if (cvButton) {
            cvButton.style.backgroundColor = "#000000";
            cvButton.style.color = "#ff3366";
            cvButton.style.borderColor = "#ff3366";
        }

        // Main Button Changes
        this.innerText = "Pinch Cheek";
        this.style.border = "2px solid #ff3366";
        this.style.color = "#ff3366";
        this.style.backgroundColor = "#050505";
        
        isAwake = false;
    }
});
</script>
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

<div id="cv-box" style="border: 4px double #ff3366; background-color: #000000; padding: 20px; font-family: 'VT323', monospace; margin: 35px 0; border-radius: 0px; box-shadow: 0 0 0 4px #000000, 6px 6px 0px #220033; position: relative;">
    
    <div style="display: flex; justify-content: space-between; border-bottom: 2px solid #333333; padding-bottom: 8px; margin-bottom: 15px; font-size: 16px; letter-spacing: 1px;">
        <span id="cv-meta-left" style="color: #666666;">SYS_REC // FILE_NO_0999</span>
        <span id="cv-meta-right" style="color: #ff3366; animation: blink 1.5s infinite steps(1);">● ACTIVE_EXTRACTOR</span>
    </div>

    <div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: flex-start;">
        
        <div id="cv-stats" style="border: 1px solid #333333; background: #050505; padding: 12px; min-width: 160px; font-size: 18px; line-height: 1.5;">
            <div style="color: #ffffaa; border-bottom: 1px dashed #333333; padding-bottom: 4px; margin-bottom: 6px; font-weight: bold;">[ ITEM PROFILE ]</div>
            <div class="cv-stat-row" style="color: #cc99ff;">CLASS: <span style="color: #ffffff; float: right;">USELESS_DATA</span></div>
            <div class="cv-stat-row" style="color: #cc99ff;">SIZE: <span style="color: #ffffff; float: right;">244 KB</span></div>
            <div class="cv-stat-row" style="color: #cc99ff;">THREAT: <span style="color: #55ff55; float: right;">11.11%</span></div>
            <div class="cv-stat-row" style="color: #cc99ff;">WEIGHT: <span style="color: #ffffff; float: right;">0.000000000000kg</span></div>
        </div>

        <div style="flex: 1; min-width: 250px;">
            <h3 id="cv-title" style="color: #ffffff; margin: 0 0 10px 0; font-size: 24px; letter-spacing: 0.5px;">seevee !</h3>
            <p id="cv-text" style="color: #aaaaaa; margin: 0 0 20px 0; font-size: 19px; line-height: 1.4; font-style: normal;">
                An institution-driven logbook of directions not to take. Extracting it to your local storage device will alter your current inventory space.
            </p>
        </div>
    </div>

    <div style="text-align: right; margin-top: 15px; border-top: 1px solid #222222; padding-top: 15px;">
        <a href="/Spadoni.cv.pdf" download="Spadoni.cv.pdf" id="cv-button" style="display: inline-block; background-color: #000000; color: #ff3366; text-decoration: none; padding: 6px 16px; font-size: 22px; font-weight: bold; border: 2px solid #ff3366; cursor: pointer; transition: all 0.1s ease;">
            ▶ DISCHARGE FILE_
        </a>
    </div>
</div>

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


<style>
@keyframes blink { 0%, 100% { opacity: 1; } 50% { opacity: 0; } }
</style>

<div style="display: flex; justify-content: space-around; margin-top: 30px; font-family: 'VT323', monospace;">
    <a href="https://orcid.org/0009-0007-3169-4745" style="color: #cc99ff; text-decoration: none; text-align: center;">
        <div style="font-size: 30px;">🚪</div>
        [ ORCID ]
    </a>
    <a href="https://scholar.google.com/citations?hl=en&view_op=list_works&authuser=1&gmla=ACrTK9XNfJz_kbQZqUWRSu06PhieRV6jyxj8Lp5T5ebYtujT5Fb9ynraSrZF906P-fRLgB652-i2XOpF9MEl7w&user=byBWnlAAAAAJ" style="color: #cc99ff; text-decoration: none; text-align: center;">
        <div style="font-size: 30px;">👁️</div>
        [ SCHOLAR ]
    </a>
    <a href="nowhere" style="color: #cc99ff; text-decoration: none; text-align: center;">
        <div style="font-size: 30px;">💼</div>
        [ INTERFACE ]
    </a>
</div>

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
        document.body.innerHTML = "<div style='text-align:center; margin-top:20%; font-family:sans-serif;'><p>You shouldn't have done that.</p></div>";
    } else {
        document.body.style.backgroundColor = "#222"; // Just makes the room slightly darker
    }
});
</script>
