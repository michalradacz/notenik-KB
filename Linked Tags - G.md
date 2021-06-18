Title:  Linked Tags - G

Tags:   levels-outline.7 Merge Templates.3 Variable Modifiers

Timestamp: 20210616201430

Seq:    8.3.14

Level:  4 - Subsection

Body: 

Each tag found in the variable will be made into a link, linking to '=$relative$=yypathyy/xxtagxx.html', where 'xxtagxx' is the tag, and 'yypathyy' is the string of characters following the 'g'.

The contents of the class attribute for the anchor tag generated for each link can be supplied following the path, with an intervening semicolon to separate the two. 

Consider the following example. 

	=$tags&gtags/;btn btn-secondary mx-1 pr-topic$=

Where:

+ `tags` is the variable name;
+ `tags/` is the path, starting from the web root;
+ `btn btn-secondary mx-1 pr-topic` are classes to be applied to each link (`<a `) HTML tag.