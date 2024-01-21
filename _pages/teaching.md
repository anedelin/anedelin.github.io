---
title: "Teaching"
layout: gridlay
sitemap: false
permalink: /teaching/
---

<style>
.btn{
    margin-bottom:0;
}
.jumbotron{
    padding-bottom:0px;
    padding-top:5px;
    margin-top:10px;
    margin-bottom:10px
}
</style>



## Teaching

Below there is the list of courses I taught through years in different Universities. For each course there is short description and 
explanation of my role. In most cases there are also my notes attached. For some of courses you can also find an extraction from 
the student evaluations (mostly in Swedish). If needed full evaluations can be send upon the request.  My current 
teaching statement can be found <a href="{{ site.url }}{{ site.baseurl }}/teaching/teaching_statement.pdf" target="_blank">here</a>. 

### Geneva University (2021-2023)

{% for myyear in site.data.years %}

{% assign yeartest = false %}
{% for publi in site.data.teaching %}
  {% if publi.university == 4 %}
    {% if publi.year == myyear.year %}
        {% assign yeartest = true %}
    {% endif %}
  {% endif %}  
{% endfor %}


{% if site.group_pub_by_year == true %}
{% if yeartest == true %}
### {{ myyear.year }}
{% endif %}
{% endif %}
 

{% for publi in site.data.teaching %}
{% if publi.year == myyear.year %}
{% if publi.university == 4 %}

<div class="jumbotron">
<div class="row">
<div class="d-none d-md-block col-sm-2">
  {% if publi.image %}
   <img src="{{ site.url }}{{ site.baseurl }}/images/teachpic/{{ publi.image }}" width="100%" style="margin-top:5px"/>
  {% endif %}
</div>
<div class="col-md-10 col-sm-12 col-xs-12">
  <b>{{ publi.title }}</b><br/>
  <i>{{ publi.role }}</i> <br/>
  {% if publi.notes %}<a href="{{ site.url }}{{ site.baseurl }}/teaching/{{ publi.notes }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-success">NOTES</button></a>{% endif %}{% if publi.eval %} <a href="{{ site.url }}{{ site.baseurl }}/teaching/evaluations/{{ publi.eval }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-warning">EVALUATIONS</button></a>{% endif %}{% if publi.abstract %} <a data-toggle="collapse" href="#{{publi.url}}" class="btn btn-sm btn-danger" role="button" aria-expanded="false" aria-controls="{{publi.url}}">DESCRIPTION</a>{% endif %}


{% if publi.abstract %}
<div class="collapse" id="{{publi.url}}"><div class="well-collapse">
 {{publi.abstract}}
</div></div>
{% endif %}

</div>
</div>
</div>

{% endif %}
{% endif %}
{% endfor %}

{% endfor %}


### University of Milano-Bicocca (2015-2018)

{% for myyear in site.data.years %}

{% assign yeartest = false %}
{% for publi in site.data.teaching %}
{% if publi.university == 2 %}
  {% if publi.year == myyear.year %}
   {% assign yeartest = true %}
  {% endif %}
{% endif %}
{% endfor %}

{% if site.group_pub_by_year == true %}
{% if yeartest == true %}
### {{ myyear.year }}
{% endif %}
{% endif %}
 

{% for publi in site.data.teaching %}
{% if publi.year == myyear.year %}
{% if publi.university == 2 %}

<div class="jumbotron">
<div class="row">
<div class="d-none d-md-block col-sm-2">
  {% if publi.image %}
   <img src="{{ site.url }}{{ site.baseurl }}/images/teachpic/{{ publi.image }}" width="100%" style="margin-top:5px"/>
  {% endif %}
</div>
<div class="col-md-10 col-sm-12 col-xs-12">
  <b>{{ publi.title }}</b><br/>
  <i>{{ publi.role }}</i> <br/>
  {% if publi.notes %}<a href="{{ site.url }}{{ site.baseurl }}/teaching/{{ publi.notes }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-success">NOTES</button></a>{% endif %}{% if publi.eval %} <a href="{{ site.url }}{{ site.baseurl }}/teaching/evaluations/{{ publi.eval }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-warning">EVALUATIONS</button></a>{% endif %}{% if publi.abstract %} <a data-toggle="collapse" href="#{{publi.url}}" class="btn btn-sm btn-danger" role="button" aria-expanded="false" aria-controls="{{publi.url}}">DESCRIPTION</a>{% endif %}


{% if publi.abstract %}
<div class="collapse" id="{{publi.url}}"><div class="well-collapse">
 {{publi.abstract}}
</div></div>
{% endif %}

</div>
</div>
</div>

{% endif %}
{% endif %}
{% endfor %}

{% endfor %}


### Uppsala University (2010-2015)

{% for myyear in site.data.years %}

{% assign yeartest = false %}
{% for publi in site.data.teaching %}
{% if publi.university == 1 %}
  {% if publi.year == myyear.year %}
   {% assign yeartest = true %}
  {% endif %}
{% endif %}
{% endfor %}


{% if site.group_pub_by_year == true %}
{% if yeartest == true %}
### {{ myyear.year }}
{% endif %}
{% endif %}
 

{% for publi in site.data.teaching %}
{% if publi.year == myyear.year %}
{% if publi.university == 1 %}

<div class="jumbotron">
<div class="row">
<div class="d-none d-md-block col-sm-2">
  {% if publi.image %}
   <img src="{{ site.url }}{{ site.baseurl }}/images/teachpic/{{ publi.image }}" width="100%" style="margin-top:5px"/>
  {% endif %}
</div>
<div class="col-md-10 col-sm-12 col-xs-12">
  <b>{{ publi.title }}</b><br/>
  <i>{{ publi.role }}</i> <br/>
  {% if publi.notes %}<a href="{{ site.url }}{{ site.baseurl }}/teaching/{{ publi.notes }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-success">NOTES</button></a>{% endif %}{% if publi.eval %} <a href="{{ site.url }}{{ site.baseurl }}/teaching/evaluations/{{ publi.eval }}.pdf" target="_blank"><button type="button" class="btn btn-sm btn-warning">EVALUATIONS</button></a>{% endif %}{% if publi.abstract %} <a data-toggle="collapse" href="#{{publi.url}}" class="btn btn-sm btn-danger" role="button" aria-expanded="false" aria-controls="{{publi.url}}">DESCRIPTION</a>{% endif %}


{% if publi.abstract %}
<div class="collapse" id="{{publi.url}}"><div class="well-collapse">
 {{publi.abstract}}
</div></div>
{% endif %}

</div>
</div>
</div>

{% endif %}
{% endif %}
{% endfor %}

{% endfor %}


