---
layout: page
title: 
permalink: /about/
---


<style>

/* ==========================================================
   ABOUT PAGE STYLES
   ========================================================== */

.about-wrap {
  max-width: 1100px;
  margin: 0 auto;
}


/* ----------------------------------------------------------
   1. TOP SECTION  —  photo + intro
   ---------------------------------------------------------- */

.about-top {
  display: flex;
  flex-wrap: wrap;
  gap: 32px;
  align-items: flex-start;
}

.about-photo {
  flex: 0 0 360px;
  max-width: 100%;
}

.about-photo img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 8px;
  box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
}

.about-photo .caption {
  font-size: 0.95em;
  color: #555;
  margin-top: 12px;
  text-align: center;
}

.about-intro {
  flex: 1 1 380px;
  min-width: 0;              /* 좁은 화면에서 넘침 방지 */
}

.about-intro h2 {
  margin-top: 0;
  color: #333;
  line-height: 1.35;
}

.about-intro p.lead {
  font-size: 1.1em;
  line-height: 1.6;
}


/* ----------------------------------------------------------
   2. SECTION LABEL  —  파란색 라벨 (Research Areas 등)
   ---------------------------------------------------------- */

.about-label {
  background-color: #0056b3;
  color: #ffffff;
  display: inline-block;
  padding: 5px 12px;
  font-weight: bold;
  border-radius: 4px;
  margin-bottom: 12px;
  letter-spacing: 0.5px;
}


/* ----------------------------------------------------------
   3. BULLET LIST  —  Research Areas / Research Method
   ---------------------------------------------------------- */

ul.about-list {
  margin: 0 0 25px 0;
  padding-left: 1.1em;
  list-style: none;
}

ul.about-list li {
  font-family: 'Times New Roman', serif;
  font-size: 1.2rem;
  line-height: 1.7;
  margin-bottom: 6px;
  position: relative;
  padding-left: 1em;
  overflow-wrap: break-word;
}

ul.about-list li::before {
  content: "●";
  position: absolute;
  left: 0;
  top: 0.35em;
  color: #0056b3;
  font-size: 0.7em;
}


/* ----------------------------------------------------------
   4. RECENT NEWS
   ---------------------------------------------------------- */

.news-section {
  margin-top: 50px;
  padding-top: 30px;
  border-top: 2px solid #e5e5e5;
}

.news-section > h2 {
  color: #333;
  margin-top: 0;
  margin-bottom: 20px;
}

.news-cols {
  display: flex;
  flex-wrap: wrap;
  gap: 20px 40px;
}

.news-col {
  flex: 1 1 380px;
  min-width: 0;
}

.news-col h3 {
  font-size: 1.05rem;
  color: #0056b3;
  margin: 0 0 10px 0;
  padding-bottom: 6px;
  border-bottom: 1px solid #dde5ee;
}

ul.news-list {
  list-style: none;
  margin: 0;
  padding: 0;
}

ul.news-list li {
  font-size: 0.97rem;
  line-height: 1.55;
  margin-bottom: 11px;
  padding-left: 15px;
  position: relative;
  overflow-wrap: break-word;
}

ul.news-list li::before {
  content: "▪";
  position: absolute;
  left: 0;
  color: #0056b3;
}

.news-date {
  color: #666;
  white-space: nowrap;
}

.news-list em     { font-style: italic; }
.news-list strong { color: #222; }


/* ----------------------------------------------------------
   5. CONTACT
   ---------------------------------------------------------- */

.about-contact {
  margin-top: 0;
  line-height: 1.6;
  overflow-wrap: break-word;
}


/* ==========================================================
   MOBILE  —  태블릿 / 휴대폰
   ========================================================== */

@media (max-width: 820px) {

  .about-top { gap: 22px; }

  .about-photo {
    flex: 0 0 100%;
    max-width: 300px;        /* 사진이 화면 전체를 채우지 않도록 제한 */
    margin: 0 auto;
  }

  .about-intro           { flex: 1 1 100%; }
  .about-intro h2        { font-size: 1.45rem; }
  .about-intro p.lead    { font-size: 1.02em; }

  ul.about-list li       { font-size: 1.02rem; line-height: 1.6; }
  ul.news-list li        { font-size: 0.93rem; }

  .news-section          { margin-top: 36px; }
}


@media (max-width: 480px) {

  .about-photo    { max-width: 240px; }
  .about-intro h2 { font-size: 1.3rem; }
}

</style>




<div class="about-wrap">


  <!-- ========================================================
       TOP : PHOTO + INTRO
       ======================================================== -->

  <div class="about-top">


    <!-- ---------- 왼쪽 : 사진 ---------- -->

    <div class="about-photo">

      <img src="/Junyeol_Photo.jpg" alt="Junyeol Ryu">

      <p class="caption">Pronounced as "Jun-Yeol"</p>

    </div>


    <!-- ---------- 오른쪽 : 소개글 ---------- -->

    <div class="about-intro">

      <h2>Welcome to my website!</h2>


      <p class="lead">
        Hello, I'm Junyeol Ryu, a Ph.D. candidate in Economics at the University of Oklahoma. My research interests are
        <span style="color:#0056b3; font-style:italic;">IO, Energy &amp; Environmental Economics</span>,
        and
        <span style="color:#0056b3; font-style:italic;">Applied Microeconomics</span>.
      </p>


      <p class="lead">
        I will be on the 2026-2027 job market.
      </p>


      <!-- ----- Research Areas ----- -->

      <div class="about-label">Research Areas</div>

      <ul class="about-list">
        <li>Electricity market regulation and design</li>
        <li>Liquefied natural gas (LNG) supply chain analysis</li>
        <li>Airline industry competition, merger, and pricing</li>
        <li>Gasoline retail station market dynamics</li>
      </ul>


      <!-- ----- Research Method ----- -->

      <div class="about-label">Research Method</div>

      <ul class="about-list">
        <li>Structural Estimation: demand forecasting, oligopoly supply modeling</li>
        <li>Machine Learning: large language models (LLM), topic modeling, random forest algorithms</li>
        <li>Causal Inference: difference-in-differences (including staggered designs), regression discontinuity, matching methods</li>
        <li>Spatial Econometrics and Geographical Analysis</li>
      </ul>


      <!-- ----- Contact ----- -->

      <div class="about-label">Contact Me</div>

      <p class="about-contact">
        Department of Economics, University of Oklahoma<br>
        308 Cate Center Drive, Office 230, Norman, OK 73019<br>
        <small>
          junyeol.ryu-1@ou.edu <i>(OU)</i>
          &nbsp;|&nbsp;
          ryujy1981@gmail.com <i>(personal)</i>
        </small>
      </p>

    </div>


  </div>




  <!-- ========================================================
       RECENT UPDATES
       ======================================================== -->

  <div class="news-section">

    <h2>Recent Updates</h2>


    <div class="news-cols">


      <!-- ---------- 왼쪽 : Research & Grants ---------- -->

      <div class="news-col">

        <h3>Research &amp; Grants</h3>

        <ul class="news-list">

        
          <li>
            <span class="news-date">Jul 2026</span> -
            <em>"Quasi-Vertical Integration, Low-Cost Entrants, and Multi-Market Contact: Coordination and Competition in Regional Gasoline Station Market"</em>
            is <strong>submitted<strong> to the <strong>Review of Economics and Statistics (RESTAT)</strong>.
          </li>

   
          
          <li>
            <span class="news-date">Jun 2026</span> -
            <em>"A Study on the Competition of LNG Power Generation in the Korean Electricity Market following the Import Method"</em>
            is <strong>submitted<strong> at <strong>Energy Policy</strong>.
          </li>

          
           <li>
            <span class="news-date">May 2026</span> -
            <em>"Coordinated Pricing After a Failed Merger: Evidence from the JetBlue-Spirit Case"</em>
            is <strong>accepted</strong> at the <strong>Review of Industrial Organization (RIO)</strong>.
          </li>
          


          
           <li>
            <span class="news-date">May 2026</span> -
            <em>"Tax Reform and Bonuses: Implications for Employee Productivity"</em>
            received an <strong>R&amp;R</strong> at <strong>Journal of Economic Behavior and Organization (JEBO)</strong>.
          </li>

          
          
          <li>
            <span class="news-date">Apr 2026</span> -
            I have been awarded the
            <strong>Dodge Family College of Arts and Sciences Dissertation Completion Fellowship</strong>,
            University of Oklahoma.
          </li>


          <li>
            <span class="news-date">Mar 2026</span> -
            <em>"Price Competition and Market Dynamics Under Asymmetric Costs:
            Evidence from Discount Gas Stations on Local Markets"</em>
            is <strong>published</strong> at <strong>Energy Economics</strong>.
          </li>

 
          <li>
            <span class="news-date">Sep 2025</span> -
            I have been awarded the <strong>Chong Liew Summer Research Award</strong>,
            University of Oklahoma.
          </li>



        </ul>

      </div>


      <!-- ---------- 오른쪽 : Conferences & Seminars ---------- -->

      <div class="news-col">

        <h3>Conferences and Seminars</h3>

        <ul class="news-list">

          <li>
            <span class="news-date">Jan 2027</span> -
            <strong>ASSA 2027 Annual Meeting</strong> (Washington, D.C.) - <em>scheduled</em>
          </li>

          <li>
            <span class="news-date">Nov 2026</span> -
            <strong>Southern Economic Association (SEA) 2026 Annual Meeting</strong> (Houston, TX) - <em>scheduled</em>
          </li>

          <li>
            <span class="news-date">Jul 2026</span> -
            <strong>Western Economic Association International (WEAI) 2026</strong> (Denver, CO)
          </li>

          <li>
            <span class="news-date">Apr 2026</span> -
            <strong>International Industrial Organization Conference (IIOC) 2026</strong> (Boston, MA)
          </li>

          <li>
            <span class="news-date">Apr 2026</span> -
            <strong>OU Ph.D. Economics Brown Bag Seminar</strong> (Norman, OK)
          </li>

          <li>
            <span class="news-date">Nov 2025</span> -
            <strong>Southern Economic Association (SEA) 2025 Annual Meeting</strong> (Tampa, FL)
          </li>

          <li>
            <span class="news-date">Oct 2025</span> -
            <strong>OU Ph.D. Economics Brown Bag Seminar</strong> (Norman, OK)
          </li>
          
          <li>
            <span class="news-date">Jun 2025</span> -
            <strong>Western Economic Association International (WEAI) 2025</strong> (San Francisco, CA)
          </li>

          <li>
            <span class="news-date">May 2025</span> -
            <strong>OU-OSU Ph.D. Economics Conference</strong> (Norman, OK)
          </li>


        </ul>

      </div>


    </div>

  </div>


</div>
