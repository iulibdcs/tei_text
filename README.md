<h1>TEI and Plain Text from Digital Collections Services, Indiana University Libraries</h1>
========

<h2>Overview</h2>
<p>Motivated by a recent mock keynote debate, "<a href="http://digitalcommons.unl.edu/englishfacpubs/106/">A Matter of Scale</a>," presented by Matt Jockers and Julia Flanders as part of the <a href="http://nulab.neu.edu/events/dhdays2013/">Boston Area Days of Digital Humanities Conference</a> and the imperative that librarians involved with many things "digital" learn not only how to build tools, in this case for textual analysis, but leverage existing tools to 
support teaching and research endeavors rooted in the text, I present TEI (P4 & P5) and plain text files of several e-text collections published by the Indiana University (IU) Libraries.</p>  

<p>Coming from the tool-building perspective and tradition, I seldom have time to explore existing tools for textual analysis.  This is partly because at IU we are so vested in textual markup following the TEI Guidelines for which few external tools exist that act on the markup (thus our focus on building). But as is the case with many academic libraries attempting to scale up digital production, we are not always in the position to build boutique interfaces, tools and functions for hand-crafted markup.  Further, often early research inquiries can be better defined if not answered by initially playing and experimenting with raw data sets before embarking on markup.  Finally, after many years of leading e-text initiatives and championing the TEI at my institution, I am eager to witness and document how these e-text collections fare in the wild.  What are the research motivations and inquiries that drive adaptation of the data and how are the data utilized and/or analyzed?  Are the TEI files we provide valuable to scholars, and if so, how?  What can we ascertain without/beyond the markup, and in turn, how does the markup aid researchers and research practices? </p>  

<p>The other motivator for this call is two-fold.  At IU we've always exposed the TEI/XML, but at the most atomic level.  I am exploring workflows moving forward in which we batch not only the TEI but other versions of the data, primarily plain text, for easier harvesting and re-purposing.  One reason for doing this – there are many good ones – is that we want to demonstrate to our faculty partners the possibilities of sharing data in this way.  The content can and should be analyzed, parsed, and remixed outside of the context of its native interface for broader impact and exposure.</p>

<p>What started as a <a href="http://dayofdh2013.matrix.msu.edu/mdalmau/2013/04/08/oh-the-one-fun-thing/">musing</a>, is finally gelling (in github, no less).  I look forward to learning how you appropriate this data, and I ask that you share this call as widely as possible with your students (great for class projects!) and colleagues (not necessarily plugged into core DH communication channels, but plugged nevertheless).   With your help, I hope to determine how to best push versions of this data into the flow.</p>

<p><b>So please FORK away!</b> And <b>POST</b> to this repository's <b><a href="https://github.iu.edu/dcs/tei_text/wiki">WIKI</a></b> with feedback, anecdotes of use, and links to this data in action so I can track your wizardry NSA-style.</p>

<h2>Data Sets</h2>
The following TEI/XML and plain text files are made available for good times:

* <a href="http://dlib.indiana.edu/collections/imh/">Indiana Magazine of History</a>, one the nation's oldest scholarly historical journal, 1905-2011 (TEI P4)
* <a href="http://dlib.indiana.edu/collections/vwwp/">Victorian Women Writers Project</a>, 1830-1929 (TEI P5)
* <a href="http://www.dlib.indiana.edu/collections/inauthors/">Indiana Authors and Their Books</a>, 1850-1929 (TEI Lite P4) 
* <a href="http://www.dlib.indiana.edu/collections/law/brevier/">Brevier Legislative Reports</a>, transcripts from Indiana State Legislature, 1858-1887 (TEI P5)
* Wright American Fiction,1851-1875 (undergoing web site migration, TEI P5)

<h2>Textual Analysis Tools</h2>
The following are a list of sample tools that can be used with the above data:

<h3>TEI-Aware Tools</h3>
* <a href="http://code.google.com/p/philomine/">PhiloLogic/PhiloMine</a> (installation required) 
* <a href="http://sourceforge.net/projects/txm">TXM</a> (installation required)

<h3>Plain Text Tools</h3>
* <a href="https://github.com/richardneal/Lexos">Lexos</a> (installation required)
* <a href="http://mallet.cs.umass.edu">Mallet</a> for topic-modeling (installation required) 
* <a href="http://voyant-tools.org">Voyant</a> for textual analysis (web-based)
* <a href="https://vue.tufts.edu/">VUE</a> for visualization and other analyses (registration and installation required)
