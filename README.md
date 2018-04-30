# 1xx

https://1xx.studingwebdev.com

inside out project version 100.0
	- added header resize functionality
	
inside out project version 100.0
	- added footer resize functionality
	- added JQuery, tether, popper
	
inside out project version 100.2
	- fixed the footer by adjusting the bootstrap column widths wrapping them inside a bootstrap row
	
inside out project version 101.0
	- added first level of navigation
	- created assets/js/app.js
	- created assets/data/menu.json
	- moved header resize js to app.js
	
inside out project version 102.0
	- completed menuBuilder functiion in app.js
	- completed nav through menuBuilder function with recursion
	
inside out project version 102.1
	- completed css for navigation
	
inside out project version 103.0
	- fixed enlarging navigation on header shrink
	- added loader to application with gears
	
inside out project version 104.0
	- modified the ajax call to get the JSON for the menu form the me.studingwebdev.com site
	- modified the menuBuilder funcion to accept the JSON data from WordPress REST API
	-removed data/menu.json from file system considering it is no longer needed
	
inside out project version 104.0
	README.md file changes
	- prepended the title to the production site link
	- added link to GitHub Pages to the top of the content me WP Site Changes
		- WP Bootstrap Starter
			- Version: 3.0.11
			- By Afterimage Designs
	- added home page name "iophtml5 - home" to pages do not add to menu
		- added conten https://www.diffchecker.com/3ZeHoYyZ
		- nest all pages below home page "iop-html - home"
	- updated "Main Menu" to "iop-html5 Menu"
	
	iside out App Changes
	- index.html
		- code changes https://www.diffchecker.com/4k9vqfca
		- removed comments and cleaned code
		- adde dthe click event to the logo - calls the getPage function
		- removed both main content sections
		- added the circle loading div and content
	- syle.css
		- code changes https://www.diffchecker/jCetXEtM
		- added th logo & logo:hover classes for the logo in the header
		- added the section class to keep the page from closing all the way when there is no content
		- added the following classes for the loader circle
			- cirlce, wave, wave:before, wave:after
			- added keyframes for animation animate
	- app.js
		- code changes https://www.diffchecker.com/qS2xXeDk
		- removed comments and cleended code
		- added the getPage function to capture link clicks and get page content
		- adde getPage function call to the ajax call for the menus on page load to get the homepage
		- modified the forEach loop in the menuBuilder to include the pageid as a data atribute
		
	inside out project version 106.0
		me WP Site Changes
			- add the pages for the links in the general links section in the footer
				- contact us, frequently ask questions, terms & conditions, privacy policy
		
		inside out App Site Changes
			
			- index.html
				- code changes https://www.diffchecker.com/Td5ZPWg6
				-add id="genLinks" to the ul in the "General Links" section in the footer
			- app.js
				- code changes https://www.diffchecker.com/KBtMvQ7d
				-add ajax call to get the general links menu
				- add varibles to the menuBuilder function to accept id and class information