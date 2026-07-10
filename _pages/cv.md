---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% if site.author.cv %}
  <div class="wordwrap">You can also download my <a href="{{ site.author.cv }}">CV as a PDF</a>.</div>
{% endif %}

Education
======
* Ph.D. in Earth Sciences, University of Connecticut, Storrs, USA, Sep 2024 – Present
  * Advisor: Prof. Lijing Wang
  * Thesis: Beaver-Induced Groundwater-Surface Water Interactions in Southern New England Wetlands: A Model-data Integration Approach
* M.S. in Civil and Environmental Engineering, Seoul National University, Seoul, South Korea, Sep 2021 – Aug 2023
  * Advisor: Prof. Young-Oh Kim
  * Thesis: Analysis of Ensemble Streamflow Prediction Effect on Deriving Releases for Water Supply
* B.S. in Civil Engineering, Yeungnam University, Gyeongsan, South Korea, Mar 2016 – Aug 2021
  * Advisor: Prof. Yongwon Seo

Experience
======
* Jun 2026 – Jul 2026: Summer Visiting Scholar Fellowship, USGS FLOW (Future Leaders in Observation of Water) Academy
  * Conducted drone-based thermal mapping of a 1,600-meter reach of the Black Warrior River, collecting aerial thermal imagery to analyze spatial water temperature distributions across the watershed
  * Processed and orthorectified UAV imagery using Pix4D and Agisoft Metashape to generate high-resolution RGB and thermal orthomosaics
  * Completed hands-on workshops in microcontroller programming, edge computing, camera calibration, and AI-based water sensing (object detection and segmentation)
  * Collaborated with USGS scientists and industry partners to translate water sensing research into operational tools, presenting findings at bi-weekly report-outs and the FLOW Tech Showcase
  * GitHub: [iamkimyeonju/black-warrior-river-thermal-mapping](https://github.com/iamkimyeonju/black-warrior-river-thermal-mapping)

* Sep 2023 – Aug 2024: Researcher, University of Seoul
  * Focused on addressing the water distribution problem in South Korea's basins by applying optimization and agent-based model techniques
  * GitHub: [iamkimyeonju/agent-based-model](https://github.com/iamkimyeonju/agent-based-model)

* Apr 2021 – Jun 2021: Intern, Korea Hydro & Nuclear Power
  * As a member of the power plant inspection division, responsible for overseeing the safety and management of the pumped-storage dam

Research Projects
======
* Sep 2023 – Aug 2024: Researcher, Korea Environmental Industry & Technology Institute
  * Development of Scenario Neutral-based Drought Vulnerability Evaluation Technology for Multilateral Decision Making
* Apr 2023 – Aug 2023: Researcher, Ministry of Environment, Republic of Korea
  * Developing a Severity-Based Emergency Response Protocol for Water Shortage using Linked Operations of Water Supply Facilities
* Dec 2022 – Mar 2023: Researcher, Seoul National University
  * Study on Flood Countermeasures for a Case Study of Seoul National University Gwanak Campus
* Jun 2021 – Jun 2022: Researcher, Ministry of Environment, Republic of Korea
  * Study on the Establishment of a Comprehensive Plan for Creating a Safe Space for Water

Workshops
======
* Sep 8–10, 2025: ATS Short Course, Oak Ridge National Laboratory
  * Completed hands-on training in the Advanced Terrestrial Simulator (ATS), including model setup, execution, and solution of example hydrologic problems
* Mar 11–14, 2025: Early Career Critical Zone Workshop, HJ Andrews Experimental Forest
  * Participated in interdisciplinary training on Critical Zone science and delivered a presentation on beaver dam hydrology

Technical Skills
======
* Programming Languages: R, Python
* Version Control: Git, GitHub
* Publication Tool: LaTeX
* Hydrologic Modeling: Amanzi-ATS, MODFLOW
* Academic Tools: ENVI, ParaView
* GIS: ArcGIS Pro, QGIS
* Field Observation: SonTek FlowTracker2, HOBO data logger, vertical temperature probe, Spypoint trail camera, Emlid RTK GNSS, YSI, Teledyne FLIR thermal camera
* Image Processing: Pix4D, Agisoft Metashape

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
