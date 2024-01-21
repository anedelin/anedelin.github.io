---
title: "About"
layout: gridlay
sitemap: false
permalink: /about/
---


## About  

{% for member in site.data.pi %}
<div class="jumbotron">
<div class="row">
<div class="col-sm-4">
  <img src="{{ site.url }}{{ site.baseurl }}/images/{{ member.photo }}" width="100%" style="max-width:250px"/>
</div>
<div class="col-sm-8 col-xs-12">
  <h3>{{ member.name }}</h3>
  <h4><i>{{ member.info }}</i></h4>
  {% if member.email %}<a href="mailto:{{ member.email }}" target="_blank"><i class="fa fa-envelope-square fa-3x"></i></a> {% endif %}
  {% if member.cv %} <a href="{{ site.url }}{{ site.baseurl }}/{{ member.cv }}" target="_blank"><i class="ai ai-cv-square ai-3x"></i></a> {% endif %}
  {% if member.scholar %} <a href="{{ member.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-3x"></i></a> {% endif %}
  {% if member.inspire %} <a href="{{ member.inspire }}" target="_blank"><i class="ai ai-inspire-square ai-3x"></i></a> {% endif %}
  {% if member.arxiv %} <a href="{{ member.arxiv }}" target="_blank"><i class="ai ai-arxiv-square ai-3x"></i></a> {% endif %}
  {% if member.orcid %} <a href="{{ member.orcid }}" target="_blank"><i class="ai ai-orcid-square ai-3x"></i></a> {% endif %}
  {% if member.researchgate %} <a href="{{ member.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-3x"></i></a> {% endif %}
  {% if member.github %} <a href="{{ member.github }}" target="_blank"><i class="fa fa-github-square fa-3x"></i></a> {% endif %}

  <ul style="overflow: hidden">
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 5 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  {% endif %}
  {% if member.number_educ == 6 %}
  <li> {{ member.education1 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education2 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education3 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education4 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education5 | replace: "-","&#8211;"}} </li>
  <li> {{ member.education6 | replace: "-","&#8211;"}} </li>
  {% endif %}
  </ul>
</div>
</div>
</div>
{% endfor %}

<div class="jumbotron">

<html>
<head>
  <meta charset="UTF-8">
  <title>Work Experience</title>
<link href="https://fonts.googleapis.com/css?family=Dosis" rel="stylesheet" type="text/css">
      <link rel="stylesheet" href="{{ site.url }}{{ site.baseurl }}/timeline.css">
</head>
 
<body>
<div class="container">
  <h1 class="main-title">Work Experience</h1>
			<ul class="timeline">	
				<li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/kings.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>King's College London <br> Research Associate</h1>
							<p>Since October 2023 I am working in the Theoretical Physics Division of 
King's College London.  </p>
					</div>
					<div class="date-l">10/2023 – Present</div>
				</li>
			  
				<li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/geneva.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>University of Geneva <br> Research Assistant</h1>
							<p> In August 2021 I moved to the Mathematics Department of Geneva University and 
joined group of <a style="color:#33ffff"  href="https://www.unige.ch/math/la-section/enseignants-et-chercheurs/alba-grassi" target="_blank" > Alba Grassi</a>. There I  continued my research of integrable systems emerging in supersymmetric gauge theories.  </p>
					</div>
					<div class="date-l">08/2021 – 08/2023</div>
				</li>
               
                <li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/technion.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>Israel Institute of Technology (Technion) <br> PostDoc Fellow</h1>
							<p>In 2018 I moved to Haifa to start PostDoc position at Technion. There I
worked with <a style="color:#33ffff"  href="https://phsites.technion.ac.il/razamat/" target="_blank">Prof. Shlomo Razamat</a>. Our main topic of collaboration which continues to the day is elliptic integrable 
models and their relation to the superconformal indices. During my years at Technion I also fruitfully collaborated 
with PhD student and other postdocs on various of topics related to supersymmetric QFT and black holes. .</p>
					</div>
					<div class="date-l">10/2018 – 08/2021</div>
				</li>


   <li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/bicocca.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>University of Milano-Bicocca <br> Research Assistant</h1>
							<p> After completing PhD degree I was hired as a postdoc researcher at the University of Milano-Bicocca. There 
I was working mainly on two projects. One project performed in collaboration with <a style="color:#33ffff"  href="https://virgilio.mib.infn.it/~zaffaron/" target="_blank">Prof. Alberto Zaffaroni</a> was related to the problem 
of the black holes microstate counting. At the same time in collaboration with <a style="color:#33ffff"  href="https://www.unimib.it/sara-pasquetti" target="_blank">Prof. Sara Pasquetti</a> I worked on aspects of 3d  dualities and 
their relation to 2d AGT-like dualities. </p>
					</div>
					<div class="date-l">09/2015 – 10/2018</div>
				</li>
				
 <li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/itep.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>Institute for Theoretical and Experimental Physics, Moscow <br> Research Engineer </h1>
							<p>During my studies in bachelor and master programs at the Moscow Institute of Physics and 
Technology I completed several research projects working at the Lattice Group of the Institute for Theoretical and Experimental physics. 
In particular under supervision of  <a style="color:#33ffff"  href="https://chernodub.pages.math.cnrs.fr/" target="_blank">Prof. Maxim Chernodub</a> 
I studied properties of different topological defects as well as phase diagram of QCD with chiral imbalance.</p>
					</div>
					<div class="date-l">09/2006 – 06/2010</div>
				</li>

			</ul>
</div>
</body>

</html>

</div>



<div class="jumbotron">

<html>
<head>
  <meta charset="UTF-8">
  <title>Education</title>
<link href="https://fonts.googleapis.com/css?family=Dosis" rel="stylesheet" type="text/css">
      <link rel="stylesheet" href="{{ site.url }}{{ site.baseurl }}/timeline.css">
</head>



<body>
<div class="container">
  <h1 class="main-title">Education</h1>
			<ul class="timeline">	
				<li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/uppsala.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>Uppsala University <br> PhD in Theoretical Physics</h1>
							 <p> <b>Thesis Title:</b> <i><a style="color:#33ffff" href="http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A787023&dswid=-8307" target="_blank">"Exact Results in Five-Dimensional Gauge Theories: On Supersymmetry, Localization and Matrix Models" </a></i><br> 
                                <b>Supervisor:</b> <a style="color:#33ffff" href="https://www.katalog.uu.se/profile/?id=N0-739" target="_blank">Prof. Joseph A. Minahan</a></p>
				      <p>During my doctoral studies at Uppsala University I have worked under the supervision of
                         <a style="color:#33ffff" href="https://www.katalog.uu.se/profile/?id=N0-739" target="_blank">Prof. Joseph A. Minahan</a></p>
                	     and <a style="color:#33ffff" href="https://www.physics.uu.se/research/theoretical-physics/people/mzabzine-webpage/" target="_blank">Prof. Maxim Zabzine</a>.
                        The focus of my research during these years was on the exploration of the matrix models emerging from supersymmetric gauge theories after 
                        supersymmetric localization. Using this approach I studied 5d gauge theories and obtained a number of important results in this field.
                    </div>
					<div class="date-l">06/2010 – 03/2015</div>
				</li>
			  
				<li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/mipt.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1>Moscow Institute of Physics and Technology <br> MSc in Applied Physics and Mathematics</h1>
							<p> <b>Thesis Title:</b> <i>"Topological Defects with nontrivial Hopf Index" </i> 
                                <b>Supervisor:</b> <a style="color:#33ffff" href="https://chernodub.pages.math.cnrs.fr/" target="_blank">Prof. Maxim Chernodub</a></p>
					</div>
					<div class="date-l">09/2008 – 06/2010</div>
				</li>
               
                <li class="timeline-blocks">
					<figure class="timeline-icon">
						<img src="{{ site.url }}{{ site.baseurl }}/images/logo/mipt.png" alt="timeline" />
					</figure>
					<div class="dir-r radius-3">
							<h1> Moscow Institute of Physics and Technology <br> BSc in Applied Physics and Mathematics </h1>
							<p> <b>Thesis Title:</b> <i>"Topological Defects in Abelian two-component Higgs Model" </i><br> 
                                <b>Supervisor:</b> <a style="color:#33ffff"  href="https://chernodub.pages.math.cnrs.fr/" target="_blank">Prof. Maxim Chernodub</a></p>
					</div>
					<div class="date-l">09/2004 – 06/2008</div>
				</li>


		
   </ul>


</div>
</body>

</html>

</div>



### Major Collaborators

{% for collab in site.data.collabs %}

<div class="jumbotron">
<div class="row">
<div class="col-md-10 col-sm-12 col-xs-12">
 <h4 class="display-9"><a style="color:#33ffff"  href="{{ collab.url }}" target="_blank"><strong> {{ collab.name }}</strong></a></h4>
<h4 class="display-15">{{collab.institution}}</h4>
 </div>
</div>
</div>


{% endfor %}


### Supervised Students

{% for student in site.data.students %}

<div class="jumbotron">
<div class="row">
<div class="col-md-10 col-sm-12 col-xs-12">
 <h5 class="display-9"><strong>{{student.name}}</strong></h5>
<h5 class="display-15">{{student.degree}}</h5>
<h5 class="display-15"><i>"{{student.title}}"</i></h5>
 {% if student.url %}<a href="{{ student.url  }}" target="_blank"><button type="button" class="btn btn-sm btn-primary">THESIS</button></a> {% endif %}
 </div>
</div>
</div>


{% endfor %}
