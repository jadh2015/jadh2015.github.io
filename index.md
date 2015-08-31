---
layout: default
---

### Encoding Cultural Resources

[The Japanese Association for Digital Humanities](http://www.jadh.org/)
is holding its fifth annual conference at the
[Insitute for Research in Humanities](http://www.zinbun.kyoto-u.ac.jp/e/institute/access-institute/access_e.htm),
Kyoto University, Japan, September 1-3,
2015. 

### News:

<div class="home">

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>

### Hosted by:

JADH2015 Organizing Committee
[[Members]({{ site.baseurl }}committee)]
 under the auspices of the Japanese Association for Digital Humanities
[[Home](http://www.jadh.org/)]

### Co-hosted by:

 * Institute for Research in Humanities (IRH), Kyoto University (KU)
   [[Home](http://www.zinbun.kyoto-u.ac.jp/e/)]
 * Center for Informatics in East Asian Studies, IRH, KU 
   [[Home](http://www.kita.zinbun.kyoto-u.ac.jp/)]
 * Center for Integrated Area Studies, KU [[Home](http://www.cias.kyoto-u.ac.jp/en/)]
<!---
The Center for Integrated Area Studies (CIAS) at Kyoto University was established with the aims of integrating information resources for area studies, conducting research in integrated area studies, and making research resources and facilities available to universities and other research institutions, both nationwide and globally.
-->
 * Graduate School of Letters, Kyoto University [[Home](http://www.kyoto-u.ac.jp/en/about/profile/faculty/faculties_and_graduate/letters.html)]
 <!-- * URA -->
 * Digital Humanities Initiative, Center for Evolving Humanities, Graduate
School of Humanities and Sociology, The University of Tokyo
 * International Institute for Digital Humanities
 [[Home](http://www.dhii.jp/index-e.html)]
 * Alliance of Digital Humanities Organizations [(ADHO)](http://adho.org)

### Supported by 

 * Kyoto University Research Administration Offices
 * The Kyoto University Foundation 

### Co-sponsored by:

 * IPSJ SIG Computers and the Humanities
[[Home](http://www.jinmoncom.jp/)]
 * Japan Art Documentation Society (JADS)
[[Home](http://www.jads.org/eng/index.html)]
 * Japan Association for East Asian Text Processing (JAET)
[[Home](http://www.jaet.gr.jp/index.html)]
 * Japan Association for English Corpus Studies 
[[Home](http://jaecs.com)]
 * The Mathematical Linguistic Society of Japan
[[Home](http://www.math-ling.org/e-index.html)]

<!--
 * Japan Association for the Contemporary and Applied Philosophy
[[Home](https://sites.google.com/site/jacapweb/)]
 * Japan Society of Library and Information Science (JSLIS)
[[Home](http://www.jslis.jp/aboutjslis_1_en.html)]
 * Japan Society for Information and Media Studies (JSIMS)
[[Home](http://www.jsims.jp/)]
-->

Copyright 2015 The Japanese Association for Digital Humanities
