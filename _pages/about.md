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

<div style="margin-top: -1.5em;"></div>

<h1 id="typing-heading"><span id="typed-text"></span><span id="cursor" style="border-right: 2px solid #000; animation: blink 0.7s steps(1) infinite;">&nbsp;</span></h1>

<style>
@keyframes blink {
  0%, 100% { border-color: #000; }
  50% { border-color: transparent; }
}
#typing-heading {
  min-height: 1.2em;
}
#cursor {
  margin-left: 1px;
  font-weight: normal;
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

I am a fifth-year Ph.D. candidate in Economics at the University of California San Diego.<br> 
I also serve as the manager of the <a href="https://econlab.ucsd.edu/" target="_blank">UC San Diego Economics Laboratory (EconLab)</a>.
<!-- Prior to UC San Diego, I earned an M.A. in Economics from Central European University. -->

<strong>I will be on the Economics Job Market 2026-2027.</strong>

My primary fields are experimental economics and behavioral economics.<br> 
I am fortunate to be advised by <a href="https://sites.google.com/site/emanuelvespa/" target="_blank">Emanuel Vespa</a> and <a href="https://econweb.ucsd.edu/~itrevino/" target="_blank">Isabel Trevino</a>.<br>
<!-- In particular, I use laboratory experiments to study how people learn by observing others’ choices. I also work on topics related to student mental health by running studies in the field.  -->

<div style="margin-top: 0.8em;">
  <a href="/files/CV_Alisher_2026_03.pdf" target="_blank" style="display:inline-flex; align-items:center; gap:5px; padding:6px 16px; border:1px solid #ccc; border-radius:4px; color:#000 !important; text-decoration:none !important; font-size:0.9em; transition:all 0.2s ease-in-out; background:transparent; font-family:inherit;" onmouseover="this.style.borderColor='#7B0000'; this.style.color='#7B0000';" onmouseout="this.style.borderColor='#ccc'; this.style.color='#000';"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Curriculum Vitae (CV)</a>
</div>


<!-- You can find the pronunciation of my first name [here](https://www.howtopronounce.com/alisher#google_vignette). -->

Conference Travel
------
Aug 6-7, 2026 — Stanford Institute for Theoretical Economics (<a href="https://economics.stanford.edu/events/site-2026/session-6-experimental-economics" target="_blank">SITE</a>) Experimental Economics Conference, Stanford CA<br>
July 14-17, 2026 — Economic Science Association (<a href="https://sites.google.com/view/esa2026la/home?authuser=0" target="_blank">ESA</a>) World Meeting, Los Angeles CA<br>
June 28 - July 7, 2026 — Russell Sage Foundation (<a href="https://laibson.scholars.harvard.edu/rsfcamp" target="_blank">RSF</a>) Summer Institute in Behavioral Economics, Dedham MA<br>
June 18-19, 2026 — Caltech Workshop in Theory-Based Experiments (<a href="https://lindeinstitute.caltech.edu/research/ctess/ctess-events" target="_blank">CTESS</a>), Los Angeles CA<br>
Mar 19-21, 2026 — Southwest Economic Theory Conference (<a href="https://gregcleo.com/files/swet_2026_program.pdf" target="_blank">SWET</a>), Loyola Marymount University<br>

Nov 7-8, 2025 — Behavioral and Experimental Student Conference, UC Santa Barbara<br>
Oct 24, 2025 — Los Angeles Experiments (<a href="https://www.anderson.ucla.edu/faculty-research/behavioral-decision-making/los-angeles-experiments-lax-workshop#tab-agenda/" target="_blank">LAX</a>) Workshop, UCLA Anderson (participant)<br>
Oct 10-12, 2025 — Economic Science Association (<a href="http://w3.econlab.arizona.edu/esa2025/" target="_blank">ESA</a>) North American Meeting, Tucson AZ<br>
Sep 18–19, 2025 — Advances with Field Experiments Conference (<a href="https://economics.uchicago.edu/advances-with-field-experiments-conference" target="_blank">AFE</a>), UChicago<br>
Sep 13–17, 2025 — The Chicago School in Experimental Economics (<a href="https://voices.uchicago.edu/jlist/the-chicago-school-in-experimental-economics-2025/" target="_blank">CSEE</a>), UChicago<br>
July 30 – Aug 1, 2025 — American Economic Association Mentoring Conference, Chicago<br>
May 27–30, 2025 — Behavioral Economics Annual Meeting (<a href="https://blogs.cornell.edu/beam/beam2025/" target="_blank">BEAM</a>), UC Berkeley (participant)


Contact Info
------
Email: [abatmanov@ucsd.edu](mailto:abatmanov@ucsd.edu)\
University of California San Diego\
Brian C. Malk Hall, Office 461\
9500 Gilman Dr, San Diego, CA 92093