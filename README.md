# MIT-NSE-thesis-Title-Page
The Latex template for the undergraduate thesis title page the MIT department of Nuclear Science and Engineering.

First of all congratulations on making it this far. You have survived 22.09, 22.05, 22.02, and many other grueling classes, which is awesome. Good for you. Pat yourself on the back. Now all you have to do is pass a few more classes and finish your thesis you will have a Bachelor's of Science from the Massachusetts Insitute of Technology in Nuclear Science and Engineering. So now let's get you through that final step. 

## Using this template

The template is set up so you don't have to manually edit the whole file. All of the edits and information you should know are in the headers.

If you are using the subfiles package you should un-comment line 18 so LaTeX knows this is a subfile.

The bulk of the editing work begins on line 43. This template uses custom commands. So all you have to do is update the command definition. An example custom command would be:

\newcommand{\thesis}{Foo Bar}

Only edit the Foo Bar part, nothing else.

### Options that need to be set
There a series of commands that need to be updated that look like the one above. The name for the one above is thesis. Below is a list of the command names, and what they do.

* Thesis: This is your thesis title. e.g. Doing stuff to Discover Things
* me: no that's you not me. It's Just the Author's full name as you would like it to appear.
* gradMoth: The Month you will be graduating. Your options are February, June, or September
* gradYear: The year you graduate, yes you need to know this.
* signDate: The date you actually sat down with your advisor and signed the official copy.
* advisorName: Your thesis advisor's name. It should include Prof or Dr. That's not their name.
* advisorTitle: The official title of your thesis advisor. You can look it up here: http://catalog.mit.edu/schools/engineering/nuclear-science-engineering/#facultystafftext
* ugChairName: Name of the Department's chair for Undergrad Education. Probably: Michael Short
* ugChairTitle: The title for the UG chair from the catalog above. 
* ugChairChair: The title for the UG chair saying their the UG chair e.g. Chairman, NSE Committee for Undergraduate Students
* copyStatement: This gets into the copyright statement of your thesis. Read below just uncomment which ever one applies to you.
* abstractart: Your thesis abstract!

## Who owns the copyright to your thesis?
Well that's a hard one because lawyers exist. Basically if in doubt ask the Technology Licensing Office. This helps with some guidelines. https://libraries.mit.edu/archives/thesis-specs/#copyright. The TL;DR, which isn't legally rigurous is that if you get paid by MIT to do any part of the thesis (e.g. UROP) MIT owns the thesis. If you do own the copyright you have to grant MIT a royalty-free license to freely distribute the thesis. Just uncomment the right line for you situation. 

## Useful Latex Links

Here's a bunch of useful links for writing your thesis in \LaTeX:
* This ShareLaTeX blog series has a ton of good info so give it a read: https://www.sharelatex.com/blog/2013/08/02/thesis-series-pt1.html
* This other ShareLaTeX blog helps with setting up a large document such as a thesis in multiple files. I am personally a fan of subfiles: https://www.sharelatex.com/learn/Multi-file_LaTeX_projects 
* Finally you should probably look over the MIT Libraries thesis specification page: https://libraries.mit.edu/archives/thesis-specs/

## Legal Note:

This is just created and maintained by undergrads it is by no means perfect, and not garaunteed to comply with the MIT Libraries guidelines. Also the author knows very little about copryight law so if in doubt ask a lawyer.
