---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv-download {
  display: inline-block;
  margin-bottom: 1.5em;
  font-size: 0.9em;
}

.cv-section {
  margin-bottom: 2em;
}

.cv-section > h2 {
  margin: 0 0 0.8em;
  padding-bottom: 0.3em;
  font-size: 1.1em;
  letter-spacing: 1px;
  text-transform: uppercase;
  border-bottom: 2px solid #001f5b;
}

.cv-entry {
  margin-bottom: 1.2em;
}

.cv-entry__head {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  gap: 0 1em;
  align-items: baseline;
}

.cv-entry__title {
  margin: 0;
  font-size: 1em;
  font-weight: bold;
  color: var(--global-heading-color);
}

.cv-entry__date {
  font-size: 0.85em;
  color: var(--global-text-color-light);
  white-space: nowrap;
}

.cv-entry__sub {
  margin: 0.15em 0 0;
  font-size: 0.9em;
  font-style: italic;
}

.cv-entry__sub span {
  font-style: normal;
}

.cv-entry ul,
.cv-list {
  margin: 0.5em 0 0;
  padding-left: 1.2em;
  font-size: 0.9em;
  line-height: 1.55;
}

.cv-entry li,
.cv-list li {
  margin-bottom: 0.3em;
}

.cv-list--pubs li {
  margin-bottom: 0.7em;
}

.cv-me {
  font-weight: bold;
  color: var(--global-heading-color);
}

.cv-tag {
  display: inline-block;
  margin-left: 0.3em;
  padding: 0 0.45em;
  font-size: 0.8em;
  border: 1px solid #001f5b;
  border-radius: 3px;
  color: #001f5b;
}
</style>

<a class="cv-download" href="/files/Aabha_CV.pdf" download><i class="fas fa-download" aria-hidden="true"></i> Download PDF</a>

<section class="cv-section">
  <h2>Education</h2>

  <div class="cv-entry">
    <div class="cv-entry__head">
      <h3 class="cv-entry__title">PhD in Robotics Engineering, Worcester Polytechnic Institute</h3>
      <span class="cv-entry__date">Expected 2028</span>
    </div>
    <p class="cv-entry__sub">Thesis: Modeling, Control &amp; Planning for Autonomous Neuroendovascular Procedures <span>&middot; GPA: 4.00</span></p>
  </div>

  <div class="cv-entry">
    <div class="cv-entry__head">
      <h3 class="cv-entry__title">Master&rsquo;s in Robotics Engineering, Worcester Polytechnic Institute</h3>
      <span class="cv-entry__date">May 2024</span>
    </div>
    <p class="cv-entry__sub">Thesis: Image Guidance and Safe Insertion Region Localization for Lumbar Puncture <span>&middot; GPA: 3.88</span></p>
  </div>
</section>

<section class="cv-section">
  <h2>Research Experience</h2>

  <div class="cv-entry">
    <div class="cv-entry__head">
      <h3 class="cv-entry__title">Autonomous Neuroendovascular Procedures</h3>
      <span class="cv-entry__date">Aug 2024 &ndash; Present</span>
    </div>
    <p class="cv-entry__sub">PhD Student &mdash; <a href="https://future-lab.wpi.edu/">FuTURE Lab</a></p>
    <ul>
      <li>Architecting full-stack patient-specific vascular digital twins for autonomous neurovascular surgical interventions.</li>
      <li>Collaborating with neurosurgeons at UMass Medical and Boston Children&rsquo;s Hospital on optimal navigation methods.</li>
      <li>Developing GPU-accelerated physics-based simulation models to capture contact mechanics for flexible tools.</li>
      <li>Achieved a 100% success rate in closed-loop guidewire-catheter navigation across 600+ simulated aortic anatomies.</li>
      <li>Integrated a custom robotic tool actuator with live C-arm imaging and path planning via a ROS2 pipeline.</li>
      <li>Resolving monoplane fluoroscopy depth ambiguity to accurately localize 3D tool poses for navigation feedback.</li>
      <li>Developing SOFA-driven multi-objective optimization to select optimal tool mechanics for patient-specific anatomies.</li>
    </ul>
  </div>

  <div class="cv-entry">
    <div class="cv-entry__head">
      <h3 class="cv-entry__title">Image Guidance for Lumbar Puncture</h3>
      <span class="cv-entry__date">Aug 2023 &ndash; May 2024</span>
    </div>
    <p class="cv-entry__sub">Master&rsquo;s Thesis Research &mdash; <a href="https://scholar.google.com/citations?view_op=view_citation&amp;hl=en&amp;user=NlcNljEAAAAJ&amp;citation_for_view=NlcNljEAAAAJ:u5HHmVD_uO8C">Thesis</a> &middot; <a href="https://github.com/taabhas/lumbar-puncture-us-guidance">Code</a></p>
    <ul>
      <li>Built an MRI&ndash;ultrasound multimodal registration framework to enhance 3D intraoperative visualization.</li>
      <li>Implemented intensity-based segmentation and 3D reconstruction pipelines for live 2D ultrasound streams.</li>
      <li>Engineered real-time 3D spatial tracking for the ultrasound probe, enabling intraoperative safe insertion region mapping.</li>
      <li>Improved registration accuracy by 13.2% IoU across 44 dynamic test cases using custom image-based local optimization.</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2>Publications</h2>
  <ul class="cv-list cv-list--pubs">
    <li><span class="cv-me">A. Tamhankar</span>, S. Verma, J. Patil, G. Pittiglio, &ldquo;Contact-aware Path Planning and Online Re-planning for Neuroendovascular Guidewire Navigation with Single Plane Fluoroscopic Feedback,&rdquo; in <i>IEEE Transactions on Medical Robotics and Bionics (T-MRB)</i>, Under Review.</li>
    <li><span class="cv-me">A. Tamhankar</span>, J. Patil, G. Pittiglio, &ldquo;<a href="https://arxiv.org/abs/2602.04050">An Anatomy-specific Guidewire Shaping Robot for Improved Vascular Navigation</a>,&rdquo; in <i>Proc. IEEE International Symposium on Medical Robotics (ISMR)</i>, 2026.</li>
    <li><span class="cv-me">A. Tamhankar</span>, R. Alterovitz, A. Puri, G. Pittiglio, &ldquo;<a href="https://arxiv.org/abs/2601.07945">Contact-aware Path Planning for Autonomous Neuroendovascular Navigation</a>,&rdquo; in <i>IEEE Robotics &amp; Automation Letters (RA-L)</i>, 2025.</li>
    <li><span class="cv-me">A. Tamhankar</span>, G. Pittiglio, &ldquo;<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11025974">Towards Autonomous Navigation of Neuroendovascular Tools for Timely Stroke Treatment via Contact-Aware Path Planning</a>,&rdquo; in <i>Proc. IEEE International Symposium on Medical Robotics (ISMR)</i>, 2025. <span class="cv-tag">2nd Place Best Student Paper Award</span></li>
  </ul>
</section>

<section class="cv-section">
  <h2>Work Experience</h2>

  <div class="cv-entry">
    <div class="cv-entry__head">
      <h3 class="cv-entry__title">Engineering Development Group Intern, MathWorks</h3>
      <span class="cv-entry__date">May 2023 &ndash; Aug 2023</span>
    </div>
    <p class="cv-entry__sub">Natick, MA</p>
    <ul>
      <li>Enhanced 3D mapping and obstacle localization by improving the TSDF representation via voxel-level curve fitting.</li>
      <li>Achieved 15% higher accuracy and a 12% runtime cut over the baseline TSDF in MATLAB driving simulations.</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2>Achievements &amp; Service</h2>
  <ul class="cv-list">
    <li>1st Place, St&auml;ubli Future Medical Roboticists Award for research on contact-aware path planning at the &ldquo;Training the Future Medical Roboticists&rdquo; workshop, IROS 2026.</li>
    <li>2nd Place, Best Student Paper Award at IEEE Intl. Symposium on Medical Robotics (ISMR), 2025.</li>
    <li>Winner, People&rsquo;s Choice Award at Graduate Research Innovation Exchange (GRIE), WPI, 2024.</li>
    <li>Invited Speaker at WPI Robotics Colloquium: &ldquo;Towards Autonomous Neuroendovascular Interventions&rdquo;.</li>
    <li>Graduate Lecturer on Optical Flow and Motion Segmentation for RBE 549 for a cohort of &asymp;60 students.</li>
    <li>Research mentor providing technical guidance to 10+ graduate students at the FuTURE Lab.</li>
  </ul>
</section>
