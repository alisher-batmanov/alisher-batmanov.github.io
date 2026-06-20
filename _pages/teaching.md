---
layout: archive
title:
nav_order: 2
permalink: /teaching/
author_profile: true
---

<style>
/* ── Teaching page styles ── */
.teaching-section-label {
  font-size: 0.75em;
  font-weight: 600;
  letter-spacing: 0.15em;
  text-transform: uppercase;
  color: #888;
  margin-bottom: 1.2em;
  margin-top: 3.5em;
}
.teaching-section-label:first-of-type {
  margin-top: 0;
}
.course-block {
  margin-bottom: 1.4em;
}
.course-title {
  font-size: 1.05em;
  font-weight: 700;
  color: #000;
  line-height: 1.4;
}
.course-scores {
  margin-top: 0.2em;
  font-size: 0.95em;
}
.course-buttons {
  margin-top: 0.5em;
  display: flex;
  flex-wrap: wrap;
  gap: 6px;
  line-height: 1;
}
.course-btn {
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
.course-btn:hover {
  border-color: #7B0000;
  color: #7B0000 !important;
}
.course-btn.active {
  border-color: #7B0000;
  color: #7B0000 !important;
}
.course-btn svg {
  flex-shrink: 0;
}
.course-evals {
  display: none;
  margin-top: 0.6em;
  padding: 0.8em 1em;
  background: rgba(123,0,0,0.04);
  border-left: 3px solid rgba(123,0,0,0.2);
  font-size: 0.93em;
  line-height: 1.6;
}
.course-evals.show {
  display: block;
}
.course-evals ul {
  margin: 0;
  padding-left: 1.2em;
}
.course-evals ul li {
  margin-bottom: 0.5em;
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
</script>

<div class="page-pull-up"></div>
# Teaching at UC San Diego

<div class="teaching-section-label">Course Instructor</div>

<div class="course-block">
  <div class="course-title">ECON 120B: Econometrics B (Linear Regression and Causal Inference) — Fall 2025</div>
  <div class="course-scores">Student learning — 4.54/5, Course structure — 4.51/5, Class environment — 4.76/5</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-120bf25-eval" onclick="toggleSection('eval-120b-f25','btn-120bf25-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="/files/120B_Batmanov_FA25_Syllabus.pdf" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Course syllabus</a>
    <a class="course-btn" href="https://drive.google.com/file/d/13mf7NVAd9TFh4iAV1TMm2HcQEwWdf3e6/view?usp=sharing" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-120b-f25">
    <ul>
      <li>"Professor's Batmanov friendly demeanor and welcomeness created a open environment where students felt comfortable participating and asking questions; I think that the course setup was great, and I liked how the tests were more challenging as I felt like I learned more from the course that way without getting punished on my overall grade for the course; Best professor I ever had. He runs multiple office hours for me cause I was struggling a little bit; Love this professor! Thoroughly enjoyed the course. You can tell Professor Batmanov tried his best to make the material approachable and cared for his students."</li>
      <li>"One aspect of Econ 120B that particularly helped me engage with the material was the emphasis on interpreting regression results and understanding how statistical assumptions affect real-world conclusions. Even though the exams were challenging for me, working through the weekly problem sets and seeing how OLS assumptions break down in different scenarios helped me understand the logic behind econometric thinking instead of just memorizing formulas; Taught a difficult subject in a simple manner and helped use good real world examples that helped me learn how the content can apply outside of the classroom; The class is very small and it's highly interactive and you get to follow along pretty easily."</li>
      <li>"I think this course itself is very challenging so before we talk about anything this aspect should be factored in. There's not a lot of lecturer can do to reduce the difficulty of Econ 120B while maintaining its integrity. The prof still does a very decent job explaining the concepts and does spend enough time reinforcing them so if you attend the class and review the notes afterwards you won't have too much trouble following while at the same time he's not wasting time repeating concepts over and over again. The class size definitely help and at least for me and couple other students it's very interactive. I appreciate the bonus quizzes, it feels good knowing you're improving your score but they're also a great way of checking your understanding. A stressful midterm is also helpful when prepping for the final, at least you know what you got wrong and can improve yourself. The end score is going to end up very similar compared to an uncurved 'easy' test so it does seem like a better way to learn."</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 100A: Intermediate Microeconomics (Consumer and Producer Theory, GE) — Summer 2025</div>
  <div class="course-scores">Student learning — 4.6/5, Course structure — 4.6/5, Class environment — 4.65/5</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-100a-eval" onclick="toggleSection('eval-100a','btn-100a-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="/files/100A_Syllabus_Batmanov_SU25.pdf" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Course syllabus</a>
    <a class="course-btn" href="https://drive.google.com/file/d/1oFjdegZzbaSsEkM8VB-jWmBpedt1PqjQ/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-100a">
    <ul>
      <li>"The presentations with 'correct' pace helped me absorb the material easily. This is by far the most crystal clear class I've ever taken. Concepts are explained clearly, without leaving any possible tiny questions unanswered."</li>
      <li>"Alisher is a great professor who cares about making sure we have the knowledge to succeed in his class. He is a fair teacher and looks out for his students; The professor did an excellent job explaining concepts in detail, and I appreciated that there was always an accompanying example showing how each concept is used to solve problems. This helped me become familiar with the language of the problems and with economics in general."</li>
      <li>"The class was pretty small but the professor creates a lot of opportunities for us to get to know our peers and I truly appreciate it. I have gained a few valuable friendships from the class that I didn't expect out of it. The class is always welcoming and I appreciate that the professor takes his time to answer any question that comes up in detail. He also manages time pretty well, which is a weird thing to notice but I do. We're never behind the syllabus which gives enough time to study and get to know the material. Overall, I feel like the class was pretty well-structured, and the quizzes/packets take a little bit pressure off the tests and that help us study along the way, not cramping last minute. So I'd say, this is one of the more structured and well-thought out classes that I've attended on campus. Thank you for everything, professor!"</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 120B: Econometrics B (Linear Regression and Causal Inference) — Summer 2024</div>
  <div class="course-scores">Student learning — 4.24/5, Course structure — 4.36/5, Class environment — 4.64/5</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-120bs24-eval" onclick="toggleSection('eval-120b-s24','btn-120bs24-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="/files/Econ120B_Batmanov_SU24_Syllabus.pdf" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/></svg> Course syllabus</a>
    <a class="course-btn" href="https://drive.google.com/file/d/1jTTdraeTxzaEmDzAUwtd2Wk6ZQ-fMIl0/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-120b-s24">
    <ul>
      <li>"The professor did a wonderful job engaging the students in a way that made the information stick. I appreciate his teaching style and the things I learned; He was really welcoming and interested in the lives of his students. He asked me about my work and why I was taking the class. He also went above and beyond by answering questions on discord that my team and I had. He was always prompt and informative."</li>
      <li>"The rate the material was taught at was easy to follow in context of the quick pace for summer session; Made sure he was readily available, especially in the discord channel that was made for the class; I especially liked how interactive lectures were."</li>
      <li>"The structure of class and the PowerPoints were relatively easy to follow along, the instructor did a good job on teaching the material and following it up with practice problems. I also really loved and appreciated the bonus pop quizzes. I commuted from LA for class this summer so at times it was hard to get myself to go to class. However, the bonus quizzes encouraged me to go to class with a positive mindset because I knew I was only helping my grade. Getting to do a bonus quiz helped me get to class and learn in person!"</li>
    </ul>
  </div>
</div>


<div class="teaching-section-label">Teaching Assistant</div>

<div class="course-block">
  <div class="course-title">ECON 100A: Intermediate Microeconomics (Consumer and Producer Theory, GE) — Spring 2026</div>
  <div class="course-scores">Overall rating — 4.79/5, Positive responses — 98%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-100a-ta-eval" onclick="toggleSection('eval-100a-ta','btn-100a-ta-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1e90pWwHk3jrJzA0VMB8PvKFRzg7SxBoi/view?usp=drive_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-100a-ta">
    <ul>
      <li>"Alisher is the most dedicated TA I've interacted with at UCSD. This is evident not only in his clear communication of the Professor's expectations, but also in the time and effort he put into answering questions on the class Discord. He consistently responded quickly, and it was clear that he genuinely cared about helping students succeed in the course."</li>
      <li>"When I was struggling through my midterms, I was expressing my concerns and he was really supportive, and helped me dial down some subjects so that I can give the second midterm and the final a good shot; I found the extra practice material he offered extremely helpful along with the study tips he'd give regarding the topics that students have struggled with in the past. He was very encouraging and always offered his help and availability."</li>
      <li>"Always was willing to help everyone, often held Zooms especially during times of exams and ensured that students understood the content completely; Discord server is incredibly helpful! He provided students with a Discord in which many students participated and gave us an easy platform to ask for questions and provide notes."</li>
      <li><em>Instructor evaluation:</em> "Alisher was an amazing TA! Very experienced, knowledgeable, and most importantly, cares a lot about the students' learning"</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 220B: Econometric Analysis of Cross-sectional Data (PhD core) — Winter 2023</div>
  <div class="course-scores">Overall rating — 4.90/5, Positive responses — 98%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-220b-eval" onclick="toggleSection('eval-220b','btn-220b-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1W9ghTAdWt5m5OivkdIutZMZZaIOOASX5/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-220b">
    <ul>
      <li>"Alisher was by far the best TA we had this quarter, and he is the best TA we have had for metrics. This is a sentiment I know many of my peers share, as it has been a common topic of conversation throughout the quarter. I could not have asked for a better metrics TA and I wish Alisher was TAing for 220C as well, and I hope that he will lead our qual review sessions. Alisher was extremely prepared for discussion, especially considering this was his first time TAing this class."</li>
      <li>"Phenomenal TA. He went above and beyond writing out notes for discussions, soliciting feedback to improve throughout, giving detailed explanations when grading, and holding additional review sessions for each exam. He deserves all the awards. Please make him the metrics Qual TA."</li>
      <li>"Alisher is my role model TA. It is an understatement to say that he goes out of his way for his students."</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 109: Game Theory — Winter 2024, Fall 2023, Summer 2023</div>
  <div class="course-scores">Overall rating — 4.72/5, Positive responses — 95%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-109-eval" onclick="toggleSection('eval-109','btn-109-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1tEylXqEdjgLQCyMhhUfXdZOTjCFfIiJi/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-109">
    <ul>
      <li>"He is one of the most well prepared TAs I've had for any of my lectures and the material covered in discussion sections are really helpful. The discussion sections were incredibly helpful and honestly helped me become more interested in the material — Alisher's thought process/approaches to the problems were really interesting and insightful throughout the quarter."</li>
      <li>"I usually don't submit evaluations for TAs because I hardly interact with them, but I genuinely understood the material thoroughly because of Alisher's help. His discussions were extremely informative and he made time for those who couldn't make it to his original office hours. Would absolutely recommend him to other students."</li>
      <li>"TA Alisher Batmanov demonstrates genuine care for students, quickly responding to any messages on the class discord. He makes discussion sections engaging, both by explaining material and homework, but also by making tangible games and activities for students during discussion. He goes the extra mile to provide clear grading guidelines rather than relying solely on Gradescope's feedback."</li>
      <li><em>Instructor evaluation:</em> "I am happy to have been able to trust Alisher completely in the role of TA for this course. Most notably, he was very organized and conscientious in establishing grading rubrics, scoring exams, and tracking students' progress."</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 100B: Microeconomics B (Producer Theory and GE) — Spring 2024, Summer 2023</div>
  <div class="course-scores">Overall rating — 4.63/5, Positive responses — 97%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-100b-eval" onclick="toggleSection('eval-100b','btn-100b-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1ihdn5jUmT1lMFpDEzvxz67eGl_Zs3qtn/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-100b">
    <ul>
      <li>"Mr Batmanov is one of the best TAs I've had in my life. Very clear explanation of the material; Extremely helpful review sessions that helped me succeed in the class; Fantastic recorded review sessions. Great examples, and made himself constantly available for questions."</li>
      <li>"Amazing TA; Straight to the point and precise. Would go through the material at a nice pace while also being open to questions. Couldn't recommend more. One of the best TAs I have had at this school; Really good TA, covered the right material, always had answers to relevant questions, and taught well; AMAZING TA!"</li>
      <li><em>Instructor evaluation:</em> "Alisher has been an amazing TA!! He's a great teacher, and does an amazing job at econ 100b"; "Alisher was an incredible TA; he provided great help to me and to the students, and made my first time teaching a course run much more smoothly. I would be very happy to work with him again and would highly recommend him to other instructors."</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">ECON 1: Principles of Microeconomics — Summer 2024, Fall 2022</div>
  <div class="course-scores">Overall rating — 4.78/5, Positive responses — 96%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-econ1-eval" onclick="toggleSection('eval-econ1','btn-econ1-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1g3d4d-cI6b7BABnUUJTuZwe0vO9v7H76/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-econ1">
    <ul>
      <li>"Alisher was a fantastic TA for this course; works graded by him were consistently done quickly and accurately; Alisher led quiz and midterm review sessions very well by being able to go through the topics and give an overview of each; by attending section I felt more prepared to take the quiz/midterm."</li>
      <li><em>Instructor evaluation:</em> "I really loved teaching Econ 1 with Alisher this summer because he was such an outstanding TA. For the first time in my 20 years of teaching at UCSD, Alisher finished grading the midterm and final on the same day the exam was given. He also graded very accurately and provided detailed explanations so that no student asked for a regrade. Particularly for summer session, quick grading of the midterm was incredibly useful so students who wanted to improve their performance could work with Alisher and me to develop a new study strategy for the final. Alisher was on top of everything all summer and was very communicative about his plans for the class. He was unfailingly kind to the students and greatly contributed to making Econ 1 successful this summer. Thank you for everything, Alisher!"</li>
    </ul>
  </div>
</div>

<div class="course-block">
  <div class="course-title">MGT 160: Experiments in Firms — Fall 2024, Winter 2025, Spring 2025</div>
  <div class="course-scores">Overall rating — 4.63/5, Positive responses — 95%</div>
  <div class="course-buttons">
    <span class="course-btn" id="btn-mgt160-eval" onclick="toggleSection('eval-mgt160','btn-mgt160-eval')"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg> Evaluations preview</span>
    <a class="course-btn" href="https://drive.google.com/file/d/1VtZensog0ZcTLFDj1BYbfjJxzLf-28Km/view?usp=share_link" target="_blank"><svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg> Full evaluation report</a>
  </div>
  <div class="course-evals" id="eval-mgt160">
    <ul>
      <li>"Really helpful and answers to questions very quickly with full professionalism; Gave very detailed and constructive feedback, always provided reminders and tips in discord that were very helpful!; TA encouraged me to feel that I could succeed in the course, Was incredibly encouraging!!; The best TA I've ever had! Incredibly patient and understanding, wish all my TA's were like him; had a great experience with Alisher and definitely recommend him to other students as well!"</li>
      <li><em>Instructor evaluation:</em> "If there is the possibility for Alisher to win an Instructional Assistant award, I highly recommend him for it. I have had many teaching assistants at numerous institutions, and he is among the best I have worked with. Alisher went above and beyond as an instructional assistant. Though not required, he set up his own Discord channel for students to be able to reach out to him any time. I was a member of the channel, so I would see students' activity. Alisher always responded promptly and professionally, helping the students out with whatever they needed. This proactive step that he took to make excellent lines of communication between him and the students really made the course much better than it would have otherwise been. Alisher also helped me out so much by showing me the ropes, since he had been an instructional assistant on this course before, but this was my first time teaching it. He had great ideas on how to solve some tough logistical problems with the course. He was a great assistant who listened to what I wanted, but also wasn't afraid to offer his opinion when he thought something could be improved, which I truly appreciated. Without him, the course would have been not only significantly bumpier, but simply not as high quality as it was. I wish he could be my instructional assistant forever!"</li>
    </ul>
  </div>
</div>
