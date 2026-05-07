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
  color: #B32121;
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
  color: #B32121 !important;
}
.paper-journal {
  margin-top: 0.15em;
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
  border-color: #B32121;
  color: #B32121 !important;
}
.paper-btn .tri {
  font-size: 0.65em;
  transition: transform 0.2s;
  display: inline-block;
}
.paper-btn .tri.open {
  transform: rotate(90deg);
}
.paper-abstract {
  display: none;
  margin-top: 0.6em;
  padding: 0.8em 1em;
  background: rgba(0,0,0,0.02);
  border-left: 3px solid #ddd;
  font-size: 0.95em;
  line-height: 1.6;
}
.paper-abstract.show {
  display: block;
}
.paper-presentations {
  display: none;
  margin-top: 0.5em;
  padding: 0.5em 1em;
  font-size: 0.9em;
  color: #555;
}
.paper-presentations.show {
  display: block;
}
</style>

<script>
function toggleSection(id, btnId) {
  var el = document.getElementById(id);
  var btn = btnId ? document.getElementById(btnId) : null;
  if (el) {
    el.classList.toggle('show');
    if (btn) {
      var tri = btn.querySelector('.tri');
      if (tri) tri.classList.toggle('open');
    }
  }
}
</script>

<div style="margin-top: -1.5em;"></div>
# Research
{% include base_path %}

<div class="research-section-label">Working Papers</div>

<div class="paper-block">
  <div class="paper-title">"Mental Models, Social Learning and Statistical Discrimination: A Laboratory Study" — Job Market Paper</div>
  <div class="paper-status"><em>(draft available upon request)</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-mm-abs" onclick="toggleSection('mm-abstract','btn-mm-abs')"><span class="tri">&#9654;</span> Abstract</span>
    <span class="paper-btn" id="btn-mm-pres" onclick="toggleSection('mm-pres','btn-mm-pres')"><span class="tri">&#9654;</span> Presentations</span>
  </div>
  <div class="paper-abstract" id="mm-abstract">
    Behavioral biases in decision-making are widespread and often persist even in the presence of feedback diagnostic of optimal behavior. This paper examines whether exposure to others' decisions can correct initial misconceptions and facilitate learning in an environment where departures from the theoretical benchmark arise from neglecting an informative signal in a worker hiring task. Using a laboratory experiment, I show that exposure to optimal behavior substantially improves decision quality. The analysis of the underlying mechanisms suggests that this improvement is not driven by mechanical imitation alone, as subjects respond asymmetrically to the quality of observed choices, nor entirely by the richer feedback environment that social exposure generates. I then evaluate the retention and transfer of these learning gains beyond the period of exposure and find that, for most subjects, the improvements are fragile. Comparing the effects of social exposure to those of explicit guidance further underscores the limits of observational learning as a policy tool. These findings highlight the dual role of social learning: while it can enhance decision-making, it can also generate imitation behavior that fails to generalize beyond the observed context.
  </div>
  <div class="paper-presentations" id="mm-pres">
    Southwest Economic Theory Conference (Loyola Marymount University 2026), American Economic Association Mentoring Conference (Chicago 2025), ESA North American Meeting (Columbus 2024), Behavioral &amp; Experimental Economics Student Conference (Caltech 2024), Los Angeles Experiments Conference Poster (Caltech 2024)
  </div>
</div>


<div class="research-section-label">Published Papers</div>

<div class="paper-block">
  <div class="paper-title">"Beliefs, Information Sharing, and Mental Health Care Use Among University Students"</div>
  <div class="paper-authors">Alisher Batmanov, <a href="https://sites.google.com/view/idagri/home?authuser=0" target="_blank">Ida Grigoryeva</a>, <a href="https://www.bruno-calderon.com" target="_blank">Bruno Calderon</a>, <a href="https://robertoglz.github.io" target="_blank">Roberto González</a> and <a href="https://research.tec.mx/vivo-tec/display/PID_316616" target="_blank">Alejandro Guardiola Ramires</a></div>
  <div class="paper-journal"><em><strong>Journal of Development Economics</strong></em> <strong>(2026)</strong></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-mh-abs" onclick="toggleSection('mh-abstract','btn-mh-abs')"><span class="tri">&#9654;</span> Abstract</span>
    <a class="paper-btn" href="https://www.sciencedirect.com/science/article/pii/S030438782500197X" target="_blank">Journal article</a>
    <a class="paper-btn" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5192345#" target="_blank">SSRN</a>
    <a class="paper-btn" href="https://x.com/Alisher_BV/status/2048283104641732832?s=20" target="_blank">X thread</a>
    <span class="paper-btn" id="btn-mh-pres" onclick="toggleSection('mh-pres','btn-mh-pres')"><span class="tri">&#9654;</span> Presentations</span>
  </div>
  <div class="paper-abstract" id="mh-abstract">
    This paper investigates the role of beliefs and stigma in shaping students' use of professional mental health services at a large private university in Mexico, where supply-side barriers are minimal and services are readily accessible. In a survey experiment with 680 students, we find that nearly 50% of students in distress do not receive professional mental health support despite a high level of awareness and perceived effectiveness, constituting a substantial treatment gap. We document stigmatized beliefs and misconceptions correlated with the treatment gap. As three-quarters of students incorrectly believe that those in distress perform worse academically and that the majority of students going to therapy are in severe distress, we implement an information intervention to correct these beliefs. We find that it increases students' sharing of on-campus mental health resources with peers and encourages them to recommend these resources when advising a friend in distress. Interestingly, we find that it lowers respondents' willingness to pay for private therapy at the end of the intervention. Yet, this effect does not translate into a long-run reduction in self-reported therapy use six months after the experiment, with prior therapy users showing increased off-campus take-up.
  </div>
  <div class="paper-presentations" id="mh-pres">
    Advances with Field Experiments Conference (UChicago 2025), NHH Field Experiments Conference (Bergen 2024)*, Behavioral &amp; Experimental Economics Student Conference (Caltech 2023)
  </div>
</div>


<div class="research-section-label">Work in Progress</div>

<div class="paper-block">
  <div class="paper-title">"Learning to Ignore Irrelevant Contingencies: An Experiment"</div>
  <div class="paper-authors">Alisher Batmanov, <a href="https://sites.google.com/site/jbkimecon/" target="_blank">Jeongbin Kim</a> and <a href="https://sites.google.com/site/emanuelvespa/" target="_blank">Emanuel Vespa</a></div>
  <div class="paper-status"><em>Draft coming soon!</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-lct-abs" onclick="toggleSection('lct-abstract','btn-lct-abs')"><span class="tri">&#9654;</span> Abstract</span>
    <span class="paper-btn" id="btn-lct-pres" onclick="toggleSection('lct-pres','btn-lct-pres')"><span class="tri">&#9654;</span> Presentations</span>
  </div>
  <div class="paper-abstract" id="lct-abstract">
    We study how individuals learn to make optimal decisions when doing so requires conditioning on payoff-relevant contingencies, as prescribed by theory. Using a laboratory experiment, we contrast learning across two environments: one in which irrelevant contingencies are excluded by design, and another in which they occur with positive probability but never affect outcomes. At baseline, 4 out of 5 subjects make a suboptimal choice. With experience and feedback, 71% of participants in the zero-probability environment switch to the optimal choice, compared to 49% in the setting where such contingencies remain present, indicating that engagement with payoff-irrelevant situations hinders learning. Participants in the zero-probability treatment are also more likely to report correct beliefs about the task environment and, conditional on holding accurate beliefs, are 15 percentage points more likely to make an optimal choice. These findings suggest that in many environments that necessitate reasoning through contingencies, not engaging with events that are irrelevant to the outcome can significantly ease learning and lead to optimal behavior.
  </div>
  <div class="paper-presentations" id="lct-pres">
    ESA North American Meeting (Tucson 2025), Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Experiment on Narratives and Information in Persuasion"</div>
  <div class="paper-authors">Alisher Batmanov and <a href="https://sites.google.com/view/bridgetgalaty" target="_blank">Bridget Galaty</a></div>
  <div class="paper-status"><em>Collecting data</em></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-narr-abs" onclick="toggleSection('narr-abstract','btn-narr-abs')"><span class="tri">&#9654;</span> Abstract</span>
    <span class="paper-btn" id="btn-narr-pres" onclick="toggleSection('narr-pres','btn-narr-pres')"><span class="tri">&#9654;</span> Presentations</span>
  </div>
  <div class="paper-abstract" id="narr-abstract">
    We study how informational advantage (cheap talk) and narrative persuasion interact in the same experimental setting. In an inference task, receivers observe a dataset and make predictions after receiving a message from a sender who may have additional information and who communicates either through a simple recommendation or an elaborate narrative explanation. By varying the sender's information and communication mode, we isolate the effects of new information versus new interpretation. This allows us to test predictions from models of strategic information transmission and competing narratives, and to assess when persuasion works through informational advantage versus framing.
  </div>
  <div class="paper-presentations" id="narr-pres">
    Behavioral &amp; Experimental Economics Student Conference (UC Santa Barbara 2025)*
  </div>
</div>

<div class="paper-block">
  <div class="paper-title">"Descriptive Simplicity in Strategyproof Matching Mechanisms"</div>
  <div class="paper-status"><em>Designing experiment</em></div>
</div>


<div class="research-section-label">Other Published Papers</div>

<div class="paper-block">
  <div class="paper-title"><a href="https://www.nature.com/articles/s41586-026-10251-x" target="_blank" style="color: #B32121; text-decoration: none;">"Reproducibility and robustness of economics and political science research"</a></div>
  <div class="paper-authors">meta paper with <a href="https://sites.google.com/site/abelbrodeur/" target="_blank">Abel Brodeur</a>, et al.</div>
  <div class="paper-journal"><em><strong>Nature</strong></em> <strong>(2026)</strong></div>
  <div class="paper-buttons">
    <span class="paper-btn" id="btn-nat-abs" onclick="toggleSection('nat-abstract','btn-nat-abs')"><span class="tri">&#9654;</span> Abstract</span>
    <a class="paper-btn" href="https://www.nature.com/articles/s41586-026-10251-x" target="_blank">Journal article</a>
  </div>
  <div class="paper-abstract" id="nat-abstract">
    Science aspires to be cumulative. Reproducibility efforts strengthen science by testing the reliability of published findings, promoting self-correction, and informing policy-making. Computational reproductions, whereby independent researchers reproduce the results of published studies, are an essential diagnostic tool. Such efforts should have greater visibility. However, little social science reproduction and robustness has been conducted at scale. Here we reproduced original analyses and conducted robustness checks of 110 articles that were published in leading economics and political science journals with mandatory data and code sharing policies. We found that more than 85% of published claims were computationally reproducible. In robustness checks, our reanalyses showed that 72% of statistically significant estimates remain significant and in the same direction, and the median reproduced effect size is nearly the same as the originally published effect size (that is, 99% of the published effect size). Additionally, 6 independent research teams examined 12 pre-specified hypotheses about determinants of robustness. Research teams with more experience found lower levels of robustness, and robustness did not correlate with author characteristics or data availability.
  </div>
</div>

<div style="margin-top: 2em; font-size: 0.9em; color: #888;">* – presentation by co-author</div>
