---
layout: default
title: Computing Projects
license: not needed
---

# Introduction

My main areas of interest are embedded systems, real-time, networking
and formal methods.

The key requirement for doing a project with me is that you should be
committed to developing a piece of software. If you're trying to avoid
programming as much as possible, you should probably talk to someone
else.

The next section gives a list of particular topics that I have in mind
for this year. Any one of them could form the basis of an interesting
project. If one or more of these topics grabs your interest, do some
googling to get a rough idea of what might be involved and then speak
to me to develop your ideas further. If you don't like any of these ideas
but you think you'd like to do something in a related area, speak to me
about it.

# Project ideas

* **Quadcopter**
The [Crazyflie Nano
Quadcopter](http://www.coolcomponents.co.uk/catalog/crazyflie-nano-quadcopter-p-1205.html)
is a new open-source development that offers many opportunities for
interesting projects, e.g. developing firmware for the heading and altitude
sensors, interfacing a tiny camera, working on algorithms for autonomous
flight etc. If you're interested in these projects, you'd need to be
prepared to purchase a kit yourself... and build it!

* **Online privacy and anonymity**
Online privacy and anonymity are currently hot topics following [Edward
Snowden's revelations](http://www.theguardian.com/world/the-nsa-files) about
the extent of government surveillance of electronic communications. The [PRISM
/ BREAK](http://prism-break.org/) organisation is already giving advice about
what steps users can take to enhance their online privacy. You could use your
project as an opportunity to find out more about some of the technical issues
involved. For example, you could
    * design and run some experiments using the [Shadow
      simulator](http://shadow.github.io/) to investigate aspects of the Tor
      anonymity network,
    * develop a prototype P2P anonymity network using
      [Python](http://python.org/) and its network event engine
      [Twisted](http://twistedmatrix.com/trac/wiki), or
    * investigate the use of a probabilistic model-checker for the analysis of
      anonymity protocols, e.g. see work by
      [Shmatikov](http://www.cs.utexas.edu/users/shmat/shmat_crowds.pdf).

* **Software-defined networking**
Software-defined networking is a new approach to networking in which the
control and data planes are clearly separated. This enables a more modular
approach to the provision of network services than has been possible so far.
Scott Shenker gave a [nice
presentation](http://www.youtube.com/watch?v=YHeyuD89n1Y) on the main ideas and
advantages a couple of years ago. A project in this area could use
[Mininet](http://mininet.org/) to
    * recreate networking experiments from the literature and compare your
      results, see, for example, [REPRODUCING NETWORK
      RESEARCH](http://reproducingnetworkresearch.wordpress.com/), or
    * build your own network controller to implement a new security policy, for
      example.

* **Quantum Leaps: event-driven programming for embedded systems**
The [Quantum Leaps](http://www.state-machine.com/) software provides a family
of lightweight, RTOS-like frameworks for event-driven programming of embedded
systems. A project in this area would involve deploying QP on the
[FRDM-K64F](https://os.mbed.com/platforms/FRDM-K64F/), implementing a small
control system using two different approaches, one using QP and another using a
more traditional OS such as uC/OS-II, and comparing the approaches, considering
performance of the code, ease of development, maintainability etc.

* **Internet of Things**
The [Internet of Things](http://mbed.org/cookbook/IOT) refers to a world where
a large number of physical objects are addressable via the Internet. The
reference above will give you some idea of what can be done. Your project can
tackle some similar problems but you will use the
[FRDM-K64F](https://os.mbed.com/platforms/FRDM-K64F/) as your target device.
You will need to integrate a WiFi module with this board, develop a simple
sensor application and then use the [HTML5
Websockets](http://mbed.org/cookbook/Websockets) framework to monitor and/or
control the application from the Internet.

The ideas below could also form the basis of a good project. Get in touch
if you'd like to discuss any of them with me.
<ul>
<li> Deploy and compare FreeRTOS and uC/OS-III on ARM platform</li>

<li> Add support for FAT filesystem to embedded OS. Analyse performance</li>

<li> Interface a communications module (e.g. Bluetooth, Zigbee, GSM,
GPS, ...) to embedded system development board. Design and implement
drivers and API. Test and analyse performance.</li>

<li> Develop Controller Area Network (CAN) driver and high-level API</li> 

<li> Investigate a real-time communications protocol, e.g. Flexray, TTA, TT-Ethernet, MILCAN</li>

<li> Design, implement and test 802.15.4 to CAN gateway</li>

<li> Implement and analyse performance of 6LoWPAN</li>

<li> Develop application and analyse performance of accelerometer module</li>

<li> Investigate tightness of bounds of WCET analyser</li>

<li> Apply model checking to analysis of security properties of a communciation protocol</li>

<li> Develop a tool to generate automatically correct ACLs from a
specification of required security properties</li>

<li> Investigate automatic code generation for CAN-based,
time-triggered embedded systems with multiple tick rates derived from
a shared clock.</li>

<li> Investigate the use of the precision time
  protocol <a href="http://www.ieee1588.com/">IEEE 1588</a> in
  distributed embedded systems.</li>
</ul>


# Writing your dissertation
<p><strong>Content and Presentation</strong></p>
<p>
Some of your content will be based on your literature review. This
will involve reading some literature. Unless you have a plan, your
reading will be inefficient. <a href="http://cgweb1.northumbria.ac.uk/SubjectAreaResources/cgdk2/how_to_read_a_research_paper.pdf">How to read a research
paper</a> is an excellent guide to forming a plan for reading a
paper. Follow its advice.
</p>

<p><a href="http://www.amazon.co.uk/Writing-Computer-Science-effective-Communication/dp/1852338024/ref=sr_1_1?ie=UTF8&amp;qid=1330186621&amp;sr=8-1">Writing
for Computer Science</a> is a good general text book about effective
communication in Computer Science.
</p>
<p>
If you don't want to splash out on a text book, there are several
sites with links to a variety of advice about how to write
clearly. Not all of the advice is directly relevant to writing a
B.Sc. or M.Sc. dissertation in Computing or Engineering. The advice
may not even be consistent. However, it is well worth reading, as you
begin to form your own ideas about how to write a good
dissertation. The sites that I find most useful are:
</p>
<ul>
<li><a href="http://www.computersciencestudent.com/">William Stallings How-To</a></li>
<li><a href="http://www.cs.cmu.edu/afs/cs.cmu.edu/user/mleone/web/how-to.html">Carnegie Mellon: Advice on Research and Writing</a></li>
<li><a href="http://www.cs.columbia.edu/~hgs/etc/writing-style.html">Writing technical articles</a></li>
</ul>

<p>
However, before rushing to devour all of the hints and tips available
from these pages, you should remember that the most valuable document
for you is the <strong>project handbook</strong> for the module that
you are studying. You should pay particular attention to the marking
guidelines and ensure that, for each part of your dissertation, you
have addressed <strong>all</strong> of the requirements of the marking
scheme. And when the project handbook requires an approach that
differs from that suggested by some other document, it is the project
handbook that you should follow. All of the general writing guidelines
in the world are of little benefit if you do not adhere strictly to
the specific requirements of the organization to which you intend to
submit your document.
</p>

<p>
Once you're clear about the advice in your project handbook, you may
find the following helpful for parts of your dissertation. Remember
that much of the advice below is written for academics intending to
submit a journal or conference paper. You'll need to interpret it
carefully to make it fit the requirements of a dissertation.
</p>

<p><em>Abstract</em></p>
<ul>

<li><a href="http://www.ece.cmu.edu/~koopman/essays/abstract.html">How
to write an abstract</a>: excellent advice from Philip Koopman.</li>

</ul>

<p><em>Main report body</em></p>
<ul>

<li><a href="http://www.sce.carleton.ca/faculty/chinneck/thesis.html">How
to organize your thesis</a>: intended mainly for Ph.D. dissertations -
but if you disregard the references to the need to demonstrate an
original contribution to knowledge, this works for M.Sc. and
B.Sc. dissertations too.</li>

<li><a href="https://www.microsoft.com/en-us/research/academic-program/write-great-research-paper">How
to write a great research paper</a>: you can guess this is advice
about writing a paper, not a dissertation - but if you ignore the
advice about length of each section, almost everything else applies to
writing a dissertation as well.</li>

</ul>

<p><em>Bibliography, references, citations</em></p>
<ul>
<li><a href="http://elp.northumbria.ac.uk/bbcswebdav/library/Library%20Content/Cite_them_right_secure.pdf">Cite them right</a>: essential reading.</li>
<li>Manage your bibliography with BibTeX. 
  <ul>
    <li>See <a href="http://www.tug.org/pracjourn/2006-4/fenn/">Managing
    Citations and Your Bibliography with BibTeX</a>
    and <a href="http://en.wikibooks.org/wiki/LaTeX/Bibliography_Management">LaTeX/Bibliography
    Management</a> to get started.</li>
    <li>Keep an archive of the papers that you read for your own use. Use <a href="http://www.lri.fr/~filliatr/bibtex2html/">bibtex2html</a>
    to produce html versions of your bibligraphy. Provide links to
    full text versions whenever possible.</li>
  </ul>
</li>
</ul>

<p><em>Style</em></p>
<ul>
<li><a href="http://www.guardian.co.uk/styleguide">Guardian style
guide</a>: I like the Guardian's style. It's a good guide to modern
British English.</li>
<li><a href="http://www.cs.columbia.edu/~hgs/etc/writing-bugs.html">Henning Schulzrine</a> and <a href="http://www.ece.ucdavis.edu/~jowens/commonerrors.html">John Owens</a> have more
specific advice about technical writing style.</li>
<li><a href="http://www.cl.cam.ac.uk/~mgk25/publ-tips/">Markus
Kuhn</a> offers good advice about preparing and preserving your
publications.</li>
</ul>

<p><strong>Tools</strong></p>
<p>
<em>Writing</em><br/>

It's hard to imagine why anyone would write a Computing or Engineering
project dissertation using anything other
than <a href="http://www.latex-project.org/">LaTeX</a>. Its key
benefit is that it allows you to concentrate on
the <strong>content</strong> of your writing rather than
its <strong>layout</strong>. Also, it handles automatically the
production of lists of contents, tables and figures, and, using
BibTeX, it makes it easy to produce a bibliography and to manage
citations. It also enables you to construct
more <a href="http://nitens.org/taraborelli/latex">beautiful</a>
documents.
</p>

I've made available
some [resources]({{site.baseurl}}{{site.raurl}}/latex_resources.tgz) that show you how to use this tool to produce a
dissertation. The <a href="http://www.ctan.org/tex-archive/info/lshort/english/lshort.pdf">Not
so short introduction to LaTeX</a> should be used to answer your
general LaTeX queries. There's also a
useful <a href="http://en.wikibooks.org/wiki/LaTeX/">LaTeX
Wikibook</a> that is worth a look.


<div>
<div class="pull-left">
<a href="assets/ra/latex_resources.tgz">
<img class="img-fluid" src="assets/images/download.png" 
     alt="Embedded Systems Circuit" width="60" style="margin:0px 5px"/>
</a>
</div>
<div> 
<strong>Download LaTeX resources, including a sample dissertation.</strong>
</div>
</div>

<br/><br/>

<div>
<em>Version control</em><br/> 
Writing a dissertation takes quite a long time. During this time you
will produce many versions of your dissertation. Occasionally, you
will be disappointed to discover that the latest version of your
dissertation is not entirely your best. You will be even more
disappointed if you cannot recover those parts from an earlier version
that you now realise were better than your latest version. You can
avoid this disappointment by using a version control system to
maintain all of your dissertation sources. There are several good,
modern version control systems that are freely available, including
  <ul>
    <li> <a href="http://git-scm.com/">Git</a>,</li>
    <li> <a href="https://www.mercurial-scm.org/">Mercurial</a>, and</li>
    <li> <a href="http://bazaar.canonical.com/en/">Bazaar</a></li>
  </ul>
If you are not already using one of these tools, you should begin
at once. Git is currently the most popular - start with it.
</div>

