---
layout: page
title: 
permalink: /research/
---

<style>

/* ==========================================================
   폰트를 바꾸려면 아래 네 줄만 수정하세요
   ========================================================== */

@import url('https://fonts.googleapis.com/css2?family=Literata:ital,wght@0,400;0,600;0,700;1,400;1,600;1,700&family=Newsreader:ital,wght@0,400;0,600;0,700;1,400;1,600;1,700&family=Noto+Serif:ital,wght@0,400;0,700;1,400&family=EB+Garamond:ital,wght@0,400;0,600;1,400&display=swap');

.research h3            { font-family: 'Noto Serif', Georgia, serif; }   /* 섹션 제목 */
.research .title        { font-family: 'Newsreader', Georgia, serif; }   /* 논문 제목 */
.research .meta         { font-family: 'Newsreader', Georgia, serif; }   /* 저자 / 저널 */
.research .abs-body     { font-family: 'EB Garamond', Georgia, serif; }  /* 초록 */


/* ==========================================================
   섹션 제목
   ========================================================== */

.research h3 {
  font-size: 1.3rem;
  font-weight: 700;
  letter-spacing: 0.02em;
  margin: 46px 0 22px;
  padding-bottom: 7px;
  border-bottom: 1px solid #e3e3e3;
}

.research h3:first-of-type { margin-top: 0; }


/* ==========================================================
   논문 한 건
   ========================================================== */

.research .paper {
  margin-bottom: 26px;
}

.research .title {
  font-size: 1.12rem;
  line-height: 1.45;
  color: #1a1a1a;
  margin: 0 0 4px;
}

.research .title a {
  color: #1a1a1a;
  text-decoration: none;
  border-bottom: 1px solid rgba(0,0,0,.18);
}

.research .title a:hover {
  color: #0056b3;
  border-bottom-color: #0056b3;
}

.research .meta {
  font-size: 1.0rem;
  line-height: 1.5;
  color: #777;
  margin: 0;
}

.research .meta em     { font-style: italic; }
.research .meta strong { color: #555; font-weight: 600; }

/* 게재 / 심사 상태 */
.research .status {
  color: #666;
}


/* ==========================================================
   Abstract 펼침
   ========================================================== */

.research details {
  margin-top: 7px;
}

.research summary {
  font-family: 'Newsreader', Georgia, serif;
  font-size: 0.98rem;
  color: #8b2b2b;
  cursor: pointer;
  display: inline-block;
  list-style: none;
  border-bottom: 1px solid rgba(139,43,43,.35);
  padding-bottom: 1px;
  user-select: none;
}

.research summary::-webkit-details-marker { display: none; }

.research summary::after {
  content: " \25B8";          /* ▸ */
  font-size: 0.8em;
  color: #a05555;
}

.research details[open] summary::after {
  content: " \25BE";          /* ▾ */
}

.research summary:hover { color: #b03a3a; }

.research .abs-body {
  margin: 11px 0 4px;
  padding: 15px 18px;
  background: #f7f8fa;
  border-left: 3px solid #d8dce2;
  font-size: 1.02rem;
  line-height: 1.65;
  color: #3a3a3a;
  text-align: justify;
  hyphens: auto;
}


/* ==========================================================
   모바일
   ========================================================== */

@media (max-width: 640px) {
  .research h3        { font-size: 1.15rem; margin: 34px 0 18px; }
  .research .title    { font-size: 1.02rem; }
  .research .meta     { font-size: 0.93rem; }
  .research summary   { font-size: 0.92rem; }
  .research .abs-body {
    font-size: 0.95rem;
    padding: 12px 14px;
    text-align: left;
  }
}

</style>

<div class="research">


  <!-- ======================================================
       PUBLICATIONS
       ====================================================== -->

  <h3>PUBLICATIONS</h3>


  <div class="paper">
    <p class="title">
      <a href="https://link.springer.com/article/10.1007/s11151-026-10057-1" target="_blank" rel="noopener">Coordinated Pricing After a Failed Merger: Evidence from the JetBlue-Spirit Case</a>
    </p>
    <p class="meta">
      with Minhae Kim and Myongjin Kim · <em>co 1st author</em><br>
      <span class="status"><em>Forthcoming</em> at <strong>Review of Industrial Organization</strong></span>
    </p>
  </div>


  <div class="paper">
    <p class="title">
      <a href="https://www.sciencedirect.com/science/article/abs/pii/S014098832600023X" target="_blank" rel="noopener">Price Competition and Market Dynamics Under Asymmetric Costs: Evidence from Discount Gas Stations on Local Markets</a>
    </p>
    <p class="meta">
      with Yenjae Chang<br>
      <span class="status"><strong>Energy Economics</strong>, 155, 109144 (Mar. 2026)</span>
    </p>
  </div>


  <div class="paper">
    <p class="title">
      <a href="https://link.springer.com/article/10.1007/s11002-024-09755-1" target="_blank" rel="noopener">What Occurs When a Shot is Fired? Gender Differences in Housing Markets</a>
    </p>
    <p class="meta">
      with Yongseok Kim, Suman Basuroy, and Myongjin Kim · <em>co 1st author</em><br>
      <span class="status"><strong>Marketing Letters</strong>, 36, 369–383 (2025)</span>
    </p>
  </div>


  <div class="paper">
    <p class="title">
      <a href="https://www.sciencedirect.com/science/article/pii/S0140988320304308" target="_blank" rel="noopener">Household Differentiation and Residential Electricity Demand in Korea</a>
    </p>
    <p class="meta">
      with Daewook Kim and Mankeun Kim · <em>1st author</em><br>
      <span class="status"><strong>Energy Economics</strong>, 95, 105090 (Mar. 2021)</span>
    </p>
  </div>


  <!-- ======================================================
       WORKING PAPERS
       ====================================================== -->

  <h3>WORKING PAPERS</h3>


  <div class="paper">
    <p class="title">Energy Security and Competition in South Korea</p>
    <p class="meta">
      with Eric Lewis, Myongjin Kim, and Hongseok So · <em>1st author</em> (2024)
    </p>
    <details>
      <summary>Abstract</summary>
      <div class="abs-body">
        여기에 초록을 넣으세요.
      </div>
    </details>
  </div>


  <div class="paper">
    <p class="title">Impacts of ZEV on Product Market, Environment, and Health Outcomes</p>
    <p class="meta">
      with Minhae Kim and Myongjin Kim · <em>1st author</em> (2024)
    </p>
    <details>
      <summary>Abstract</summary>
      <div class="abs-body">
        여기에 초록을 넣으세요.
      </div>
    </details>
  </div>


  <div class="paper">
    <p class="title">
      <a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7025078" target="_blank" rel="noopener">Quasi-Vertical Integration, Low-Cost Entrants, and Multi-Market Contact: Coordination and Competition in Regional Gasoline Station Market</a>
    </p>
    <p class="meta">
      with Qi Ge and Myongjin Kim · <em>1st author</em> (2024)<br>
      <span class="status"><em>Submitted</em> to <strong>Review of Economics and Statistics</strong></span>
    </p>
    <details>
      <summary>Abstract</summary>
      <div class="abs-body">
        여기에 초록을 넣으세요.
      </div>
    </details>
  </div>


  <div class="paper">
    <p class="title">
      <a href="https://www.dropbox.com/scl/fi/gi87koi28y9m07mpolmuj/Tax_Reform_and_Product_Quality.pdf?rlkey=c3d2jkef8xii836nqtlzq5w43&amp;e=1&amp;dl=0" target="_blank" rel="noopener">Tax Reform and Bonuses: Implications for Employee Productivity</a>
    </p>
    <p class="meta">
      with Myongjin Kim, Georgia Kosmopoulou, and Jangsu Yoon (2024)<br>
      <span class="status"><em>R&amp;R</em> at <strong>Journal of Economic Behavior and Organization</strong></span>
    </p>
    <details>
      <summary>Abstract</summary>
      <div class="abs-body">
        여기에 초록을 넣으세요.
      </div>
    </details>
  </div>


  <div class="paper">
    <p class="title">A Study on the Competition of LNG Power Generation in the Korean Electricity Market following the Introduction Method</p>
    <p class="meta">
      with Hongseok So, Daewook Kim, and Mankeun Kim (2024)<br>
      <span class="status"><em>Under review</em> at <strong>Energy Policy</strong></span>
    </p>
    <details>
      <summary>Abstract</summary>
      <div class="abs-body">
        This study empirically compares and analyzes the cost efficiency of two LNG import methods—private direct import and the Korea Gas Corporation's average rate system—in terms of fuel cost under buyer and seller market conditions in the global LNG market. Using Asian LNG spot prices (JKM) from January 2015 to May 2023, the Bai-Perron test was applied to identify changes in market structure. Contrary to the perception that direct importers would hold a cost advantage in buyer markets and KOGAS-supplied generators in seller markets, the empirical analysis revealed that direct importers are relatively advantageous in both market types, with their competitiveness being particularly pronounced in seller markets. This study reexamines the impact of the high market responsiveness and cost efficiency of private direct importers on the electricity system.
      </div>
    </details>
  </div>


  <div class="paper">
    <p class="title">Marijuana Legalization and Airline Competition</p>
    <p class="meta">
      with Minhae Kim and Myongjin Kim (2024)
    </p>
  </div>


  <!-- ======================================================
       WORKS IN PROGRESS
       ====================================================== -->

  <h3>WORKS IN PROGRESS</h3>


  <div class="paper">
    <p class="title">A Network, Scoring Auction and Collusion</p>
    <p class="meta">with Georgia Kosmopoulou, Hojin Jung, and Myongjin Kim (2024)</p>
  </div>


  <div class="paper">
    <p class="title">A Study of Renewable Energy Policy on Electricity Market in South Korea, Jeju</p>
    <p class="meta">with Hongseok So (2025)</p>
  </div>


  <div class="paper">
    <p class="title">Procurement Collusion and Network</p>
    <p class="meta">with Myongjin Kim and Yunmi Kong (2025)</p>
  </div>


  <div class="paper">
    <p class="title">Gas Station Location Selection with Multi-Market Contact and Market Power</p>
    <p class="meta">2025</p>
  </div>


  <div class="paper">
    <p class="title">The Impact of SAF on Supply Chain, Market Outcome</p>
    <p class="meta">2024</p>
  </div>


  <div class="paper">
    <p class="title">Regionally Differentiated Electricity Prices and Price Elasticity</p>
    <p class="meta">with Sumi Seon and Daewook Kim (2026)</p>
  </div>


  <div class="paper">
    <p class="title">Reshaping Entrepreneurship? Lessons from the Kansas Tax Experiment</p>
    <p class="meta">with Bowei Dong (2026)</p>
  </div>


</div>
