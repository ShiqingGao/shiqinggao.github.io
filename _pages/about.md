---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently a Ph.D. student at the School of Computer Science and the John Hopcroft Center for Computer Science, Shanghai Jiao Tong University. 

My research interests span reinforcement learning, constrained optimization, and reasoning in large language models. I am particularly interested in developing theoretically grounded algorithms that enable intelligent agents to explore safely and reason efficiently under constraints.

I have published multiple papers at the top international AI conferences such as ICML and IJCAI, with one of my works recognized as an ICML Oral presentation.






# 🔥 News
- *2025.06*: &nbsp;🎉🎉 Our paper was accepted to ICML 2025 as an <span style="color:blue">**Oral presentation** (*Top 1%*)</span>.
- *2025.05*: &nbsp;🎉🎉 Our paper is accepted by ICML 2025 as <span style="color:blue">**splotlight**</span>. 
- *2025.05*: &nbsp;🎉🎉 Our paper is accepted by ICML 2025.
- *2024.04*: &nbsp;🎉🎉 Our paper is accepted by IJCAI 2025. 


# 📝 Publications 

<!-- [**Project**](hhttps://github.com/ShiqingGao/MICE) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025 Oral</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:blue">**ICML 2025**</span> · <span style="color:#e67300"><strong>Oral (Top 1%)</strong></span> · <span style="color:#1a75ff"><em>First Author</em></span> · May 2025  
[Controlling Underestimation Bias in Constrained Reinforcement Learning for Safe Exploration](https://openreview.net/pdf?id=nq5bt0mRTC), **Shiqing Gao**, et al.
[**Code**](hhttps://github.com/ShiqingGao/MICE)

- Proposed the **Memory-driven Intrinsic Cost Estimation (MICE)** algorithm to mitigate value underestimation in constrained RL. 
- Utilizes a memory module to record high-risk regions, generate intrinsic costs, and apply an **extrinsic–intrinsic cost update scheme**, significantly reducing violations while preserving policy performance. 
- Provided a theoretical **upper bound on constraint violations** and proved **value function convergence**.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:blue">**ICML 2025**</span> · <span style="color:#1a75ff"><em>First Author</em></span> · May 2025  
[Extreme Value Policy Optimization for Safe Reinforcement Learning](https://openreview.net/pdf?id=3aC94m0wbF), **Shiqing Gao**, et al.
[**Code**](hhttps://github.com/ShiqingGao/EVO)

- Introduced **Extreme Value Policy Optimization (EVO)** based on **Extreme Value Theory (EVT)** to explicitly model tail extreme events. 
- Developed an **extreme value quantile constraint** and an **extreme-value-prioritized replay** mechanism to leverage rare events in policy updates, reducing violation probability. 
- Theoretically proved **lower violation probability and variance** and derived quantiles ensuring **zero violations**.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:blue">**IJCAI 2024**</span> · <span style="color:#1a75ff"><em>First Author</em></span> · Apr. 2024  
[Exterior Penalty Policy Optimization with Penalty Metric Network under Constraints](https://www.ijcai.org/proceedings/2024/443), **Shiqing Gao**, et al.
[**Code**](hhttps://github.com/ShiqingGao/EPOPMN)

- Developed an efficient **first-order exterior penalty optimization (EPO)** algorithm with a **penalty metric network** to capture policy-space penalties. 
- Introduced an **surrogate penalty function** within a trust region to balance reward and constraint satisfaction.
- Guaranteed **monotonic violation reduction**, **algorithm convergence**, and provided bounds on violations and approximation error.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:blue">**Neurocomputing (JCR Q1)**</span> · <span style="color:#1a75ff"><em>First Author</em></span> · Apr. 2022  
[Deterministic Policy Optimization with Clipped Value Expansion and Long-Horizon Planning](https://bura.brunel.ac.uk/bitstream/2438/24394/2/FullText.pdf), **Shiqing Gao**, et al.

- Proposed a **model-based deterministic policy gradient (MBDPG)** method combining a **Mixture Gaussian dynamics model** with **long-horizon planning**. 
- Incorporated **clipped value expansion** to reduce overestimation bias, significantly improving sample efficiency and convergence.

</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">OCMA</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<span style="color:blue">**Ocean & Coastal Management (JCR Q1)**</span> · <span style="color:#1a75ff"><em>First Author</em></span> · Feb. 2022  
[Container Ocean Shipping Network Design Considering Carbon Tax and Choice Inertia of Cargo Owners](https://www.sciencedirect.com/science/article/abs/pii/S0964569121004695)  

**Shiqing Gao**, et al.

- Proposed a **shipping network optimization model** incorporating **carbon tax** and **cargo owners’ choice inertia**. 
- Solved via a **genetic algorithm**, enhancing operational decision-making for liner companies under varying carbon and demand scenarios.

</div>
</div>






# 🎖 Honors and Awards
- *2022.04* Outstanding Graduate of Shanghai Municipality. 
- *2019.09* Outstanding Graduate of Beijing Municipality.
- Multiple national and university-level scholarships and honorary titles

# 📖 Educations
- *2022.09 - 2025.08 (now)*, Shanghai Jiao Tong University. 
- *2019.09 - 2022.06*, Tongji University.
- *2015.09 - 2019.06*, Beijing Jiao Tong University. 


# 💬 Invited Talks

- ICML – Oral presentation at the Reinforcement Learning session.
- IJCAI – Oral presentation at the Reinforcement Learning session.



# 💻 Internships
- *2025.06 - 2025.08 (now)*, Tecent, Algorithm Intern, Game AI Technology **(Qingyun Program)**