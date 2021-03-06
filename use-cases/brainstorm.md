# Booklist Browser app domain use cases

## Booklist

![example4-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/andysylvester/federated-bookshelves/master/use-cases/example-uml-booklist.iuml)

Booklist elements - List of items that can be contained in a booklist (see Federated Bookshelves list and Library JSON list)

Point to other booklist - URL or location of another booklist

Point to blog post - URL or location of a blog post referring to a booklist


## Book

![example5-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/andysylvester/federated-bookshelves/master/use-cases/example-uml-book.iuml)

Booklist - List of items that can be contained in a booklist (see Federated Bookshelves list and Library JSON list)

## Booklist Editor

![example6-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/andysylvester/federated-bookshelves/master/use-cases/example-uml-booklist-editor.iuml)

Edit booklist - User can change any book element in a booklist

Read booklist - User can look at all entries in a booklist

Create booklist - User can create a new booklist, new list will not have any default values and have one book in the list

Display all book elements for a book in a booklist - User selects a book in the booklist and all elements for that book are displayed

Open booklist - User can select a booklist to review


## Booklist Analyzer

![example7-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/andysylvester/federated-bookshelves/master/use-cases/example-uml-booklist-analyzer.iuml)

Detect booklist change - Check current copy of a booklist against the stored copy to see if had changed

Detect booklist addition - If the booklist has changed, determine if the change was an addition

Detect booklist deletion - If the booklist has changed, determine if the change was a deletion

Create reverse-chronologic list of booklist updates - For all changes in booklists being followed, create a reverse-chronologic list of those changes


## Booklist Browser

![example8-uml](http://www.plantuml.com/plantuml/proxy?cache=no&src=https://raw.githubusercontent.com/andysylvester/federated-bookshelves/master/use-cases/example-uml-booklist-browser.iuml)

Display book reviews - Display book reviews in the booklist

View a booklist - User can view a selected booklist

Follow updates to booklists - User can select booklists that should be followed (supports creating list of booklist updates)

Create list of followed booklists - User can create a list of booklists to follow

Share list of followed booklists - Provides a URL or other some other location for a list of followed booklists (like an OPML subscription list for RSS)


# PlantUML Resources

Jonas Hackt (https://github.com/jonashackt/plantuml-markdown) - Links to examples

PlantUML Cheat Sheet (https://ogom.github.io/draw_uml/plantuml/) - Examples of most PlantUML in Github

PlantUML (https://plantuml.com/) - Home site of PlantUML software and documentation

Markdown native diagrams with PlantUML (https://blog.anoff.io/2018-07-31-diagrams-with-plantuml/)
