---
layout: archive
title:
nav_order: 1
permalink: /research/
author_profile: true
---

<style>
/* ── Research page styles ── */
.research-section-label {
  font-size: 0.75em;
  font-weight: 600;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 1.2em;
  margin-top: 2em;   /* = 1.5em of body text, same as the gap after the intro */
}
.research-section-label:first-of-type {
  margin-top: 0;
}
.research-section-label.first-label {
  margin-top: 0;
}
.paper-block {
  margin-bottom: 0;
}
.paper-block + .paper-block {
  margin-top: 1.5em;   /* same gap as between sections (label margin-top 2em x 0.75em font = 1.5em) */
}
.paper-title {
  font-size: 1.05em;
  font-weight: 700;
  color: #7B0000;
  line-height: 1.4;
}
.paper-authors {
  margin-top: 0.2em;
  color: #000;
}
.paper-authors a {
  color: #000 !important;
}
.paper-authors a:hover {
  color: #7B0000 !important;
}
.paper-journal {
  margin-top: 0.15em;
  font-weight: 600;
}
.paper-status {
  margin-top: 0.15em;
}
.paper-buttons {
  margin-top: 0.5em;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  line-height: 1;
}
.paper-btn {
  display: inline-flex;
  align-items: center;
  gap: 4px;
  padding: 5px 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  color: #000 !important;
  text-decoration: none !important;
  font-size: 0.82em;
  cursor: pointer;
  transition: all 0.2s ease-in-out;
  background: transparent;
  font-family: inherit;
}
.paper-btn:hover {
  border-color: #7B0000;
  color: #7B0000 !important;
}
.paper-btn.active {
  border-color: #7B0000;
  color: #7B0000 !important;
}
.paper-btn svg {
  flex-shrink: 0;
}
.paper-abstract {
  display: none;
  margin-top: 0.6em;
  padding: 0.8em 1em;
  background: rgba(123,0,0,0.04);
  border-left: 3px solid rgba(123,0,0,0.2);
  font-size: 0.95em;
  line-height: 1.6;
}
.paper-abstract.show {
  display: block;
}
.paper-presentations {
  display: none;
  margin-top: 0.5em;
  padding: 0.6em 1em;
  background: rgba(123,0,0,0.04);
  border-left: 3px solid rgba(123,0,0,0.2);
  font-size: 0.9em;
  line-height: 1.6;
}
.paper-presentations.show {
  display: block;
}
.paper-presentations ul {
  margin: 0;
  padding-left: 1.2em;
}
.paper-presentations ul li {
  margin-bottom: 0.3em;
}
.paper-resources {
  display: none;
  margin-top: 0.5em;
  padding: 0.6em 1em;
  background: rgba(123,0,0,0.04);
  border-left: 3px solid rgba(123,0,0,0.2);
}
.paper-resources.show {
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
}
</style>

<script>
function toggleSection(id, btnId) {
  var el = document.getElementById(id);
  var btn = btnId ? document.getElementById(btnId) : null;
  if (el) {
    el.classList.toggle('show');
    if (btn) btn.classList.toggle('active');
  }
}
function openJmpIfNeeded() {
  if (window.location.hash === '#show-jmp') {
    var abs = document.getElementById('mm-abstract');
    var btn = document.getElementById('btn-mm-abs');
    var pres = document.getElementById('mm-pres');
    var btnPres = document.getElementById('btn-mm-pres');
    if (abs) abs.classList.add('show');
    if (btn) btn.classList.add('active');
    if (pres) pres.classList.add('show');
    if (btnPres) btnPres.classList.add('active');
    window.scrollTo(0, 0);
  }
}
openJmpIfNeeded();
window.addEventListener('load', openJmpIfNeeded);
window.addEventListener('hashchange', openJmpIfNeeded);
</script>

<div class="page-pull-up"></div>
# Research
{% include base_path %}

<div style="margin-bottom: 1.5em; line-height: 1.7;">

My research is primarily in <strong>experimental and behavioral economics</strong>, with additional interests in development economics and economic theory. I mainly focus on how people learn to make better decisions, and why the resulting improvements often prove fragile. <strong>In the laboratory</strong>, I design controlled experiments that examine how individuals learn from exposure to others' behavior and from their own experience with the decision environment. <strong>In field settings</strong>, I study how inaccurate beliefs and learning from peers shape university students' decisions to seek mental health care.

</div>

<!-- TEMPORARILY HIDDEN: Research Statement button
<div onclick="window.open('/files/Alisher_Research_Statement.pdf','_blank');" onmouseover="this.style.boxShadow='inset 0 0 0 1px #7B0000';" onmouseout="this.style.boxShadow='inset 0 0 0 1px #ccc';" style="display: flex; align-items: center; gap: 16px; padding: 14px 20px; box-shadow: inset 0 0 0 1px #ccc; border-radius: 6px; cursor: pointer; margin-bottom: 2.5em; transition: all 0.2s ease-in-out;">
  <svg width="30" height="30" viewBox="0 0 24 24" fill="none" stroke="#7B0000" stroke-width="1.4" stroke-linecap="round" stroke-linejoin="round" style="flex-shrink: 0;"><line x1="3" y1="2.8" x2="3" y2="21"/><line x1="3" y1="21" x2="21.5" y2="21"/><path d="M1.9 4.3 L3 2.3 L4.1 4.3" fill="none"/><path d="M19.7 19.9 L21.7 21 L19.7 22.1" fill="none"/><line x1="5" y1="18.5" x2="21" y2="6" stroke-width="1.1"/><circle cx="5.6" cy="14.6" r="0.75" fill="#7B0000" stroke="none"/><circle cx="6.6" cy="19.6" r="0.75" fill="#7B0000" stroke="none"/><circle cx="8.2" cy="12.1" r="0.75" fill="#7B0000" stroke="none"/><circle cx="9.6" cy="17.9" r="0.75" fill="#7B0000" stroke="none"/><circle cx="10.4" cy="14.9" r="0.75" fill="#7B0000" stroke="none"/><circle cx="11.4" cy="8.9" r="0.75" fill="#7B0000" stroke="none"/><circle cx="13.1" cy="16.6" r="0.75" fill="#7B0000" stroke="none"/><circle cx="14.2" cy="11.3" r="0.75" fill="#7B0000" stroke="none"/><circle cx="15.4" cy="15.1" r="0.75" fill="#7B0000" stroke="none"/><circle cx="16.4" cy="6.6" r="0.75" fill="#7B0000" stroke="none"/><circle cx="18.4" cy="10.9" r="0.75" fill="#7B0000" stroke="none"/><circle cx="19.3" cy="4.6" r="0.75" fill="#7B0000" stroke="none"/><circle cx="20.5" cy="8.9" r="0.75" fill="#7B0000" stroke="none"/></svg>
  <div style="flex: 1;">
    <div style="font-weight: 700; color: #7B0000;">Research Statement</div>
    <div style="font-size: 0.88em; color: #555; margin-top: 2px;">Research agenda, job market paper, working papers, and ongoing projects.</div>
  </div>
  <div style="font-weight: 700; color: #7B0000; white-space: nowrap; font-size: 0.95em;">View PDF &rarr;</div>
</div>
-->

<div class="research-section-label first-label">Job Market Paper</div>

<div class="paper-block" id="jmp">
  <div class="paper-title" style="cursor: pointer;" onclick="window.open('/files/Alisher_JMP.pdf','_blank');" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">"Fragile Learning From Others" <span style="font-size: 0.85em;">[PDF]</span></div>
  <div class="paper-status"><em>Updated regularly</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-mm-abs" onclick="toggleSection('mm-abstract','btn-mm-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-mm-pres" onclick="toggleSection('mm-pres','btn-mm-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
  </div>
  <div class="paper-abstract" id="mm-abstract">
    Behavioral biases in decision-making are widespread and often persist despite experience and transparent feedback. This paper examines whether exposure to others' optimal decisions can correct initial misconceptions and facilitate learning in an environment where departures from the theoretical benchmark arise from neglecting an informative signal in a worker hiring task. Using a laboratory experiment, I show that such exposure substantially improves the quality of one's own decisions. The analysis of the underlying mechanisms shows that this improvement is not driven by mechanical imitation, as responses to exposure are <em>asymmetric</em> in the quality of observed choices, pointing instead to selective adoption of observed behavior. Adopting others' decisions selectively, however, need not reflect an understanding of <em>why</em> those decisions are optimal, so I further evaluate the transfer of these learning gains to a modified environment once exposure ends. The main result of the paper is that learning from others is <em>fragile</em>: the improvements do not survive a change in the environment's primitives, and the acquired gains from exposure dissipate entirely. Comparing these effects with those of explicit guidance further underscores the limits of social exposure as an effective policy tool. These findings highlight the dual role of observational learning: while it can enhance the incidence of optimal behavior, the improvements it generates often fail to generalize beyond the observed context.
  </div>
  <div class="paper-presentations" id="mm-pres">
    <ul>
      <li>SITE Experimental Economics Conference (Stanford 2026)</li>
      <li>CTESS Workshop in Theory-Based Experiments (Caltech 2026)</li>
      <li>Economic Science Association (ESA) World Meeting (Los Angeles 2026)</li>
      <li>Southwest Economic Theory Conference (Loyola Marymount 2026)</li>
      <li>American Economic Association Mentoring Conference (Chicago 2025)</li>
      <li>Economic Science Association (ESA) North American Meeting (Columbus 2024)</li>
      <li>Behavioral &amp; Experimental Economics Student Conference (Caltech 2024)</li>
      <li>Los Angeles Experiments (LAX) Conference Poster (Caltech 2024)</li>
    </ul>
  </div>
</div>


<div class="research-section-label">Published Papers</div>

<div class="paper-block">
  <div class="paper-title" style="cursor: pointer;" onclick="window.open('/files/Batmanov_et_al_2026_JDE.pdf','_blank');" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">"Beliefs, Information Sharing, and Mental Health Care Use Among University Students" <span style="font-size: 0.85em;">[PDF]</span></div>
  <div class="paper-authors">Alisher Batmanov, <a href="https://sites.google.com/view/idagri/home?authuser=0" target="_blank">Ida Grigoryeva</a>, <a href="https://www.bruno-calderon.com" target="_blank">Bruno Calderon</a>, <a href="https://robertoglz.github.io" target="_blank">Roberto Gonz&aacute;lez</a> and <a href="https://research.tec.mx/vivo-tec/display/PID_316616" target="_blank">Alejandro Guardiola Ramires</a></div>
  <div class="paper-journal">Journal of Development Economics (2026)</div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-mh-abs" onclick="toggleSection('mh-abstract','btn-mh-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-mh-pres" onclick="toggleSection('mh-pres','btn-mh-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
    <span class="paper-btn" id="btn-mh-res" onclick="toggleSection('mh-resources','btn-mh-res')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg> Resources</span>
  </div>
  <div class="paper-abstract" id="mh-abstract">
    This paper investigates the role of beliefs and stigma in shaping students' use of professional mental health services at a large private university in Mexico, where supply-side barriers are minimal and services are readily accessible. In a survey experiment with 680 students, we find that nearly 50% of students in distress do not receive professional mental health support despite a high level of awareness and perceived effectiveness, constituting a substantial treatment gap. We document stigmatized beliefs and misconceptions correlated with the treatment gap. As three-quarters of students incorrectly believe that those in distress perform worse academically and that the majority of students going to therapy are in severe distress, we implement an information intervention to correct these beliefs. We find that it increases students' sharing of on-campus mental health resources with peers and encourages them to recommend these resources when advising a friend in distress. Interestingly, we find that it lowers respondents' willingness to pay for private therapy at the end of the intervention. Yet, this effect does not translate into a long-run reduction in self-reported therapy use six months after the experiment, with prior therapy users showing increased off-campus take-up.
  </div>
  <div class="paper-presentations" id="mh-pres">
    <ul>
      <li>Advances with Field Experiments Conference (UChicago 2025)</li>
      <li>NHH Field Experiments Conference (Bergen 2024)*</li>
      <li>Behavioral &amp; Experimental Economics Student Conference (Caltech 2023)</li>
    </ul>
  </div>
  <div class="paper-resources" id="mh-resources">
    <a class="paper-btn" href="https://www.sciencedirect.com/science/article/pii/S030438782500197X" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Journal article</a>
    <a class="paper-btn" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5192345#" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> SSRN article</a>
    <a class="paper-btn" href="https://x.com/Alisher_BV/status/2048283104641732832?s=20" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Thread on X</a>
  </div>
</div>


<div class="paper-block">
  <div class="paper-title" style="cursor: pointer;" onclick="window.open('https://www.econstor.eu/bitstream/10419/338965/1/I4R-DP287.pdf','_blank');" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">"Reproducibility and Robustness of Economics and Political Science Research" <span style="font-size: 0.85em;">[PDF]</span></div>
  <div class="paper-authors">Meta paper with <a href="https://sites.google.com/site/abelbrodeur/" target="_blank">Abel Brodeur</a>, et al.</div>
  <div class="paper-journal">Nature (2026)</div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-nat-abs" onclick="toggleSection('nat-abstract','btn-nat-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-nat-res" onclick="toggleSection('nat-resources','btn-nat-res')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg> Resources</span>
  </div>
  <div class="paper-abstract" id="nat-abstract">
    Science aspires to be cumulative. Reproducibility efforts strengthen science by testing the reliability of published findings, promoting self-correction, and informing policy-making. Computational reproductions, whereby independent researchers reproduce the results of published studies, are an essential diagnostic tool. Such efforts should have greater visibility. However, little social science reproduction and robustness has been conducted at scale. Here we reproduced original analyses and conducted robustness checks of 110 articles that were published in leading economics and political science journals with mandatory data and code sharing policies. We found that more than 85% of published claims were computationally reproducible. In robustness checks, our reanalyses showed that 72% of statistically significant estimates remain significant and in the same direction, and the median reproduced effect size is nearly the same as the originally published effect size (that is, 99% of the published effect size). Additionally, 6 independent research teams examined 12 pre-specified hypotheses about determinants of robustness. Research teams with more experience found lower levels of robustness, and robustness did not correlate with author characteristics or data availability.
  </div>
  <div class="paper-resources" id="nat-resources">
    <a class="paper-btn" href="https://www.nature.com/articles/s41586-026-10251-x" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Journal article</a>
    <a class="paper-btn" href="https://www.econstor.eu/handle/10419/276253" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Replication paper</a>
  </div>
</div>


<div class="research-section-label">Working Papers</div>

<div class="paper-block">
  <div class="paper-title" style="cursor: pointer;" onclick="window.open('/files/BG_working_paper.pdf','_blank');" onmouseover="this.style.textDecoration='underline';" onmouseout="this.style.textDecoration='none';">"Information versus Interpretation: Evidence from an Experiment on Persuasion" <span style="font-size: 0.85em;">[PDF]</span></div>
  <div class="paper-authors">Alisher Batmanov and <a href="https://sites.google.com/view/bridgetgalaty" target="_blank">Bridget Galaty</a></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-narr-abs" onclick="toggleSection('narr-abstract','btn-narr-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-narr-pres" onclick="toggleSection('narr-pres','btn-narr-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
  </div>
  <div class="paper-abstract" id="narr-abstract">
    We experimentally study the relative persuasive effects of having more information versus having the same information but complementing the message with an explanation in a strategic communication environment. Senders recommend an action, and Receivers make a prediction based on a dataset they observe together with the Sender's recommendation. By varying the Sender's information and message format in a 2-by-2 design, we separate the effect of new information from that of new interpretation. We find that an informational advantage is the dominant channel: messages from better-informed Senders pull Receivers' guesses substantially closer to the recommendation, while adding an explanation to a message yields only a small insignificant effect, with or without an informational advantage. This asymmetry persists at every level of task difficulty. When the preferences of Senders and Receivers are aligned, information remains the stronger channel, though explanations now add marginal persuasive power. Consistent with these responses, when Receivers choose which type of message to receive, a majority prefer one from a better-informed Sender over one with an explanation, and the Receivers who prefer the explanation are the least responsive to information.
  </div>
  <div class="paper-presentations" id="narr-pres">
    <ul>
      <li>Economic Science Association (ESA) World Meeting (Los Angeles 2026)*</li>
      <li>Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)*</li>
    </ul>
  </div>
</div>


<div class="research-section-label">Work in Progress</div>

<div class="paper-block">
  <div class="paper-title">"Learning to Ignore Irrelevant Contingencies: An Experiment"</div>
  <div class="paper-authors">Alisher Batmanov, <a href="https://sites.google.com/site/jbkimecon/" target="_blank">Jeongbin Kim</a> and <a href="https://sites.google.com/site/emanuelvespa/" target="_blank">Emanuel Vespa</a></div>
  <div class="paper-status"><em>Draft coming soon!</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-lct-abs" onclick="toggleSection('lct-abstract','btn-lct-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-lct-pres" onclick="toggleSection('lct-pres','btn-lct-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
  </div>
  <div class="paper-abstract" id="lct-abstract">
Identifying and discarding irrelevant contingencies is a crucial component of theoretical analysis. A contingency may be irrelevant because it occurs with probability zero or because the agent's payoff is unaffected by their choice. While the literature has documented that people often struggle to ignore irrelevant contingencies, it remains unclear whether difficulties with learning to ignore them depend on what makes them irrelevant. In this paper, we design an experiment to address this question. Our main finding is that participants are more likely to learn to ignore probability-zero contingencies than contingencies in which their payoff is independent of their choice.
</div>
  <div class="paper-presentations" id="lct-pres">
    <ul>
      <li>Economic Science Association (ESA) North American Meeting (Tucson 2025)</li>
      <li>Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)</li>
    </ul>
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Descriptive Simplicity in Strategyproof Matching Mechanisms"</div>
  <div class="paper-status"><em>Designing experiment</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-ds-abs" onclick="toggleSection('ds-abstract','btn-ds-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
  </div>
  <div class="paper-abstract" id="ds-abstract">
    Although strategyproof matching mechanisms such as deferred acceptance (DA) and serial dictatorship (SD) guarantee that straightforward reporting is a dominant strategy, empirical evidence consistently documents widespread deviations from truthful behavior. This raises a fundamental question: are such deviations driven by strategic incentives, or by misunderstanding of the mechanism's informational structure? In this project, I examine whether alternative descriptions of strategyproof mechanisms can reduce cognitive burden and improve straightforward reporting. Rather than altering the underlying mechanism, I focus on how it is explained to participants. Specifically, I study interventions that highlight counterfactual outcomes under alternative rank-order lists, allowing participants to observe for themselves that strategizing cannot improve their payoff. By making the logic of strategyproofness transparent through concrete examples, the intervention aims to improve participants' understanding of dominant-strategy incentives and increase truthful reporting.
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Learning About Therapy From Friends: Conversations and Treatment Take-Up Among Students"</div>
  <div class="paper-authors">Alisher Batmanov and <a href="https://sites.google.com/view/idagri/home?authuser=0" target="_blank">Ida Grigoryeva</a></div>
  <div class="paper-status"><em>Designing experiment</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-tf-abs" onclick="toggleSection('tf-abstract','btn-tf-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
  </div>
  <div class="paper-abstract" id="tf-abstract">
    Many university students in mental distress do not seek professional help, even where counseling is free and widely regarded as effective. Information interventions that correct misperceptions about therapy have been shown to increase conversations about mental health and the sharing of resources among peers, yet their effects on individual help-seeking remain limited. In this project, we ask whether learning from friends' therapy-use experience can shift help-seeking itself. We propose a field experiment at a large university with free on-campus counseling, in which students attend small group sessions with their peers. In treated groups, a structured conversation invites participants to share how they or people close to them came to seek therapy and what the experience was like, while control groups discuss an unrelated campus topic. Our primary outcome is subsequent use of counseling services. To our knowledge, this is the first experiment to test whether learning from the lived experiences of peers moves students from talking about mental health to seeking care.
  </div>
</div>


<div style="margin-top: 2em; font-size: 0.9em; color: #888;">* – presentation by co-author</div>
