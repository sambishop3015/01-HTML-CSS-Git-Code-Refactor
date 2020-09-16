# 01-HTML-CSS-Git-Code-Refactor

# Semantics

	HTML	<div class="header"></div> ==> <header></header>
	CSS	.header ==> header

	HTML 	<div class="hero"></div> ==> <div id="pageImage"></div>
	CSS	.hero ==> #pageImage

	HTML	<div class="content"></div> ==> <main></main>
	CSS	.content ==> main

	HTML	Main Content - renamed SEO,Online Rep, Social Media classes all to mainBoxes
	CSS	Consolidated all classes to .mainBoxes

	CSS	Consolidated mainBoxes images to .mainBoxes img

	HTML	<div class="benefits"></div> ==> <aside></aside>
	CSS	.benefits ==> aside

	HTML	<div class="benefit-(lead, brand, cost)"></div> ==> <div class="benefits"></div>
	CSS	.benefit-(lead, brand, cost) ==> .benefits
	CSS	consolidated benefit image code to reduce redundancy
	CSS	consolidated benefit h3 code to reduce redundancy

	HTML	<div class="footer"></div> ==> <footer></footer>	
	CSS	.footer ==> footer

	HTML	<div></div> ==> <nav></nav>
	CSS	div ==> nav

	HTML	Removed no-essential classes in each mainBoxes divs. 

	HTML	Removed non-essential misc. img closing tags in aside section. 

# Misc. Refactoring
	
	HTML	<title>webpage</title> ==> <title>Horiseon</title>;
	HTML	Added notes to all pertinent items;
	HTML	Code organization;
	CSS	Code organization;

# Links/Buttons
	
	HTML	Added working URL links to nav buttons