Title:  Template Module Parameters

Tags:   levels-outline.8 Script Files.2 Scripting Modules

Timestamp: 20210617211729

Seq:    9.2.4

Level:  4 - Subsection

Body: 

A Template command may have an action of 'webroot', 'open' or 'generate'.

#### Webroot

A 'webroot' action causes the value column to be used as a path to the top level of a website to be generated. Template variables of 'relative' will then be replaced with a series of '../' strings taking a file reference back to the top of the website. 


#### Open

The file pointed to by the path in the value column will be opened as a Template file.

#### Generate

The previously opened Template file will be processed according to the rules of [[Merge Templates]], generating one or more output files.