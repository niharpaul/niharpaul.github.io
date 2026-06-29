---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<div class="publication-header">

# Publications

My research combines **physical oceanography, numerical modeling, observations,
and theory** to investigate multiscale ocean dynamics, including
submesoscale processes, near-inertial waves, equatorial dynamics,
and Indian Ocean variability.

{% if author.googlescholar %}
<p>
<a class="btn btn--primary" href="{{author.googlescholar}}">
Google Scholar
</a>

<a class="btn btn--primary" href="{{author.orcid}}">
ORCID
</a>

<a class="btn btn--primary" href="{{author.github}}">
GitHub
</a>
</p>
{% endif %}

</div>

---

## Research Areas

<div class="research-tags">

<span class="tag">Submesoscale Dynamics</span>

<span class="tag">Near-Inertial Waves</span>

<span class="tag">Internal Waves</span>

<span class="tag">Equatorial Waves</span>

<span class="tag">Indian Ocean</span>

<span class="tag">Marine Heat Waves</span>

<span class="tag">Ocean Modeling</span>

<span class="tag">Environmental Data Science</span>

</div>

---

## Featured Publications

Choose your 3–4 strongest papers and include an image,
summary, DOI, PDF, GitHub, and BibTeX.

Example:

<table>

<tr>

<td width="32%">

<img src="/images/front_transport.jpg">

</td>

<td>

### Near-inertial wave interaction with submesoscale fronts

A process study demonstrating how wave–vortex interactions
enhance convergence, divergence, and vertical tracer transport.

**Journal**

Geophysical Research Letters

**Links**

[PDF]

[DOI]

[Code]

</td>

</tr>

</table>

---

# Complete Publication List

{% for post in site.publications reversed %}

{% include archive-single.html %}

{% endfor %}
