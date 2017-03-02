<ul class="nav navbar-nav">
{% assign sorted_pages = site.pages | sort:"name" %}
{% for p in sorted_pages %}
{% if p.id != "home" %}
  <li>
    <a href="/RDDR{{ p.url }}">
  {{ p.title }}
    </a>
  </li>
{% endif %}
{% endfor %}
</ul>
 
## Audio Signal Processing SoC - ASP-SoC

### [Abstract](#abstract) [DE1](#de1-soc-by-terasic) [Team](#team) [Contact](#contact)

# Abstract

The aim of the project is...

# DE1-SoC by Terasic

<img src="http://www.terasic.com.tw/attachment/archive/836/image/image_71_thumb.jpg" width="600" >

<img src="http://www.terasic.com.tw/attachment/archive/836/image/DE1-SoC_Layout_top_01-01.jpg" width="600" >

For more information check [terasic DE1-SoC](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=836 "Terasic Homepage")

# Team

- Haberleitner David
- Posch Johannes
- Reisinger Thomas
- Steiger Martin
- Steinbacher Franz
- Wurm Michael

# Contact

<img src="/Pictures/fhLogo.png" width="120" >

**University of Applied Science Upper Austria**
**Campus Hagenberg**  
Department Hardware-Software-Design

Project Audio Signal Processing SoC - ASP-SoC  
**mail:** ASPSoC.fhHagenberg@gmail.com  

© 2017
