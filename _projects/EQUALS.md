---
layout: page
title: ""
description: ""
img: assets/img/EQUALS/logo_EQUALS.png
importance: 2
category: Funded projects
permalink: /projects/equals
---

<div style="display: block; margin-bottom: 2em; text-align: left;">
  <img src="/assets/img/EQUALS/logo_EQUALS.png"
       alt="EQUALS – Low-carbon electricity modeling project logo"
       style="width: 100%; max-width: 480px; border-radius: 16px; background: white; padding: 0.5em; display: block; margin: 0 auto 1em auto;" />
git add
  <div>
    <div style="font-size: 1.07rem; font-weight: 400; color: #1d3557; letter-spacing: 0.5px; margin-bottom: 0.2em; line-height: 1.4;">
      EQUALS - Equitable Allocation of Low-carbon Electricity Sources in a Changing and Resource-limited World
    </div>
    <div style="border-left: 6px solid #0d6efd; background-color: #e9f1ff; padding: 1em 1.5em; margin: 1.5em 0; border-radius: 6px;">
      <strong>🔔 Note:</strong><br>
      <p style="margin-top: 0.5em;">
        <strong>EQUALS</strong> is a research project funded by the 
        <a href="https://anr.fr/en/call-for-proposals-details/call/generic-call-for-proposals-aapg-2025/" target="_blank" rel="noopener">
          French National Research Agency (ANR)</a> as part of the 2025 Generic Call for Proposals.<br>
        The project will begin in early 2026 and will run for four years.
        <br><br>
          <strong>🚀 We are hiring, join the team!</strong> Two internships, one PhD position, and one postdoctoral position are available.<br>
        👉 <a href="https://nuage.gresille.org/index.php/s/C5oq8qEP8F7gTDm" target="_blank"><strong>See the postdoc offer (PDF)</strong></a> | Contact: arthur.clerjon (at) cea.fr
      </p>
    </div>
  </div>
</div>



---

<p style="font-style: italic; font-size: 1.05rem; text-align: justify;">
  The project acronym <strong>EQUALS</strong> stands for 
 <em>“EQUItable Allocation of Low-carbon Electricity Sources in a Changing and Resource-limited World.”</em> Another possible name could have been <em>“Optimal Allocation of Low-carbon Electricity Sources […]”</em>, 
  reflecting the project’s dual ambition:
</p>

<ol>
  <li>
    To optimize the global allocation of low-carbon electricity sources in a resource-constrained world.
  </li>
  <li>
    To investigate how universal access to low-carbon electricity can be achieved in an equitable way—ensuring a decent standard of living while staying within planetary boundaries.
  </li>
</ol>

<hr style="width: 60px; border: none; border-top: 2px solid #ccc; margin: 1rem auto;">

## Quick Navigation

- [Project Summary](#project-summary)
- [An Interdisciplinary Team](#an-interdisciplinary-team)
- [Preliminary Results](#preliminary-results)
- [Downloads](#downloads)
- [Coming Soon](#coming-soon)

## Project Summary

**EQUALS** addresses a major global challenge: transitioning from fossil fuel-based energy systems to low-carbon alternatives, such as intermittent renewable energy sources (IRES), nuclear, and hydropower. In a world with limited raw material availability and planetary boundaries, this transition must ensure optimal resource use to provide the best possible energy service.
Indeed, the relevance of deploying an energy source varies from region to region, depending on climate, energy uses, and territorial specificities.

Funded by the ANR JCJC programme and coordinated by **Arthur Clerjon**, EQUALS explores how solar and wind energy can be most effectively distributed worldwide to reduce reliance on fossil fuels while respecting planetary boundaries, resource limitations, and territorial specificities.

To analyze such differences, we develop an innovative electricity system optimization model that integrates raw material availability at its core. 
This global analysis will be regionalized, taking into account local climates, energy demand, and territorial characteristics. The model will focus on the temporal match between electricity demand and IRES supply (e.g., wind, photovoltaic), accurately assessing flexibility needs and power system sizing.
The goal is to depict a global distribution of low-carbon energy sources that minimizes fossil fuel use, considering environmental and territorial constraints.

This project is built on a transparent methodology and an open-source model, making the results accessible to a wide audience. 
With this interdisciplinary and open approach, the project aims to co-construct transition scenarios, fostering broader participation in decision-making processes for energy systems sustainability.

**Overall, EQUALS seeks to:**

- Identify where and how low-carbon electricity can meet local demand;  
- Integrate constraints from planetary boundaries, material availability, and environmental compatibility;  
- Design deployment strategies that respect both regional equity and global sustainability.


## An Interdisciplinary Team

The EQUALS project builds on research by **Arthur Clerjon** during his [PhD thesis](https://hal.science/tel-03230033/). His work continues globally through the PhD research of **[Justine Duval](https://theses.fr/s399297)**, who is developing the project’s first proof of concept.

To explore the connection between energy and resources, the project collaborates with the **ISTerre** group led by [**Olivier Vidal**](https://www.isterre.fr/annuaire/pages-web-du-personnel/olivier-vidal/), with support from [**Hugo Le Boulzec**](https://www.researchgate.net/profile/Hugo-Le-Boulzec-2).

To bridge energy modeling with spatial and regulatory constraints, [**Emmanuelle Santoire**](https://latts.fr/membres/santoireemmanuelle/) (LATTS, CNRS) will lead efforts in geography and territorial planning. She will be joined by a master's intern (_position open_).

To integrate a climate perspective, **François-Marie Bréon** (CEA-LSCE) will bring expertise in climate science in order to assess and quantify influence of future climates on long-term energy demand and intermittent supply.

Finally, [**Fabien Perdu**](https://www.linkedin.com/in/fabien-perdu-7325a41a5/) and [**Pimprenelle Parmentier**](https://www.linkedin.com/in/pimprenelle-parmentier-6b0373131/) (CEA), co-supervisors of Justine Duval’s PhD, will support the methodological and technical development of the global energy model.

## Preliminary Results

EQUALS builds on previous research and incorporates the ongoing PhD work of Justine Duval. Below is an illustration of the project's approach, from the 2025 ECOS International Conference:

👉 [Duval et al. (2025) – ECOS Conference Paper](https://cea.hal.science/cea-05141769)

<a href="/assets/img/RQUALS/PV_distribution_ECOS.png" target="_blank">
  <img src="/assets/img/EQUALS/PV_distribution_ECOS.png" alt="Optimal PV/Wind allocation" style="max-width:100%; border: 1px solid #ccc; padding: 5px;">
</a>
<p style="font-size: 0.9rem;">Figure: Optimal mix of PV and wind by region (a), and by latitude (b), minimizing the need for dispatchable power. Source: ECOS 2025.</p>

Overall, this figure shows an optimal mixes of PV and wind that would minimize dispatchable power sources. To go further, here a some of the following steps:

- Increasing model complexity: to include interconnections, existing low-carbon dispatchable sources (hydro and nuclear)
- Adding regional and fglobal environmental  constraints, such as greenhouse gas budgets, land availability, etc. to assess how these constraints impact balances between power sources in each region.
- Building prospective energy demand and supply time-series, accounting for future climates and energy demand patterns.
- etc.

## Related Page and References

For more on the scientific foundation and background behind this work, see the [Power System Flexibility →](/projects/energy-system-flexibility) page.

These earlier studies form the conceptual and methodological basis of the EQUALS project.

---

## Downloads

<p>
  <a class="btn btn-primary" href="https://nuage.gresille.org/index.php/s/9TonKDSQCjWzkZr">📄 Full Proposal (PDF)</a><br>
  <a class="btn btn-outline-secondary" href="https://nuage.gresille.org/index.php/s/cLf7toepGt8nm3g">📃 Pre-Proposal</a>
  <a class="btn btn-outline-primary" href="https://nuage.gresille.org/index.php/s/sioYgnqM3AHDQyD">📝 Project Summary</a><br>
</p>

---
## Open Positions

<div style="border: 2px solid #28a745; background-color: #f0fff4; padding: 1.2em 1.5em; margin: 1.5em 0; border-radius: 8px;">
  <strong>🎯 Join the EQUALS team!</strong>
  <ul style="margin-top: 0.8em; margin-bottom: 0;">
    <li><strong>Postdoctoral researcher</strong> – Energy systems modeling & optimization<br>
        <a href="https://nuage.gresille.org/index.php/s/C5oq8qEP8F7gTDm" target="_blank">📄 Download the offer (PDF)</a></li>
    <li><strong>PhD position</strong> – Details coming soon</li>
    <li><strong>Master's internships (x2)</strong> – Details coming soon</li>
  </ul>
  <p style="margin-top: 1em; margin-bottom: 0;">
    📧 Contact: <strong>arthur.clerjon (at) cea.fr</strong>
  </p>
</div>

---

## Coming Soon

<ul>
  <li>📊 Interactive platform for exploring deployment scenarios</li>
  <li>📁 Access to datasets and source code</li>
  <li>📚 New publications and methodological notes</li>
</ul>


*Last updated: February 2026*
