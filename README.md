# 01-week-refactor
Upon opening the HTML file, there was a quick view that the original author of this code was using non semantic elements throught his code.

Some of these were changed so that we can better understand what is going on in that certain area of the code. 

There were <div> used repeatedly and it made reading the code very hard. <sections> took the place of <div> so that the reader can see that a new chapter or section was being started.

Spacing and indentations were added to make things more clearly.

Alt attributes were added to the <img> files to make them accessible.

CSS file was not in order with the html file. Some things had to be moved around and changed so that they fall in sequential order.

The "search engine optimaization" source in <h2> wasn't working at first and nothing happened when you clicked on it, while the other siblings moved them to the correct <p>. It was fixed adding an "id" and now they all function.