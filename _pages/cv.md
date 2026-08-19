---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
  .cv-entry-list {
    list-style: none;
    margin: 0.5em 0 0;
    padding-left: 0;
  }
  .cv-entry {
    padding: 0.9em 0;
    border-bottom: 1px solid var(--global-border-color);
  }
  .cv-entry:first-child {
    padding-top: 0;
  }
  .cv-entry:last-child {
    border-bottom: none;
  }
  .cv-entry__title {
    margin: 0 0 0.3em;
    font-size: 1em;
  }
  .cv-entry__meta {
    margin: 0;
    color: var(--global-text-color-light);
    font-size: 0.9em;
    line-height: 1.5;
  }
  .archive a,
  .archive a:visited {
    color: var(--global-text-color);
    text-decoration: underline;
  }
  .archive a:hover {
    color: var(--global-text-color);
    text-decoration: none;
  }
</style>

## Education
* Ph.D. in Mechanical Engineering, University of Connecticut, 2026
* B.S. in Mechanical Engineering, summa cum laude, Iowa State University, 2021

## Work experience
* July 2026 -- Present: **Senior Battery Engineer**
  * AST SpaceMobile, Homestead, FL, USA

* June 2025 -- August 2025: **Engineering Development Intern**
  * [The MathWorks, Inc.](https://www.mathworks.com), Natick, MA, USA
  * Duties included: 
    * Developed customer-facing functions for battery data analysis and feature engineering, targeted for future release. 
    * Analyzed use cases, pain points, design alternatives, and functional requirements for new API design.
    * Benchmarked functions to extract predictive features from battery electrochemical impedance data.
    * Prototyped Python-MATLAB workflows for anomaly detection algorithms, accelerating internal benchmarking.

* May 2024 -- August 2024: **Engineering Development Intern**
  * [The MathWorks, Inc.](https://www.mathworks.com), Natick, MA, USA
  * Duties included: 
    * Built a deep learning model to identify current pulses in battery data, improving accuracy over baselines.
    * Prototyped functions for feature extraction from Li-ion battery current pulses. 
    * Authored [an example on pulse feature extraction](https://www.mathworks.com/help/predmaint/ug/automatic-data-segmentation-and-feature-extraction-for-reference-performance-battery-test.html), integrated into MATLAB’s Predictive Maintenance Toolbox.
    * Benchmarked ensemble learning algorithms for battery state-of-health estimation.

<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3 -->

## Publications
<ul class="cv-entry-list">{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Talks
<ul class="cv-entry-list">{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
   -->

## Service and leadership
* Reviewer (November 2022--Present) 
  * [Joule](https://www.cell.com/joule/home)
  * [Nature Communications](https://www.nature.com/ncomms/)
  * [IEEE Transactions on Industrial Informatics](https://www.ieee-ies.org/pubs/transactions-on-industrial-informatics)
  * [IEEE Transactions on Industrial Electronics](https://www.ieee-ies.org/pubs/transactions-on-industrial-electronics)
  * [Journal of Energy Storage](https://www.sciencedirect.com/journal/journal-of-energy-storage)
  * [Engineering Optimization](https://www.tandfonline.com/journals/geno20)
  * [Sustainable Energy & Fuels](https://pubs.rsc.org/en/journals/journalissues/se#!recentarticles&adv)
  * [Journal of Mechanical Design](https://asmedigitalcollection.asme.org/mechanicaldesign)
  * [Future Batteries](https://www.sciencedirect.com/journal/future-batteries)

* Social Media Director (June 2025--May 2026), John Lof Scholar (September 2024--May 2026):  
  * [John Lof Leadership Academy](https://jlla.engr.uconn.edu/) 
  * [Personal JLLA Profile](https://jlla.engr.uconn.edu/meet-tingkai-li/)
 
* Social Media Director (November 2024--August 2025) 
  *  [Mechanical Engineering Graduate Student Association at UConn](https://www.linkedin.com/company/megsa-uconn/)

