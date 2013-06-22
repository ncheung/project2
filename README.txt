IAT381 - P02

COLUMN SYSTEM:

Two main columns: main-content (width: 75%) + sidebar-column (width: 25%)

Within main-content: 
	- heading-column (heading for each section e.g. Top Music)
	- heading-content-column (space between heading and the content e.g. album covers)
	- content-column (content column for large bodies of text e.g. Vinyl bros blurb)
	- content-sidebar-column (space between content and the sidebar)
	- album-column (each album is placed in its own column)

To make the content within main-content = 100%:
	1. heading-column + heading-content-column + content-column + content-sidebar-column
	2. heading-column + heading-content-column + album-column (x3) + content-sidebar-column

Reason main-content width: 75% is so that the content can float to the left of the sidebar (width: 25%). Thus, the content within main-content have to add to 100% (heading-column + heading-content-column + etc..)

Reason for "content-separator" before the fourth row is to push all the main content down so that it aligns better with the sidebar (the top of the content aligns with the top of the search bar). Without it, it looks like the sidebar starts too far down the page.

Reason for "first-separator" and "separator" is that in order to get the line to appear between the sections (e.g. between Vinyl Bros section and Top Music section) and in the right place on the page, the section is offset based on percentages. However, sometimes it inexplicably didn't work based on math so I had to create another div to manually adjust the values.

