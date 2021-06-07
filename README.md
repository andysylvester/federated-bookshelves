# federated-bookshelves
Capturing information/resources on approaches to sharing information and opinions about books

# A Federated Bookshelves reader

Recently, Ton Zijlstra wrote about the concept of “federated bookshelves” (https://www.zylstra.org/blog/2021/04/federated-bookshelves-revisited/), in which he referenced a post by Tom Critchlow on a similar concept called “Library JSON” (https://tomcritchlow.com/2020/04/15/library-json/). I read through the postings flowing from Tom Crichlow’s post in 2020, and the ones from Ton Zijlstra’s post, and thought it would be helpful to provide a chronology of the development of this idea. To this end, I have created this Github repo with a chronology and links to tools and other distributed book info concepts that I have come across in reading on this topic. Pull requests and other comments are welcome! I am planning to spend some time on this in the next few weeks, so hopefully more prototypes and ideas to come….


# Chronology

## April 2020

Tom Critchlow proposes Library JSON (https://tomcritchlow.com/2020/04/15/library-json/), a format for enabling sharing of books and information/reviews on bookshelves

Ravern Koh built a prototype parser for Library-JSON (source at https://github.com/ravern/bookshelves, no current instance hosted (was at https://bookshelves.ravern.co, but no longer available)

Matt Webb responds to Tom Critchlow (https://interconnected.org/home/2020/04/16/rss_for_books), suggesting RSS and OPML as tools that could also be used for this idea.

Ton Zijlstra responded (https://www.zylstra.org/blog/2020/04/federated-bookshelves/), saying RSS and OPML might mean a more ready environment.

Tom McWright posted a response also leaning toward RSS (https://gist.github.com/tmcw/f88e31265363569ffcdcb709148fc8e8), also had comments several years ago on booklists (https://macwright.com/2017/12/11/indieweb-reading.html), has a reading list (https://macwright.com/reading/) 

Gregor Morill responded mentioning microformats (https://gregorlove.com/2020/04/a-lot-of-interesting-ideas/) 

Cory Doctorow started a Twitter thread on Tom Critchlow’s post (https://twitter.com/doctorow/status/1250830877615026177), which surfaced services Readernaut (https://readernaut.com/) and Library Thing (https://www.librarything.com/)

Phil Gyford responded with further thoughts on what to include in a listing (https://www.gyford.com/phil/writing/2020/04/27/tracking-reading/), mentioning that he has an app (https://github.com/philgyford/django-spectator) he has used to track his reading for over 20 years.

Jeremy Keith responded (https://adactio.com/journal/16803) also mentioning microformats as a mechanism for surfacing book information, and mentions a post by Mark Llobrera  (https://web.archive.org/web/20200812232538/http://dirtystylus.com/2020/04/17/visualizing-my-reading-with-semiotic/) on a tool he created to visualize his reading list (https://github.com/dirtystylus/reading-log).

## April 2021

Ton Zijlstra reviewed his post of a year ago and shared more thoughts on federated bookshelves (https://www.zylstra.org/blog/2021/04/federated-bookshelves-revisited/) proposing that OPML might be most simple approach.

## May 2021

Ton Zijlstra creates a proof of concept in OPML (https://www.zylstra.org/blog/2021/05/federated-bookshelf-proof-of-concept/), using an XSL stylesheet to make the OPML human-readable as well as machine-readable (https://zylstra.org/opml/books/books.opml). 

Ton Z gets a question from Tom Critchlow on being able to subscribe to OPML updates using RSS, and he responds (https://www.zylstra.org/blog/2021/05/on-opml-and-rss-for-federated-bookshelves/) 

Ton Zijlstra defines a OPML data structure based on his proof of concept (https://www.zylstra.org/blog/booklist-opml-data-structure/). 

Stephen Downes (https://downes.ca/) talks about Ton Zijlstra’s prototype and Tom Critchlow’s Library JSON (https://halfanhour.blogspot.com/2021/05/how-it-could-work.html) in the context of an open and distributed learning resource network. Ton responded (https://www.zylstra.org/blog/2021/05/16801/) with some questions/comments about RSS timestamps. Ton expanded on these comments (https://www.zylstra.org/blog/2021/05/going-in-opml-rss-json-circles/), exploring the ideas of Stephen Downes and Matt Webb (mentioned in April 2020 summary) on how RSS and OPML would best be used for this domain of books and information about books.

Andy Sylvester tries out Ton Zijlstra’s format for creating an OPML booklist (http://andysylvester.com/2021/05/31/getting-started-with-federated-bookshelves/), and has a problem displaying the result.

## June 2021

Ton Zijlstra suggests a solution to Andy Sylvester’s display problem (https://www.zylstra.org/blog/2021/06/andy-tries-out-my-opml-book-lists/), Andy tries it (http://andysylvester.com/2021/06/02/federated-bookshelves-update-1/) and still has issues, then figures out that the MIME type was not set up on his web hosting. After correcting that (http://andysylvester.com/2021/06/03/federated-bookshelves-update-2/), Andy is able to duplicate Ton’s results.

Andy Sylvester creates this repo and posts about it (http://andysylvester.com/2021/06/06/a-federated-bookshelves-reader/), and Stephen Downes comments (https://www.downes.ca/post/72424)

# Implementations

## Library JSON Booklists

Tom Critchlow booklist (https://tomcritchlow.com/library.json)

## Federated Bookshelves OPML Booklists

Ton Zijlstra booklist (https://zylstra.org/opml/books/books.opml)

Andy Sylvester booklist (http://andysylvester.com/files/booklists/booklist.opml)

# Tools

Little Outliner (http://littleoutliner.com/) - Outliner that creates OPML files as its output format

Java Outline Editor (http://outliner.sourceforge.net/) - Can be used to create OPML outlines, not sure about attributes though...

Bookshelves (https://github.com/ravern/bookshelves) - Library JSON parser/viewer

XSL stylesheet (https://zylstra.org/opml/books/test.xsl)  for display of Federated Bookshelves OPML booklists in human-readable form

OPML blogroll display in human-readable form (https://www.chrisfinke.com/2006/07/30/kickin-it-opml-style/), (https://www.zylstra.org/blog/2019/06/my-human-readable-opml-blogroll/) 

# Formats

Library JSON (https://tomcritchlow.com/2020/04/15/library-json/) 

OPML book list structure (https://www.zylstra.org/blog/booklist-opml-data-structure/)

# Existing library-type services

Readernaut (https://readernaut.com/)

Library Thing (https://www.librarything.com/)

Bookwyrm (https://tech.lgbt/@bookwyrm)

