---
title: "Blaauboer Group - Publications"
layout: gridlay
excerpt: "Blaauboer Group -- Publications."
sitemap: false
permalink: /publications/
---


# Publications

<div style="margin-bottom: 1.5em;"></div>

**At the end of this page, you can find the [full list of scientific publications](#full-list-of-publications) of our group, as well as [popular articles](#popular-articles) and [columns](#columns) I wrote on research, education, history of physics and society. All scientific papers are also available on [arXiv](https://arxiv.org/search/advanced?advanced=&terms-0-operator=AND&terms-0-term=Blaauboer%2C+M&terms-0-field=author&terms-1-operator=NOT&terms-1-term=Blaauboer%2C+Mirre+J&terms-1-field=author&classification-physics_archives=all&classification-include_cross_list=include&date-filter_by=all_dates&date-year=&date-from_date=&date-to_date=&date-date_type=submitted_date&abstracts=show&size=50&order=-announced_date_first).**    

<div style="margin-bottom: 1.5em;"></div>

## Group highlights

<div style="margin-bottom: 1.5em;"></div>


{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="33%" style="float: left" />
  <p>{{ publi.description }}</p>
  <p><em>{{ publi.authors }}</em></p>
  <p><strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong></p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


## Full List of publications

<div style="margin-bottom: 2.0em;"></div>

{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

<div style="margin-bottom: 2.0em;"></div>

## Popular articles

<div style="margin-bottom: 1.0em;"></div>

Publications on general aspects of teaching, research, history of physics and society (mostly in Dutch):

<div style="margin-bottom: 2.5em;"></div>

- [Hendrika J. van Leeuwen]({{ site.baseurl }}/downloads/Hendrika van Leeuwen.pdf), NTvN **81**, 8 (2015) - in Dutch
<div style="margin-bottom: 0.1em;"></div><br>
   (See also het [digitaal lexicon](http://resources.huygens.knaw.nl/vrouwenlexicon/lemmata/data/Leeuwen) van het Huygens Instituut)

- [Nanosciencefiction]({{ site.baseurl }}/downloads/Nanosciencefiction.pdf) (Review of the book “Spiral” by Paul McEuen), NTvN **78**, 52 (2012) - in Dutch

- [Quantum entanglement and locality](https://www.europhysicsnews.org/articles/epn/abs/2010/06/epn2010416p17/epn2010416p17.html) (invited feature article), EuroPhysics News **41**, 17-21 (2010)

- [De Bell-ongelijkheid testen met elektronen]({{ site.baseurl }}/downloads/Bell.pdf), NTvN **71**, 308-311 (2005) - in Dutch


<div style="margin-bottom: 2.5em;"></div>

## Columns and other items

<div style="margin-bottom: 1.5em;"></div>

These are columns I wrote for the [newsletter](https://kavli.tudelft.nl/newsletter) of the Kavli Institute of Nanoscience Delft 
between 2013-2015.

<div style="margin-bottom: 2.3em;"></div>

[Crowdfunding of research: valorisation at its best]({{ site.baseurl }}/downloads/Crowdfunding of research.pdf) (2015)

[A cheap and easy way to motivate people]({{ site.baseurl }}/downloads/Motivating people.pdf) (2015)

[Peer review on ArXiv]({{ site.baseurl }}/downloads/Peer review.pdf) (2014)

[At the QApple Store]({{ site.baseurl }}/downloads/QApple store.pdf) (2014)

[Management meeting]({{ site.baseurl }}/downloads/Management meeting.pdf)  (2014)

[Why engineers enjoy quantum]({{ site.baseurl }}/downloads/Engineers and quantum.pdf) (2013)

[Trust]({{ site.baseurl }}/downloads/Trust.pdf) (2013)

[Langevin]({{ site.baseurl }}/downloads/Langevin.pdf) (2013)

<div style="margin-bottom: 2.5em;"></div>

**Elementary particle poetry**: In 2021, the Dutch Physical Society (NNV) hosted the ‘Dicht een Deeltje’ competition, challenging participants to write poems (in Dutch) about particles in the Standard Model that combine literary quality with physical accuracy. My entries for the muon neutrino and the charm quark were awarded first prize in their categories and can be read alongside the other winners [here](https://www.natuurkunde.nl/artikelen/3669/het-standaardmodel-in-gedichten) (scroll down to the blue Standard Model diagram and select the particle).

<div style="margin-bottom: 2.5em;"></div>
