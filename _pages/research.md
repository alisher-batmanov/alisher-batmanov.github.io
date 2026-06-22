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
  margin-top: 2.5em;
}
.research-section-label:first-of-type {
  margin-top: 0;
}
.paper-block {
  margin-bottom: 2.2em;
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
document.addEventListener('DOMContentLoaded', function() {
  if (window.location.hash === '#show-jmp') {
    var abs = document.getElementById('mm-abstract');
    var btn = document.getElementById('btn-mm-abs');
    if (abs) abs.classList.add('show');
    if (btn) btn.classList.add('active');
    window.scrollTo(0, 0);
  }
});
</script>

<div class="page-pull-up"></div>
# Research
{% include base_path %}

<div class="research-section-label">Working Papers</div>

<div class="paper-block" id="jmp">
  <div class="paper-title">"Fragile Learning From Others" — Job Market Paper</div>
  <div class="paper-status"><em>Draft available upon request</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-mm-abs" onclick="toggleSection('mm-abstract','btn-mm-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-mm-pres" onclick="toggleSection('mm-pres','btn-mm-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
  </div>
  <div class="paper-abstract" id="mm-abstract">
    Behavioral biases in decision-making are widespread and often persist even in the presence of feedback diagnostic of optimal behavior. This paper examines whether exposure to others' decisions can correct initial misconceptions and facilitate learning in an environment where departures from the theoretical benchmark arise from neglecting an informative signal in a worker hiring task. Using a laboratory experiment, I show that exposure to optimal behavior substantially improves decision quality. The analysis of the underlying mechanisms suggests that this improvement is not driven by mechanical imitation alone, as subjects respond asymmetrically to the quality of observed choices, nor entirely by the richer feedback environment that social exposure generates. I then evaluate the retention and transfer of these learning gains beyond the period of exposure and find that, for most subjects, the improvements are fragile. Comparing the effects of social exposure to those of explicit guidance further underscores the limits of observational learning as a policy tool. These findings highlight the dual role of social learning: while it can enhance decision-making, it can also generate imitation behavior that fails to generalize beyond the observed context.
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
  <div class="paper-title">"Beliefs, Information Sharing, and Mental Health Care Use Among University Students"</div>
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
    We study how individuals learn to make optimal decisions when doing so requires conditioning on payoff-relevant contingencies, as prescribed by theory. Using a laboratory experiment, we contrast learning across two environments: one in which irrelevant contingencies are excluded by design, and another in which they occur with positive probability but never affect outcomes. At baseline, 4 out of 5 subjects make a suboptimal choice. With experience and feedback, 71% of participants in the zero-probability environment switch to the optimal choice, compared to 49% in the setting where such contingencies remain present, indicating that engagement with payoff-irrelevant situations hinders learning. Participants in the zero-probability treatment are also more likely to report correct beliefs about the task environment and, conditional on holding accurate beliefs, are 15 percentage points more likely to make an optimal choice. These findings suggest that in many environments that necessitate reasoning through contingencies, not engaging with events that are irrelevant to the outcome can significantly ease learning and lead to optimal behavior.
  </div>
  <div class="paper-presentations" id="lct-pres">
    <ul>
      <li>Economic Science Association (ESA) North American Meeting (Tucson 2025)</li>
      <li>Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)</li>
    </ul>
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Experiment on Narratives and Information in Persuasion"</div>
  <div class="paper-authors">Alisher Batmanov and <a href="https://sites.google.com/view/bridgetgalaty" target="_blank">Bridget Galaty</a></div>
  <div class="paper-status"><em>Draft coming soon!</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-narr-abs" onclick="toggleSection('narr-abstract','btn-narr-abs')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Abstract</span>
    <span class="paper-btn" id="btn-narr-pres" onclick="toggleSection('narr-pres','btn-narr-pres')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg> Presentations</span>
  </div>
  <div class="paper-abstract" id="narr-abstract">
    We experimentally study how the elements of cheap-talk communication and narrative persuasion interact in the same setting. In an inference task, receivers observe a dataset and make predictions after receiving a message from a sender who may have additional information and who communicates either through a simple recommendation or a narrative explanation. By varying the sender's information and communication mode, we isolate the effects of new information versus new interpretation. We examine how the effects of these message types differ based on whether the sender and receiver have aligned or misaligned preferences, allowing us to test predictions from models of strategic information transmission and to assess when persuasion works through informational advantage versus framing. We find that receivers' guesses land roughly midway between the true grade and the sender's recommendation. Both informational advantage and narratives increase persuasive power, though information plays a much stronger role: a sender with an informational advantage moves guesses approximately 39% closer to their recommendation, while adding a narrative under equal information yields a smaller, statistically insignificant effect of approximately 9%. This asymmetry holds across all levels of task complexity — varying the number of variables and conditional versus unconditional DGP structure. When preferences are aligned, both channels move guesses more strongly toward the recommendation, but information continues to matter more.
  </div>
  <div class="paper-presentations" id="narr-pres">
    <ul>
      <li>Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)*</li>
    </ul>
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Descriptive Simplicity in Strategyproof Matching Mechanisms"</div>
  <div class="paper-status"><em>Designing experiment</em></div>
</div>


<div class="research-section-label">Other Published Papers</div>

<div class="paper-block">
  <div class="paper-title">"Reproducibility and robustness of economics and political science research"</div>
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

<div style="margin-top: 2em; font-size: 0.9em; color: #888;">* – presentation by co-author</div>
