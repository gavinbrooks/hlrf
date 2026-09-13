---
title: "2026 Conference — Schedule test (test01)"
date: 2026-09-13
conference_year: 2026
banner:
  image: "images/hiroshima_skyline_long.jpg"
  title: "H-LRF 2026 Conference"
  description: "September 19-20, 2026"
type: "conference"
build:
  list: never
  render: always
---

<style>
.sched-v1 { --v1-purple: rgb(98, 0, 234); --v1-muted: #6b7280; --v1-line: #ececf3; }
.sched-v1 .v1-note { font-size: 0.88rem; color: var(--v1-muted); margin: 0 0 1.6rem 0;
  padding-left: 0.75rem; border-left: 3px solid #cd5c5c; }
.sched-v1 .v1-days { display: grid; grid-template-columns: 1fr 1fr; gap: 1.75rem; align-items: start; }
.sched-v1 .v1-dayhead { font-size: 1.15rem !important; margin: 0 0 1.1rem 0 !important; }
.sched-v1 .v1-block { display: flex; gap: 0.8rem; background: #fff; border: 1px solid var(--v1-line);
  border-left: 3px solid var(--v1-purple); border-radius: 10px; padding: 0.85rem 0.95rem;
  margin: 0 0 0.85rem 0; box-shadow: 0 1px 2px rgba(17, 24, 39, 0.05); }
.sched-v1 .v1-rail { flex: 0 0 52px; min-width: 52px; padding-top: 0.1rem; line-height: 1.4;
  font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
  font-size: 0.74rem; color: var(--v1-muted); }
.sched-v1 .v1-rail b { display: block; font-weight: 600; color: #374151; }
.sched-v1 .v1-body { flex: 1 1 auto; min-width: 0; }
.sched-v1 .v1-stitle { font-size: 0.95rem; font-weight: 600; color: #111827; line-height: 1.3;
  margin: 0 0 0.5rem 0; }
.sched-v1 .v1-talks { list-style: none; margin: 0; padding: 0; }
.sched-v1 .v1-talks li { padding: 0.45rem 0; border-top: 1px solid #f2f2f7; }
.sched-v1 .v1-talks li:first-child { border-top: 0; padding-top: 0; }
.sched-v1 .v1-talks a { display: block; color: var(--v1-purple); font-size: 0.9rem; font-weight: 600;
  line-height: 1.35; text-decoration: none; box-shadow: none; background-image: none; }
.sched-v1 .v1-talks a:hover { text-decoration: underline; }
.sched-v1 .v1-pres { display: block; color: var(--v1-muted); font-size: 0.79rem; line-height: 1.4;
  margin-top: 0.2rem; }
.sched-v1 .v1-minor { display: flex; gap: 0.8rem; align-items: baseline; color: var(--v1-muted);
  font-size: 0.83rem; margin: 0 0 0.85rem 0; padding: 0.3rem 0.95rem 0.3rem calc(0.95rem + 3px); }
.sched-v1 .v1-minor .t { flex: 0 0 52px; min-width: 52px;
  font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace; font-size: 0.74rem; }
@media (max-width: 780px) {
  .sched-v1 .v1-days { grid-template-columns: 1fr; gap: 2rem; }
}
@media (max-width: 480px) {
  .sched-v1 .v1-block { padding: 0.75rem 0.7rem; gap: 0.6rem; }
  .sched-v1 .v1-rail, .sched-v1 .v1-minor .t { flex-basis: 46px; min-width: 46px; font-size: 0.7rem; }
  .sched-v1 .v1-minor { padding-left: calc(0.7rem + 3px); padding-right: 0.7rem; gap: 0.6rem; }
}

.conference-content > p { margin: 0 0 1rem 0; line-height: 1.6; }
.conference-content > h2#about-the-conference { margin-top: 2.75rem; }
.conference-content > p a { color: rgb(98, 0, 234); font-weight: 600; text-decoration: none;
  box-shadow: none; background-image: none; }
.conference-content > p a:hover { text-decoration: underline; }
.conference-content > hr { border: 0; border-top: 1px solid #ececf3; margin: 2.5rem 0 0 0; }
</style>

<div class="conference-info-section">
  <h1>2026 H-LRF Conference</h1>
  <p>The 2026 H-LRF Conference will be held online on Saturday, September 19th and Sunday, September 20th. In order to accommodate presenters from different time zones, the conference will run from 2:15 pm to 7:00 pm (JST) on Saturday and from 1:30 pm to 7:30 pm (JST) on Sunday. Below is a list of the presenters and presentations for this conference. All times are JST. Each talk is 25 minutes, followed by a 5-minute changeover.</p>
</div>

<div class="sched-v1">
<p class="v1-note">Each talk is 25 minutes; times shown are the start of each session block.</p>
<div class="v1-days">
<div class="v1-day">
<h2 class="v1-dayhead">Saturday, September 19th</h2>
<div class="v1-minor"><span class="t">14:15–14:30</span><span>Conference opening</span></div>
<div class="v1-block">
<div class="v1-rail"><b>14:30</b>15:25</div>
<div class="v1-body">
<p class="v1-stitle">Session 1: Lexical targets and deliberate vocabulary learning</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/saturday_01/" >}}">Research-based Lexical Targets in Education and Teaching Materials</a><span class="v1-pres">Batia Laufer</span></li>
<li><a href="{{< relurl "conferences/test/saturday_02/" >}}">Pairs vs. Quizlet: Vocabulary Gains Across Aspects of Word Knowledge</a><span class="v1-pres">Thomas Stones, Jon Clenton, Tatsuya Nakata</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">15:25–15:35</span><span>Break (10 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>15:35</b>16:30</div>
<div class="v1-body">
<p class="v1-stitle">Session 2: Technology in vocabulary learning and teaching</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/saturday_03/" >}}">Learner Autonomy and Vocabulary Choice on an Online Platform</a><span class="v1-pres">Marshall Kiyoshi Higa</span></li>
<li><a href="{{< relurl "conferences/test/saturday_04/" >}}">Evaluating the Efficacy of Data-Driven Learning and Input Enhancement Approaches on Grammatical Collocations in Saudi EFL Learners</a><span class="v1-pres">Abeer Alenezi</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">16:30–16:45</span><span>Break (15 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>16:45</b>17:40</div>
<div class="v1-body">
<p class="v1-stitle">Session 3: Learning from viewing</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/saturday_05/" >}}">Effects of Enhanced Bilingual Subtitles on Comprehension and Vocabulary Learning</a><span class="v1-pres">Jiaqi Wu, Takumi Hayabusa, Kazuki Shintome, Akifumi Yanagisawa</span></li>
<li><a href="{{< relurl "conferences/test/saturday_06/" >}}">Vocabulary Support on Learner Engagement During Viewing and Vocabulary Learning</a><span class="v1-pres">Misaki Hatakeyama, Gaia Oikawa, Takumi Uchihara</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">17:40–17:55</span><span>Break (15 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>17:55</b>18:50</div>
<div class="v1-body">
<p class="v1-stitle">Session 4: Incidental learning of words and multiword items</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/saturday_07/" >}}">How Effective Is L2 Incidental Collocation Learning? A Multilevel Meta-Analysis</a><span class="v1-pres">Muhang Li & Takumi Uchihara</span></li>
<li><a href="{{< relurl "conferences/test/saturday_08/" >}}">The Effects of Proficiency on Incidental Learning of Words versus Multiword Expressions</a><span class="v1-pres">Mahnaz Aliyar</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">18:50–19:00</span><span>Day 1 closing</span></div>
</div>
<div class="v1-day">
<h2 class="v1-dayhead">Sunday, September 20th</h2>
<div class="v1-block">
<div class="v1-rail"><b>13:30</b>14:25</div>
<div class="v1-body">
<p class="v1-stitle">Session 5: Reading, eye movements and incidental vocabulary learning</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/sunday_01/" >}}">Perceived Narrator Effects on Incidental Vocabulary Learning and Eye Movements</a><span class="v1-pres">Alexandre Gaspar Mendes Alves, Barry Lee Reynolds, Brian V. Rusk</span></li>
<li><a href="{{< relurl "conferences/test/sunday_02/" >}}">Diminished Mnemonic Advantage of Alliterative Phrases in Silent Reading</a><span class="v1-pres">Yinhui Gao, Barry Lee Reynolds, Brian V. Rusk</span></li>
</ul></div></div>
<div class="v1-block">
<div class="v1-rail"><b>14:30</b>15:25</div>
<div class="v1-body">
<p class="v1-stitle">Session 6: The bilingual mental lexicon</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/sunday_03/" >}}">Locus of Translation Priming Effect: Shared Concept or Form-Level Association?</a><span class="v1-pres">Yoan Linon & Mariko Nakayama</span></li>
<li><a href="{{< relurl "conferences/test/sunday_04/" >}}">Do Chinese-English Bilinguals Activate Phonology in Early L2 Visual Word-Processing?</a><span class="v1-pres">Liying Yang, Irina Elgort, Sasha Calhoun</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">15:25–15:35</span><span>Break (10 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>15:35</b>16:30</div>
<div class="v1-body">
<p class="v1-stitle">Session 7: Measuring lexical knowledge</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/sunday_05/" >}}">The Semitic Paradigm: Vocabulary Depth Hierarchies in L2 Hebrew</a><span class="v1-pres">Eihab Abu-Rabiah</span></li>
<li><a href="{{< relurl "conferences/test/sunday_06/" >}}">Development and Initial Validation of COLLAT: A Collocation Awareness Instrument</a><span class="v1-pres">Chi Cuong Chau & Barry Lee Reynolds</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">16:30–16:45</span><span>Break (15 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>16:45</b>17:40</div>
<div class="v1-body">
<p class="v1-stitle">Session 8: Perceiving and judging spoken lexis</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/sunday_07/" >}}">Measuring Spoken Vocabulary Knowledge: Word-Level Accentedness and Comprehensibility</a><span class="v1-pres">Soma Sekiguchi, Ryuya Komuro, Yui Suzukida, Takumi Uchihara</span></li>
<li><a href="{{< relurl "conferences/test/sunday_08/" >}}">Listener Background and the Evaluation of Spoken L2 English Lexis</a><span class="v1-pres">Philip Head</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">17:40–17:55</span><span>Break (15 minutes)</span></div>
<div class="v1-block">
<div class="v1-rail"><b>17:55</b>19:20</div>
<div class="v1-body">
<p class="v1-stitle">Session 9: Lexis in academic and specialised discourse</p>
<ul class="v1-talks">
<li><a href="{{< relurl "conferences/test/sunday_09/" >}}">Beyond Monologues: Predicting L2 Fluency in Academic Multilogues</a><span class="v1-pres">Christopher J. Hollis, Jon Clenton, Gavin Brooks, Jen Jordan, Daniel Hougham</span></li>
<li><a href="{{< relurl "conferences/test/sunday_10/" >}}">Rhetorical Structure and Lexical Features of Abstracts and Full Texts</a><span class="v1-pres">Motoko Asano, Kaori Sakakibara, Miho Fujieda, Tomoko Wakasa, Yoshinori Miyazaki</span></li>
<li><a href="{{< relurl "conferences/test/sunday_11/" >}}">Developing an Agricultural Word List</a><span class="v1-pres">Wakako Takinami, Gavin Brooks, Jon Clenton</span></li>
</ul></div></div>
<div class="v1-minor"><span class="t">19:20–19:30</span><span>Conference closing</span></div>
</div>
</div></div>

---

## About the conference

The conference schedule can be found here:

[HLRF 2026 Schedule]({{< relurl "files/2026/HLRF_2026_Schedule.pdf" >}})

The book of abstracts can be found here:

[HLRF 2026 Book of Abstracts]({{< relurl "files/2026/HLRF_2026_Abstracts.pdf" >}})

The conference will take place via Zoom. If you have questions about the conference you can get in touch with us <a href="https://forms.gle/dNqFScXZk2F7qMpP7" target="_blank">here</a>.
