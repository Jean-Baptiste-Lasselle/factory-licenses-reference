
<body>
<div class="inner">
<!-- start of server/body-include-1.html -->



<!--
<div id="translations">
<p>
<span dir="ltr" class="original"><a lang="en" hreflang="en" href="/licenses/gpl-howto.en.html">English</a>&nbsp;[en]</span> &nbsp;
<span dir="ltr"><a lang="ca" hreflang="ca" href="/licenses/gpl-howto.ca.html">català</a>&nbsp;[ca]</span> &nbsp;
<span dir="ltr"><a lang="de" hreflang="de" href="/licenses/gpl-howto.de.html">Deutsch</a>&nbsp;[de]</span> &nbsp;
<span dir="ltr"><a lang="es" hreflang="es" href="/licenses/gpl-howto.es.html">español</a>&nbsp;[es]</span> &nbsp;
<span dir="ltr"><a lang="fr" hreflang="fr" href="/licenses/gpl-howto.fr.html">français</a>&nbsp;[fr]</span> &nbsp;
<span dir="ltr"><a lang="it" hreflang="it" href="/licenses/gpl-howto.it.html">italiano</a>&nbsp;[it]</span> &nbsp;
<span dir="ltr"><a lang="ja" hreflang="ja" href="/licenses/gpl-howto.ja.html">日本語</a>&nbsp;[ja]</span> &nbsp;
<span dir="ltr"><a lang="pl" hreflang="pl" href="/licenses/gpl-howto.pl.html">polski</a>&nbsp;[pl]</span> &nbsp;
<span dir="ltr"><a lang="pt-br" hreflang="pt-br" href="/licenses/gpl-howto.pt-br.html">português&nbsp;do&nbsp;Brasil</a>&nbsp;[pt-br]</span> &nbsp;
<span dir="ltr"><a lang="ru" hreflang="ru" href="/licenses/gpl-howto.ru.html">русский</a>&nbsp;[ru]</span> &nbsp;
<span dir="ltr"><a lang="ta" hreflang="ta" href="/licenses/gpl-howto.ta.html">தமிழ்</a>&nbsp;[ta]</span> &nbsp;
</p>
</div>
-->

<!-- end of server/body-include-1.html -->

<!-- start of server/body-include-2 -->




<div id="content">
<!-- end of server/banner.html -->

<h4><a href="https://www.gnu.org/licenses/gpl-howto.html">Page de Référence GNU, où ont été trouvées ces informations (lien ajouté par l'usine logicielle)</a></h4>



<h1>How to use GNU licenses for your own software</h1>



<p>This is a brief explanation of how to place a program under the <a
href="/licenses/gpl.html">GNU General Public License</a>, <a
href="/licenses/lgpl.html">GNU Lesser General Public License</a>, or <a
href="/licenses/agpl.html">GNU Affero General Public License</a>.  For the
<a href="/licenses/fdl.html">GNU Free Documentation License</a>, we have
a <a href="/licenses/fdl-howto.html">separate page</a>.</p>

<p>For further information, see our list
of <a href="/licenses/gpl-faq.html">frequently asked questions about
our licenses</a>.</p>

<p>If you are considering using the GNU Lesser General Public License,
please read the article &ldquo;<a href="/licenses/why-not-lgpl.html">Why
you shouldn't use the LGPL for your next library</a>&rdquo; first.  The
article explains why it may be better to use the ordinary GPL instead,
and how we would make the decision.</p>

<p>Here's a brief summary of what you need to do to release a program
under one of our licenses:</p>

<ul>
<li>Get a copyright disclaimer from your employer or school.</li>
<li>Give each file the proper copyright notices. Make
sure <a href="/licenses/identify-licenses-clearly.html">to clearly
identify which versions of the license users can use</a>.</li>
<li>Add a COPYING file with a copy of the GNU GPL or GNU AGPL.</li>
<li>Also add a COPYING.LESSER file with a copy of the GNU LGPL, if you
use that.</li>
<li>Put a license notice in each file.</li>
<li>(Optionally) make the program display a startup notice.</li>
<li>(If using the AGPL) make the program offer copies of its source code.</li>
</ul>

<p>This involves adding two elements to each source file of your
program: a copyright notice (such as &ldquo;Copyright 1999 Terry
Jones&rdquo;), and a statement of copying permission, saying that the
program is distributed under the terms of the GNU General Public
License (or the Lesser GPL, or the Affero GPL).</p>

<h3>The copyright disclaimer</h3>

<p>If you are an individual, and you have an employer or study in
a school, it's wise to ask your
employer or school to sign a copyright disclaimer for your
program, so it cannot later claim that the copyright belongs to it
and that you had no right to release the program at all.  This really
has nothing to do with the GNU GPL&mdash;it applies no matter which
free software license you use to release the program.</p>

<p>Here is a sample copyright disclaimer; just alter the names, title,
and program description as appropriate:</p>

<blockquote>
<p>Yoyodyne, Inc., hereby disclaims all copyright interest
in the program &ldquo;Woodpecker&rdquo; (which deconstructs trees)
written by James Hacker.</p>

<p><em>signature of Moe Ghoul</em> 1 April 1989<br />
  Moe Ghoul, President of Vice</p>
</blockquote>

<p>If you are a university student, we recommend you request the
disclaimer <a href="/philosophy/university.html"> at an early stage in
writing the program</a> to reduce resistance.  If you are not a
research assistant or teaching assistant, it could be that the university
has no claim to copyright on your work, but ask a lawyer to make
sure of that.</p>

<p>If you work, the best time to negotiate permission to release free
software is <em>when negotiating your employment agreement</em>.</p>

<h3>The copyright notice</h3>

<p>The copyright notice should include the year in which you finished
preparing the release (so if you finished it in 1998 but didn't post
it until 1999, use 1998).  You should add the proper year for each
past release; for example, &ldquo;Copyright 1998, 1999 Terry
Jones&rdquo; if some releases were finished in 1998 and some were
finished in 1999.  If several people helped write the code, use all
their names.</p>

<p>For software with several releases over multiple years, it's okay
to use a range (&ldquo;2008-2010&rdquo;) instead of listing individual
years (&ldquo;2008, 2009, 2010&rdquo;) if and only if every year in
the range, inclusive, really is a &ldquo;copyrightable&rdquo; year
that would be listed individually; <em>and</em> you make an explicit
statement in your documentation about this usage.</p>

<p>Always use the English word &ldquo;Copyright&rdquo;; by international
convention, this is used worldwide, even for material in other
languages. The copyright symbol &ldquo;&copy;&rdquo; can be included if
you wish (and your character set supports it), but it's not necessary.
There is no legal significance to using the three-character sequence
&ldquo;(C)&rdquo;, but it does no harm.</p>

<p>If you have copied code from other programs covered by the same
license, copy their copyright notices too.  Put all the copyright
notices for a file together, right near the top of the file.</p>

<h3>The license files</h3>

<p>You should also include a copy of the license itself somewhere in the
distribution of your program.  All programs, whether they are released
under the GPL or LGPL, should include <a href="/licenses/gpl.txt">the
text version of the GPL</a>.  In GNU programs we conventionally put the
license in a file called COPYING.</p>

<p>If you are releasing your program under the GNU AGPL,
use <a href="/licenses/agpl.txt">the text version of the GNU AGPL</a>
instead of the GNU GPL.</p>

<p>If you are releasing your program under the Lesser GPL, you should also
include <a href="/licenses/lgpl.txt">the text version of the LGPL</a>,
usually in a file called COPYING.LESSER.  Please note that, since the
LGPL is a set of additional permissions on top of the GPL, it's crucial
to include both licenses so users have all the materials they need to
understand their rights.</p>

<h3>The license notices</h3>

<p>Each file's copying permission statement (also called the license notice)
should come right after its copyright notices.  For a one-file
program, the statement (for the GPL) should look like this, to use
GPL version 3 or later:</p>

<pre>
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see &lt;https://www.gnu.org/licenses/&gt;.
</pre>

<p>For programs that are more than one file, it is better to replace
&ldquo;this program&rdquo; with the name of the program, and begin the
statement with a line saying &ldquo;This file is part of NAME&rdquo;.
For instance,</p>

<pre>
    This file is part of Foobar.

    Foobar is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    Foobar is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with Foobar.  If not, see &lt;https://www.gnu.org/licenses/&gt;.
</pre>

<p>To use a different set of GPL versions, you would modify the end of
the first long paragraph.  For instance, to license under version 2 or
later, you would replace &ldquo;3&rdquo; with &ldquo;2&rdquo;.</p>

<p>This statement should go near the beginning of every source file,
close to the copyright notices.  When using the Lesser GPL, insert the
word &ldquo;Lesser&rdquo; before &ldquo;General&rdquo; in <em>all
three</em> places.  When using the GNU AGPL, insert the
word &ldquo;Affero&rdquo; before &ldquo;General&rdquo; in <em>all
three</em> places.</p>

<h3>Why license notices?</h3>

<p>The purpose of a free software license is to give certain rights to
all users of a program.  If it is not clear what rights you have given
them, that defeats the purpose.  Our practices are designed to
avoid any uncertainty.</p>

<p>If a program has a copy of a license FOO alongside the source files,
but doesn't have an explicit statement that &ldquo;This program is
released under license FOO,&rdquo; that leaves room for uncertainty
about whether the license FOO applies to the code of that program.</p>

<p>If a release has one statement that &ldquo;This program is released
under license FOO,&rdquo; in a central place such as the README file,
that makes the situation clear <em>for that release</em>.  However,
programmers often copy source files from one free program into
another.  If a source file contains no statement about what its
license is, then moving it into another context eliminates all trace
of that point.  This invites confusion and error.</p>

<h3>The startup notice</h3>

<p>For interactive programs, it is usually a good idea to make the
program display a brief notice about copyright and copying permission
when it starts up.  See <a href="/licenses/gpl-3.0.html#howto">the end
of the GNU GPL</a> for more information about this.</p>

<h3>The Affero notice</h3>

<p>If you are releasing your program under the GNU AGPL, and it can
interact with users over a network, the program should offer its source to
those users in some way.  For example, if your program is a web
application, its interface could display a &ldquo;Source&rdquo; link that
leads users to an archive of the code.  The GNU AGPL is flexible enough
that you can choose a method that's suitable for your specific
program&mdash;see section 13 for details.</p>

<h3>Miscellaneous</h3>

<p>It is very important for practical reasons to include contact
information for how to reach you, perhaps in the README file, but this
has nothing to do with the legal issues of applying the license.</p>

<p>There is no legal requirement to register your copyright with anyone;
simply writing the program makes it copyrighted.  However, for the US,
it is a good idea to register the copyright with the US Registry of
Copyrights, because that puts you in a stronger position against anyone
who violates the license in the US.  Most other countries have no system
of copyright registration.</p>

<p>We would like to list all free software programs in the Free
Software Directory, including all programs licensed under the GPL (any
version).  So please submit an entry for your program, when it has
reached the point of being useful.  Please see
the <a href="http://directory.fsf.org/">Directory web page</a> for
information and an online submission form.</p>

<p>It is also possible to make your program a GNU package, a part of the
GNU Project.  If you might be interested in joining up with the
GNU Project in this way, please see our <a
href="/help/evaluation.html">GNU software evaluation page</a> for more
information and a short questionnaire.  We will respond and discuss the
matter with you.</p>

<p>You are welcome to use any of our licenses even if your program
is not a GNU package; indeed, we hope you will.  They're available to
everyone.  If you'd like to advertise your use of a particular license,
feel free to use <a href="/graphics/license-logos.html"
title="GNU License Logos">one of our logos</a>.</p>

</div>
<div style="clear:both"></div>
<div id="back-to-top"><a href="#navigation"><span>TOP</span> &#9650;</a></div>

<hr class="no-display" />
<div id="fsf-links">
 <ul>
  <li class="gnu"><a href="/proprietary/proprietary.html">MALWARE</a></li>
  <li class="gnu"><a href="/graphics/graphics.html">GNU&nbsp;ART</a></li>
  <li class="gnu"><a href="/people/people.html">GNU'S&nbsp;WHO?</a></li>
  <li class="gnu"><a href="/server/sitemap.html">SITEMAP</a></li>
  <li><a href="//directory.fsf.org">SOFTWARE&nbsp;DIRECTORY</a></li>
  <li><a href="https://h-node.org/">HARDWARE</a></li>
 </ul>
</div><!-- /fsf-links -->

<div id="mission-statement">

<blockquote>
<p style="direction:ltr; text-align:left"><a href="//www.fsf.org"><img id="fsfbanner"
src="/graphics/fsf-logo-notext-small.png" alt=" [FSF logo] "/></a><strong>
&ldquo;The Free Software Foundation (FSF) is a nonprofit with a worldwide
mission to promote computer user freedom. We defend the rights of all
software users.&rdquo;</strong></p>
</blockquote>

<p id="support-the-fsf" class="button">
  <a class="join" href="//www.fsf.org/associate/support_freedom?referrer=4052">JOIN</a>
  <a class="donate" href="//donate.fsf.org/">DONATE</a>
  <a class="shop" href="//shop.fsf.org/">SHOP</a>
</p>

</div><!-- /mission-statement -->
<!-- end server/footer-text.html -->


<div id="footer">
<div class="unprintable">

<p>Please send general FSF &amp; GNU inquiries to
<a href="mailto:gnu@gnu.org">&lt;gnu@gnu.org&gt;</a>.
There are also <a href="/contact/">other ways to contact</a>
the FSF.  Broken links and other corrections or suggestions can be sent
to <a href="mailto:webmasters@gnu.org">&lt;webmasters@gnu.org&gt;</a>.</p>

<p><!-- TRANSLATORS: Ignore the original text in this paragraph,
        replace it with the translation of these two:

        We work hard and do our best to provide accurate, good quality
        translations.  However, we are not exempt from imperfection.
        Please send your comments and general suggestions in this regard
        to <a href="mailto:web-translators@gnu.org">
        &lt;web-translators@gnu.org&gt;</a>.</p>

        <p>For information on coordinating and submitting translations of
        our web pages, see <a
        href="/server/standards/README.translations.html">Translations
        README</a>. -->
Please see the <a
href="/server/standards/README.translations.html">Translations
README</a> for information on coordinating and submitting translations
of this article.</p>
</div>

<!-- Regarding copyright, in general, standalone pages (as opposed to
     files generated as part of manuals) on the GNU web server should
     be under CC BY-ND 4.0.  Please do NOT change or remove this
     without talking with the webmasters or licensing team first.
     Please make sure the copyright date is consistent with the
     document.  For web pages, it is ok to list just the latest year the
     document was modified, or published.
     
     If you wish to list earlier years, that is ok too.
     Either "2001, 2002, 2003" or "2001-2003" are ok for specifying
     years, as long as each year in the range is in fact a copyrightable
     year, i.e., a year in which the document was published (including
     being publicly visible on the web or in a revision control system).
     
     There is more detail about copyright years in the GNU Maintainers
     Information document, www.gnu.org/prep/maintain. -->

<p>Copyright &copy; 2001, 2007, 2008, 2009, 2013, 2014, 2017, 2018
Free Software Foundation, Inc.</p>

<p>This page is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by-nd/4.0/">Creative
Commons Attribution-NoDerivatives 4.0 International License</a>.</p>

<!-- start of server/bottom-notes.html -->
<div id="bottom-notes" class="unprintable">
<p><a href="//www.fsf.org/about/dmca-notice">Copyright Infringement Notification</a></p>
<div id="generic">


</div>
</div>
<!-- end of server/bottom-notes.html -->


<p class="unprintable">Updated:
<!-- timestamp start -->
$Date: 2018/12/15 14:02:36 $
<!-- timestamp end -->
</p>
</div>
</div><!-- for class="inner", starts in the banner include -->
</body>
</html>
