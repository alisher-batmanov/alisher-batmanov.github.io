---
layout: archive
permalink: /
title: 
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="page-pull-up"></div>

<h1 id="typing-heading"><span id="typed-text"></span></h1>

<style>
@keyframes blink {
  0%, 100% { opacity: 1; }
  50% { opacity: 0; }
}
#typing-heading {
  min-height: 1.2em;
}
#typed-text::after {
  content: '';
  display: inline-block;
  width: 2px;
  height: 0.85em;
  background: #000;
  margin-left: 2px;
  vertical-align: text-bottom;
  animation: blink 0.7s steps(1) infinite;
}
</style>

<script>
(function() {
  const phrases = ["Welcome to my website!", "Thanks for visiting!", "Take a look around!"];
  const typedEl = document.getElementById("typed-text");
  const typeSpeed = 90;
  const deleteSpeed = 50;
  const pauseAfterType = 1800;
  const pauseAfterDelete = 400;
  let phraseIndex = 0;
  let charIndex = 0;

  function typeChar() {
    const current = phrases[phraseIndex];
    if (charIndex < current.length) {
      typedEl.textContent += current.charAt(charIndex);
      charIndex++;
      setTimeout(typeChar, typeSpeed);
    } else {
      setTimeout(deleteChar, pauseAfterType);
    }
  }

  function deleteChar() {
    if (charIndex > 0) {
      typedEl.textContent = phrases[phraseIndex].substring(0, charIndex - 1);
      charIndex--;
      setTimeout(deleteChar, deleteSpeed);
    } else {
      phraseIndex = (phraseIndex + 1) % phrases.length;
      setTimeout(typeChar, pauseAfterDelete);
    }
  }

  typeChar();
})();
</script>

I am a fifth-year Ph.D. candidate in Economics at the University of California San Diego.<br class="desktop-only"> I also serve as the manager of the <a href="https://econlab.ucsd.edu/" target="_blank">UC San Diego Economics Laboratory (EconLab)</a>.
<!-- Prior to UC San Diego, I earned an M.A. in Economics from Central European University. -->

<strong>I will be on the Economics Job Market 2026-2027.</strong>

<div style="margin-top: 0.8em; margin-bottom: 0.2em; display: flex; flex-wrap: wrap; gap: 6px; padding-bottom: 2px;">
  <a href="/files/CV_Alisher_2026_07.pdf" target="_blank" style="display:inline-flex; align-items:center; gap:5px; padding:6px 16px; border:1px solid #ccc; border-radius:4px; color:#000 !important; text-decoration:none !important; font-size:0.9em; transition:all 0.2s ease-in-out; background:transparent; font-family:inherit;" onmouseover="this.style.borderColor='#7B0000'; this.style.color='#7B0000';" onmouseout="this.style.borderColor='#ccc'; this.style.color='#000';"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Curriculum Vitae (CV)</a>
  <a href="/research/#show-jmp" style="display:inline-flex; align-items:center; gap:5px; padding:6px 16px; border:1px solid #ccc; border-radius:4px; color:#000 !important; text-decoration:none !important; font-size:0.9em; transition:all 0.2s ease-in-out; background:transparent; font-family:inherit;" onmouseover="this.style.borderColor='#7B0000'; this.style.color='#7B0000';" onmouseout="this.style.borderColor='#ccc'; this.style.color='#000';"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg> Job Market Paper (coming soon)</a>
</div>

My primary fields are Experimental Economics and Behavioral Economics. I am also interested in Development Economics and Economic Theory. I am fortunate to be advised by <a href="https://sites.google.com/site/emanuelvespa/" target="_blank">Prof. Emanuel Vespa</a> and <a href="https://econweb.ucsd.edu/~itrevino/" target="_blank">Prof. Isabel Trevino</a>.

In my research, I use laboratory experiments to study systematic biases in decision-making, focusing on how people learn from feedback and from observing others' behavior. Specifically, I examine when behavioral improvements reflect genuine understanding versus superficial imitation, and how the structure of decision environments can foster more effective learning. In the field settings, I also study miscalibrated beliefs related to mental health stigma among university students and how targeted information interventions can correct them.


<!-- You can find the pronunciation of my first name [here](https://www.howtopronounce.com/alisher#google_vignette). -->

Conference Travel
------
<ul class="conf-list">
  <li>Aug 6-7, 2026 — <a href="https://economics.stanford.edu/events/site-2026/session-6-experimental-economics" target="_blank">Stanford Institute for Theoretical Economics (SITE) Experimental Economics Conference, Stanford CA</a></li>
  <li>July 14-17, 2026 — <a href="https://sites.google.com/view/esa2026la/home?authuser=0" target="_blank">Economic Science Association (ESA) World Meeting, Los Angeles CA</a></li>
  <li>June 28 - July 7, 2026 — <a href="https://laibson.scholars.harvard.edu/rsfcamp" target="_blank">Russell Sage Foundation (RSF) Summer Institute in Behavioral Economics, Boston MA</a></li>
  <li>June 18-19, 2026 — <a href="https://lindeinstitute.caltech.edu/research/ctess/ctess-events" target="_blank">Caltech Workshop in Theory-Based Experiments (CTESS), Los Angeles CA</a></li>
  <li>Mar 19-21, 2026 — <a href="https://gregcleo.com/files/swet_2026_program.pdf" target="_blank">Southwest Economic Theory Conference (SWET), Loyola Marymount University</a></li>
</ul>

<div style="margin-top: 0.8em;">
  <span id="btn-conf-2025" style="display:inline-flex; align-items:center; gap:5px; padding:5px 12px; border:1px solid #ccc; border-radius:4px; color:#000; text-decoration:none; font-size:0.85em; cursor:pointer; transition:all 0.2s ease-in-out; background:transparent; font-family:inherit;" onclick="var el=document.getElementById('conf-2025');var btn=this;if(el.style.display==='none'){el.style.display='block';btn.style.borderColor='#7B0000';btn.style.color='#7B0000';}else{el.style.display='none';btn.style.borderColor='#ccc';btn.style.color='#000';}">Conferences in 2025</span>
</div>
<div id="conf-2025" style="display:none; margin-top: 0.6em;">
<ul class="conf-list">
  <li>Nov 7-8, 2025 — Behavioral and Experimental Student Conference, UC Santa Barbara</li>
  <li>Oct 24, 2025 — <a href="https://www.anderson.ucla.edu/faculty-research/behavioral-decision-making/los-angeles-experiments-lax-workshop#tab-agenda/" target="_blank">Los Angeles Experiments (LAX) Workshop, UCLA Anderson (participant)</a></li>
  <li>Oct 10-12, 2025 — <a href="http://w3.econlab.arizona.edu/esa2025/" target="_blank">Economic Science Association (ESA) North American Meeting, Tucson AZ</a></li>
  <li>Sep 18–19, 2025 — <a href="https://economics.uchicago.edu/advances-with-field-experiments-conference" target="_blank">Advances with Field Experiments Conference (AFE), UChicago</a></li>
  <li>Sep 13–17, 2025 — <a href="https://voices.uchicago.edu/jlist/the-chicago-school-in-experimental-economics-2025/" target="_blank">The Chicago School in Experimental Economics (CSEE), UChicago</a></li>
  <li>July 30 – Aug 1, 2025 — American Economic Association Mentoring Conference, Chicago</li>
  <li>May 27–30, 2025 — <a href="https://blogs.cornell.edu/beam/beam2025/" target="_blank">Behavioral Economics Annual Meeting (BEAM), UC Berkeley (participant)</a></li>
</ul>
</div>


Contact Info
------
Email: [abatmanov@ucsd.edu](mailto:abatmanov@ucsd.edu)\
University of California San Diego\
Brian C. Malk Hall, Office 461\
9500 Gilman Dr, San Diego, CA 92093
