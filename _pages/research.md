---
title: ""
permalink: /research/
author_profile: false
---

## Work in Progress

### [The Race Gap in Residential Energy Expenditures](/files/race_energyGap_2020-6-15.pdf)

Black households have higher residential energy expenditures than white households in the US. This residential energy expenditure gap persists after controlling for income, household size, home-owner status, and city of residence. It decreased but did not disapper between 2010 and 2017, and it is fairly stable in levels across the income distribution, except at the top. Controlling for home type or vintage does not eliminate the gap, but survey evidence on housing characteristics and available appliances is consistent with the gap being driven at least in part by differences in housing stock and related energy efficiency investments.

## Publications

### [Regulating Mismeasured Pollution: Implications of Firm Heterogeneity for Environmental Policy](/files/RegulatingMismeasuredPolution.pdf)
With Joe Shapiro and Reed Walker. *AEA Papers and Proceedings* (2018)

We estimate within-industry heterogeneity in energy and CO2 productivity for industries spanning the entire US manufacturing sector. We show that heterogeneity in energy and CO2 productivity across plants is enormous and exceeds heterogeneity in most other productivity measures. This has important implications for environmental policies targeting industries rather than plants.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
