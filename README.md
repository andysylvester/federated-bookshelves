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

Andy Sylvester creates a test viewer for Library JSON (http://andysylvester.com/2021/06/09/library-json-test-viewer-now-available/)

Andy Sylvester summarizes possible requirements for Federated Bookshelves/Library JSON (http://andysylvester.com/2021/06/13/requirement-brainstorm-and-some-tools-for-federated-bookshelves/), opens an issue for discussions, and added two tools on viewing OPML/JSON files to the Tools section on the main repo page.

Andy Sylvester took a cut at compiling requirements for Booklist Browser (http://andysylvester.com/2021/06/18/my-take-on-requirements-for-booklist-browser-app/)

## July 2021

Ravern Koh has set up a new instance of his Bookshelves app for Library JSON files (https://bookshelves.ravern.dev/) (mentioned by Andy Sylvester http://andysylvester.com/2021/07/01/tool-update-for-federated-bookshelves-library-json-project/)

Andy Sylvester tried out a new OPML toolkit and modified the client to read a booklist file (http://andysylvester.com/files/opmlclient/) (see also http://andysylvester.com/2021/07/04/another-opml-viewer-for-federated-bookshelves/)

Andy Sylvester created a set of requirements for Booklist Browser app, and refined the requirements into concepts and domains (http://andysylvester.com/2021/07/13/booklist-browser-app-update/). This repo now has folders for requirements and domains.

## December 2021

Chris Aldrich put out a call for a IndieWeb pop-up for personal libraries (https://boffosocko.com/2021/12/25/call-for-interest-indiewebcamp-pop-up-session-on-goodreads-replacements-and-decentralized-book-projects/), signup page at https://indieweb.org/2022/Pop-ups/Sessions#Personal_Libraries.

## January 2022

Ton Zijlstra created a workflow for creating OPML booklists from his Markdown notes in Obsidian (https://www.zylstra.org/blog/2022/01/federated-bookshelves-obsidian-notes-to-opml/), and published results of his production run of his scripts (https://www.zylstra.org/blog/2022/01/first-production-run-of-federated-bookshelves/) (see his Github repo (https://github.com/tonzyl/books_markdown_to_opml) for the scripts he used).

Andy Sylvester published an update on his work on federated bookshelves (https://andysylvester.com/2022/01/15/federated-bookshelves-january-2022-update/).

# Implementations

## Library JSON Booklists

Tom Critchlow booklist (https://tomcritchlow.com/library.json), can be viewed at https://bookshelves.ravern.dev/ or http://andysylvester.com/files/booklists/libraryJsonViewer01.html

## Federated Bookshelves OPML Booklists

Ton Zijlstra booklist (https://zylstra.org/opml/books/books.opml)

Andy Sylvester booklist (http://andysylvester.com/files/booklists/booklist.opml)

# Tools

Little Outliner (http://littleoutliner.com/) - Outliner that creates OPML files as its output format

Java Outline Editor (http://outliner.sourceforge.net/) - Can be used to create OPML outlines, not sure about attributes though...

Bookshelves (https://github.com/ravern/bookshelves) - Library JSON parser/viewer (new instance available at https://bookshelves.ravern.dev/ as of 7/1/2021)

OPML Client (https://github.com/scripting/opmlPackage/tree/main/client) - Example of OPML display client (instance of client demonstrating display of a Federated Bookshelves booklist at http://andysylvester.com/files/opmlclient/)

Library JSON Test Viewer (https://github.com/andysylvester/federated-bookshelves/blob/main/tools/libraryJsonViewer.html) - HTML file that can read a Library JSON file defined in a variable and display all the elements (based on example code from https://howtocreateapps.com/fetch-and-display-json-html-javascript/)

XSL stylesheet (https://zylstra.org/opml/books/test.xsl)  - method for display of Federated Bookshelves OPML booklists in human-readable form

OPML blogroll display in human-readable form (https://www.chrisfinke.com/2006/07/30/kickin-it-opml-style/), (https://www.zylstra.org/blog/2019/06/my-human-readable-opml-blogroll/) 

OPML Viewer (https://codebeautify.org/opmlviewer) - Can open an OPML file (local or online) and show original text and XML tree view

JSON Viewer (https://codebeautify.org/jsonviewer) - Can open a JSON file (local or online) and show original text and object view

# Formats

Library JSON (https://tomcritchlow.com/2020/04/15/library-json/) 

OPML book list structure (https://www.zylstra.org/blog/booklist-opml-data-structure/)

# Existing library-type services

Readernaut (https://readernaut.com/)

Library Thing (https://www.librarything.com/)

Bookwyrm (https://tech.lgbt/@bookwyrm)

Open Library (https://openlibrary.org/)

Libreture (https://www.libreture.com/)


