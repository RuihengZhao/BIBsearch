# BIBsearch

<p>BIBsearch consists of two or three application programs with simple command line interfaces.</p>
<p>Used C++ together with SQL and the static embedded SQL protocol to implement BIBsearch.</p>
<br>
<p>This applica
<p>Program bibauthor</p>
<p>This application is to print a list of publication records for each publication by an author with a name supplied as a
string argument on the command line.</p>
<br>
<p>Program bibmaint </p>tion inserts new publications into the database or modifies existing publications already in the database.</p>
<p>author(aid#name)<br>
authorurl(aid#url)<br>
book(pubid#title#aid1;: : :;aidk#publisher#year)<br>
journal(pubid#title#volume#number#year)<br>
proceedings(pubid#title#year)<br>
article(pubid#title#aid1;: : :;aidk#appearsin#startpage#endpage)</p>
<br>
<p>Database Schema</p>
