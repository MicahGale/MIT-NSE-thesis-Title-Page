# MIT NSE Thesis Title Page
The Latex template for the undergraduate thesis title page the MIT department of Nuclear Science and Engineering.

Thank you to Natasha Skowronski for actually doing all of the formatting and making this look pretty. 

First of all congratulations on making it this far. You have survived 22.09, 22.05, 22.02, and many other grueling classes, which is awesome. Good for you. Pat yourself on the back. Now all you have to do is pass a few more classes and finish your thesis you will have a Bachelor's of Science from the Massachusetts Institute of Technology in Nuclear Science and Engineering. So now let's get you through that final step. 

## Using this package 

You can include the package by using: 

    \usepackage{nseTitle}

The options are: `normal` or `upper`. These options change if chunks of the title page are in all upper-case or just use normal capitalization. The default is to use `upper`. If you want to use
normal capitalization use:

    \userpackage[normal]{nseTitle}

### Options that need to be set
There a series of commands that need to be run before you can run `\maketitle`.

* title: This is your thesis title. e.g. Doing stuff to Discover Things
* author: It's Just the Author's full name as you would like it to appear. You should keep this consistent with the name you give to the registrar for your degree application.
* gradMoth: The Month you will be graduating. Your options are February, June, or September
* gradYear: The year you graduate, yes you need to know this.
* date: The date you actually sat down with your advisor and signed the official copy.
* advisorName: Your thesis advisor's name. It shouldn't include Prof or Dr. That's not their name.
* advisorTitle: The official title of your thesis advisor. You can [look it up here.](http://catalog.mit.edu/schools/engineering/nuclear-science-engineering/#facultystafftext)
* ugChairName: Name of the Department's chair for Undergrad Education. Probably: Michael Short
* ugChairTitle: The title for the UG chair from the catalog above. 
* copyStatement: This gets into the copyright statement of your thesis. Read below and just uncomment which ever one applies to you.
* abstract: Your thesis abstract!
* iOwn: Whether or not you own the thesis. Pass true to this if you own it. Otherwise MIT owns it you can pass false or anything else you like.
* ugChairChair: The title for the UG chair saying they're the UG chair i.e. Chairman, NSE Committee for Undergraduate Students. Don't do anything with this unless you want to `renewcommand` it.

## Who owns the copyright to your thesis?
Well that's a hard one because lawyers exist. Basically if in doubt ask the Technology Licensing Office. [The library provides  some guidelines that help.](https://libraries.mit.edu/archives/thesis-specs/#copyright). The TL;DR, which isn't legally rigorous is that if you get paid by MIT to do any part of the thesis (e.g. UROP) MIT owns the thesis, otherwise it's yours. If you do own the copyright you have to grant MIT a royalty-free license to freely distribute the thesis. 

## Useful Latex Links

Here's a bunch of useful links for writing your thesis in \LaTeX:
* [This ShareLaTeX blog series has a ton of good info so give it a read](https://www.sharelatex.com/blog/2013/08/02/thesis-series-pt1.html)
* [This other ShareLaTeX blog helps with setting up a large document such as a thesis in multiple files. I am personally a fan of subfiles.](https://www.sharelatex.com/learn/Multi-file_LaTeX_projects)
* [Finally you should probably look over the MIT Libraries thesis specification page.](https://libraries.mit.edu/archives/thesis-specs/)

## Legal Note:

This is just created and maintained by undergrads it is by no means perfect, and not guaranteed to comply with the MIT Libraries guidelines. Also the author knows very little about copyright law so if in doubt ask a lawyer.
