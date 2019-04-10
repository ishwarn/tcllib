
[//000000001]: # (stringprep::data \- Preparation of Internationalized Strings)
[//000000002]: # (Generated from file 'stringprep\_data\.man' by tcllib/doctools with format 'markdown')
[//000000003]: # (Copyright &copy; 2007\-2009, Sergei Golovan <sgolovan@nes\.ru>)
[//000000004]: # (stringprep::data\(n\) 1\.0\.1 tcllib "Preparation of Internationalized Strings")

<hr> [ <a href="../../../../toc.md">Main Table Of Contents</a> &#124; <a
href="../../../toc.md">Table Of Contents</a> &#124; <a
href="../../../../index.md">Keyword Index</a> &#124; <a
href="../../../../toc0.md">Categories</a> &#124; <a
href="../../../../toc1.md">Modules</a> &#124; <a
href="../../../../toc2.md">Applications</a> ] <hr>

# NAME

stringprep::data \- stringprep data tables, generated, internal

# <a name='toc'></a>Table Of Contents

  - [Table Of Contents](#toc)

  - [Synopsis](#synopsis)

  - [Description](#section1)

  - [Bugs, Ideas, Feedback](#section2)

  - [Keywords](#keywords)

  - [Copyright](#copyright)

# <a name='synopsis'></a>SYNOPSIS

package require Tcl 8\.3  
package require stringprep::data 1\.0\.1  

# <a name='description'></a>DESCRIPTION

The __stringprep::data__ package is a helper for
__[stringprep](stringprep\.md)__, providing it with the data tables
needed to perform its functions\. It is an *internal* package which should not
be accessed on its own\. Because of that it has no publicly documented API
either\. Its implementation is generated by a script\.

# <a name='section2'></a>Bugs, Ideas, Feedback

This document, and the package it describes, will undoubtedly contain bugs and
other problems\. Please report such in the category *stringprep* of the
[Tcllib Trackers](http://core\.tcl\.tk/tcllib/reportlist)\. Please also report
any ideas for enhancements you may have for either package and/or documentation\.

When proposing code changes, please provide *unified diffs*, i\.e the output of
__diff \-u__\.

Note further that *attachments* are strongly preferred over inlined patches\.
Attachments can be made by going to the __Edit__ form of the ticket
immediately after its creation, and then using the left\-most button in the
secondary navigation bar\.

# <a name='keywords'></a>KEYWORDS

[stringprep](\.\./\.\./\.\./\.\./index\.md\#stringprep),
[unicode](\.\./\.\./\.\./\.\./index\.md\#unicode)

# <a name='copyright'></a>COPYRIGHT

Copyright &copy; 2007\-2009, Sergei Golovan <sgolovan@nes\.ru>