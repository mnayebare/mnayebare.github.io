---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

<style>
/* Abstract toggle styling */
.abstract-toggle {
    cursor: pointer;
    color: #2c5aa0;
    text-decoration: none;
    font-size: 0.9em;
    margin-left: 5px;
}

.abstract-toggle:hover {
    text-decoration: underline;
    color: #1a3d6d;
}

/* Abstract content box */
.abstract-content {
    display: none;
    margin: 8px 0 25px 0;
    padding: 20px;
    background-color: #f9f9f9;
    border-left: 3px solid #2c5aa0;
    line-height: 1.6;
    font-size: 0.95em;
}

.abstract-content.show {
    display: block;
}

/* Paper title styling */
h4 {
    margin-bottom: 3px;
    line-height: 1.3;
}

h4 a {
    color: #000;
    text-decoration: none;
}

h4 a:hover {
    color: #2c5aa0;
}

/* Coauthor text */
.coauthors {
    font-size: 0.9em;
    color: #666;
    font-style: italic;
    margin: 3px 0 5px 0;
}

/* Section headers */
h3 {
    margin-top: 30px;
    margin-bottom: 20px;
    font-size: 1.1em;
    font-weight: 600;
}

/* Links styling */
.paper-links {
    margin-top: 10px;
    margin-bottom: 20px;
}

.paper-links a {
    color: #2c5aa0;
    text-decoration: none;
    margin-right: 15px;
}

.paper-links a:hover {
    text-decoration: underline;
}
</style>

<script>
function toggleAbstract(id) {
    var content = document.getElementById(id);
    var link = event.target;
    
    if (content.classList.contains('show')) {
        content.classList.remove('show');
        link.textContent = 'Abstract';
    } else {
        content.classList.add('show');
        link.textContent = 'Hide Abstract';
    }
}
</script>


### ["Peer Effects and Ethnicity in Uganda: Impacts of Coethnic and High-Ability Peers on University Performance"](/files/JMP_web_version.pdf)

<a href="javascript:void(0);" class="abstract-toggle" onclick="toggleAbstract('abstract1')">Abstract</a>

<div id="abstract1" class="abstract-content">
Empirical research has documented the negative impact ethnic diversity has on several political and economic outcomes in Sub-Saharan Africa, including economic growth, political engagement, conflict, and contributions to public goods. However, we know relatively little about educational peer effects in such settings, which are generally characterized by high ethnic diversity and cross-ethnic mixing. This paper studies the effect of coethnic and high-ability peers in student groups on academic outcomes at a large public university in Uganda, a country with pronounced ethnic heterogeneity and segregation. I link data on student-level university admissions with subsequent grades. Upon admission, dorm assignments are random conditional on gender, providing exogenous variation in peer group formation. On average, high-ability peers (irrespective of ethnicity) and coethnic peers (irrespective of ability) positively affect a student's performance. Whereas the coethnic peer effect disappears by the year of graduation, the high-ability peer effect persists and even increases in magnitude over time. The effect of high-ability coethnic peers on performance is statistically indistinguishable from that of high-ability noncoethnic peers. The results of heterogeneous effects analysis suggest that the entire coethnic peer effect is driven by students with little exposure to other ethnicities prior to enrolling at the university. The pattern of results is consistent with both psychological and peer-to-peer learning explanations that reflect the specific context of this study.
</div>

---

### ["The STEM Major Gender Gap: Evidence from Coordinated College Application Platforms Across Five Continents"](/files/stem_gap_multicountry.pdf)

<div class="coauthors">(with G. Artemov, A. Barrios-Fernández, A. Bizopoulou, M. Kaila, J. Liu, R. Megalokonomou, J. Montalbán, C. Neilson, S. Otero, J. Sun, and X. Ye)</div>

<a href="javascript:void(0);" class="abstract-toggle" onclick="toggleAbstract('abstract2')">Abstract</a>

<div id="abstract2" class="abstract-content">
Women account for only 35% of global STEM graduates, a share unchanged for a decade. We use administrative microdata from centralized university admissions in ten systems to deliver the first crossnational decomposition of the STEM gender gap into a pipeline gap (academic preparedness) and a choice gap (first-choice field conditional on eligibility). In deferred-acceptance platforms where eligibility is score-based, we isolate preferences from access. The pipeline gap varies widely, from -19 to +31 percentage points across education systems. By contrast, the choice gap is remarkably stable: high-scoring women are 25 percentage points less likely than men to rank STEM first.
</div>

---

### Selected Works in Progress

### "Is Affirmative Action the Answer to Gender Gap in STEM Majors?" 

<div class="coauthors">(with Saloni Chopra)</div>

<a href="javascript:void(0);" class="abstract-toggle" onclick="toggleAbstract('abstract3')">Abstract</a>

<div id="abstract3" class="abstract-content">
This paper analyze a gender-based affirmative action policy implemented in 2020 for STEM programs at Uganda’s largest public university. Pushing more women in STEM majors by relaxing the admission criterion may lead to a potential mismatch. Improved gender balance, on the other hand, can generate positive peer effects for the entire cohort, especially women. Linking different administrative datasets on student’s applications, admissions and college academic performance, we empirically assess the effects of the policy induced changes in gender composition, on students’ higher education outcomes. We first establish that the policy successfully increased women’s access to STEM majors, resulting in a 9-percentage-point rise in female enrollment in traditionally male-dominated fields. We document that women (men) entering treated majors after the policy have, on average, lower (higher) high school test scores than their counterparts in untreated majors. Despite this, the policy led to improved college GPA and reduced the likelihood of failing courses in the first year for both men and women in the treated majors. Even among the top high school applicants whose admission status were not affected by the policy, we find that both men and women in treated majors experienced significant GPA improvements. Women’s GPA rose by 8%, compared to a 4% increase for men. Our results suggest that increased gender diversity, brought by the policy, had positive spillover effects beyond its direct impact on enrollment.
</div>


### "Beliefs and the Demand for Employee Training: A Field Experiment with Small Firms in Uganda"

<div class="coauthors">(with Andy Brownback, Sarojini Hirshleifer, and Arman Rezaee)</div>

<a href="javascript:void(0);" class="abstract-toggle" onclick="toggleAbstract('abstract3')">Abstract</a>

<div id="abstract3" class="abstract-content">
This study examines how employers select employees for training and employee demand for training. We incentive-compatibly elicit employers' beliefs about which of their employees it would be socially optimal to train, as well as employers' preferences over which of their employees they choose to train. We will then investigate if employers' selection of workers is individually rational or driven by behavioral biases. Finally, we will measure employees' self-selection into training and its alignment with employers' selections. To ensure incentive compatibility of employer and employee choices, we provide employees from a sample of metalworking SMEs in Kampala, Uganda, with free, high-quality skills training. In addition, we conduct practical skills tests to measure employee metal working skills before and after training. <a href="https://www.socialscienceregistry.org/trials/11788">AEA RCT registration</a> (Baseline complete)
</div>

### "Thou Must be a Doctor or an Engineer: Unintended Consequences of a Compulsory Science Policy"

<div class="coauthors">(with Tess Lallemant and Henry Joe Opio)</div>

<a href="javascript:void(0);" class="abstract-toggle" onclick="toggleAbstract('abstract4')">Abstract</a>

<div id="abstract4" class="abstract-content">
We study the effect of Uganda's policy that made chemistry and physics compulsory in addition to biology and mathematics, which were already mandatory for all students in junior high school. We examine the impact of this policy on performance in national exams, the number of girls entering STEM fields at advanced levels, and the persistence of both boys and girls in STEM at university. Using test scores in national exams, university applications, and school-level registrations, our approach exploits pre-policy variation in the school-level share of candidates sitting for national chemistry and physics exams.
</div>

<!--
### Selected Works in progress
"Univeral Secondary Education"
-->

---

### Pre-PhD Research

**"The contribution of millennium development goals towards improvement in major development indicators, 1990–2015"**

<div class="coauthors">(with Rati Ram)</div>

*Applied Economics*, 2018

<div class="paper-links">
<a href="https://www.tandfonline.com/doi/abs/10.1080/00036846.2018.1494808">Paper</a>
</div>
