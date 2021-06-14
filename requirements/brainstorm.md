This is a collection of possible requirements based on blog posts about the Library JSON/Federated Bookshelves concept

# Tom Critchlow’s original Library JSON post

Source: https://tomcritchlow.com/2020/04/15/library-json/ 

Book feed reader/book browser ideas 

Be able to display booklists from other people (display book cover images) (Bookshelf)

Indicate if the reader has finished the book (give a date) or is “in progress” (Bookshelf)

Present a reverse-chronologic list of updates to booklists (Feed)

	Someone created a booklist (list the books)
	Someone just finished reading a book (maybe link to a review)
	Someone added a book to their “in progress” list

# Matt Webb response to Tom Critchlow post 

Source: https://interconnected.org/home/2020/04/16/rss_for_books 

Subscribe to lists of books 

Subscribe to blog posts containing lists of books

Break up Library JSON into two parts:
	the library – posting at lists (best science fiction of 2020, etc)
	the booklist – a simple list of book objects

Tags for book objects could include
	Author
	Title
	Same-as links to Amazon, Open Library, etc
	Multiple “also-in” links where the user can show what other lists their book is in 
	Have a set of tags in the spec that are marked “experimental’ and seek feedback

An aggregator that showed me book reviews from everyone I follow explicitly, and also everyone they follow – but no-one else. 

# Phil Gyford response to Tom Critchlow post  

Source: https://www.gyford.com/phil/writing/2020/04/27/tracking-reading/

Possible elements in a booklist:

* reading start date/end date/finished?

* IDs - use Open Library?

* categories/tags

* author/role

* URL field

* review field


# Ton Zijlstra's post revisiting his initial post on Federated Bookshelves

Source: https://www.zylstra.org/blog/2021/04/federated-bookshelves-revisited/ 

multiple lists (by topic of interest, genre, language, year, author maybe) 

be able to point from one of my lists to another (from an author field in one list to an author centered list e.g.) 

links to author websites or their publisher would be useful, as is a link to a list sharer’s/reader’s blogpost 

be able to see/get/follow other people’s lists 

sharing a list of other people’s lists I follow 

be able to adopt entries in other people’s lists into one of my lists (e.g. an authour, a book or thematic list 

be great if such lists could be imported somehow into tools people might use, e.g. Calibre, Delicious Library, Zotero 


# Ton Zijlstra's post summarizing discussion on use of RSS/OPML/JSON for Federated Bookshelves concept 

Source: https://www.zylstra.org/blog/2021/05/going-in-opml-rss-json-circles/

Discovery, of books and people reading them, is my core aim for federation

OPML seems useful for lists (of lists)

RSS seems useful for content about books

Both depend on using specific book related data attributes which will have limited standardisation, even if they follow existing namespaces. It is impossible to depend on or assume standardisation, something more flexible is needed

My current OPML lists points to other lists by me and others, and to RSS feeds by me and others

I’m willing to generate OPML, RSS and JSON versions of the same lists and content if useful for others, other than templating there’s no key difference after all

Probably my website is not the core element in creating or maintaining lists. It is for publishing things about books.

I’m interested in other people’s RSS feeds about books, and will share my list of feeds I follow as OPML

I need to figure out ways to create OPM/RSS/JSON etc directly from where that information now lives in my workflow and toolset

I need to figure out ways to incorporate what others share with me into my workflow and toolset. Whatever is shared through RSS already fits existing information strategies.

For a limited number of sources shared with me by others, it might make sense to create mappings of their content to my own content structures, so I can import/integrate them more fully.
