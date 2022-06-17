# Horiseon Company Website

## Contributors:

* **Matthew Lyjak**

## Abstract:

Horiseon is a company specializing in Search Engine Optimization (SEO), Online Reputation Managment (ORM), and Social Media Marketing (SMM).

## Project Brief:

Horiseon has requested that their website be refactored according to Industry Standards for accessibility from all devices including for people with disabilities.  The company also requests source code be streamlined for future developers.

## Technologies used:

* HTML 5
* CSS
* GitHub
* Various Hardware including multiple different screen sizes and mobile devices

## Description:

https://mlyjak1.github.io/Challenge_1/

The Website is made up of 3 Main Parts: The Header, Content Blocks, and a Sidebar.

The Header contains the company name on a blue background with 3 internal-page links in the top right corner.  These links are set to turn black if moused-over and will direct to the internal Content Cards when clicked.  They will also condense to a vertical list if the width of the screen is too narrow.

The Main Content is found in 3 blocks on the left extending to the middle of the page.  They all have the same fonts and header attributes.

The sidebar has additional information for potential clients.  The block is set to be the same height as the combined main content blocks, and the text will shrink when the screen gets too small to accomodate it's regular size

Everything on the page is keyboard-selectable with the exception of the main image.  All text can be read via a screen reader that will also read the alt text behind any selectable image.  Every image except the main image has a title that will pop-up if moused over.  The alt captions were selected specifically to enhance SEO results and adhere to accessibility guidelines.  

![](assets/pictures/Horiseon%20Screenshot%20Mobile.png)


## Instructions for Future Developers:

Many of the individual blocks have identical attibutes.  To simplify the code, these attributes were all assigned to the blocks in their respective groups.  Each block or section is still identified by a specific ID for future changes if necessary.  The links at the top are currently internal, but may be used in the future to direct users to additional pages as they are added.

## Known Bugs:

This page has not been formatted for printing.


## License Information:

* Horiseon Social Solution Services, Inc. - Copyright 2019
* Source Code provided by Heart Industries. A subsidiary of Horiseon Social Solution Services.
* TM 6/17/22

## Version Information:

**0.0 - Initial Commit of Original Source Code - 6/15/22**

**0.1 - First Pass of HTML Code - Changelog:**
    
    *Changed <title> to Company name
    *Changed <div class="header"> to <section class="header">
    *Changed <div class="hero"> to <img class="hero"> and removed </div>
    *Changed <div class="content"> to <section class="content">
    *Removed redundant <span>
    *Removed unused  class="seo" from <h1> HTML
    *Changed <div class="benefits"> to <section class="benefits">
    *Changed <div class="footer"> to <section class="footer">
    
**0.11 - Second Pass of HTML Code Changelog:**

    *Changed <section class=*> to relevant element identifiers
    *Added <Figure> around main image "Hero"

**0.2 Search Engine Optimization and Site Flow Changelog:**
    
    *Added <alt> tags to images in <Main>
    *Added <alt> tags to icons in <aside>
    *Changed <divs> within <main> to <sections>
    *Removed extra un-used <IDs> from <main> <sections>
    *Changed <divs> within <aside> to <sections>
    *Added hover functionality to <header> links
    *Links in <header> now direct to sections in <main>

**0.3 CSS Clean-up and Optimization Changelog:**

    *Added reset.css as industry standard
    *Added "seo" class and <span> back in to HTML code
        *Made color of "seo" darker for better contrastmaintaing visibility standards
    *Header Modifications:
        *Removed .header div ul - Redundant
        *Removed p{font-size} - Unnessecary
    *Main Modifications:
        *Moved <main> elements in style.css above <aside> elements to math HTML
        *Consolidated #content <IDs> into .content section <class>
        *Consolidated #content-<IDs> img into .content img <class>
        *Consolidated #content<IDs> h2 into .content h2 <class>
    *Aside Modifications:
        *Removed color:white from #benefit-<IDs> and placed in .benefit<Class>
        *Consolidated #benefit-<IDs> for margin spacing to .benefits section <class>
        *Consolidated #benefit-<IDs> h3 to single command under .benefits h3 <class>
            *Added font-size:25 px to h3 for industry standard decreasing header sizes
        *Consolidated #benefit-<IDs> img to single command under .benefits img <class>

**0.4 Accessibility Modifications and Title Tag Additions Changelog:**

    *Added Titles to Images in Content Section
    *Added Titles to Icons in Benefit Section
    *Contrast of Benefit Section was not acceptable for Industry Standards, modified background color to the same as Content Section

**0.5 Media Query and Mobile Optimization Changelog:**

    *Tested website at various widths
        *Issue found with .header links and .benefits container
    *Added Media Query for .header div ul li element to be vertical when under 1020 pixel width
        *Added padding to .header div element to get it close to center
    *Changed .benefits height to static 940px to match .content height
    *Added Media Query for .benefits element to make text smaller to fit inside container

**V0.6 Screen Reader Testing Changelog:**

    *Tested with Google Chrome Screen Reader Extension
        *Added periods between acronym letters.
        *Added tabindex=0 to all elements
        **Passed - All Appropriate Elements Read**
    *Tested with Windows Screen Reader
        **Passed**
    *Changed unnessecary </img> at the end of #benefit-cost img and replaced with />
    *Removed comma in first sentence of Online Reputation Management 
    **Need to Run Website through WAVE Web Accessibility Evaluation Tool once it is Live**

**0.7 Full Testing and Clean-up (Alpha)**

    *Removed commented-out CSS (Can be found in oldcss.md)
    *Added Comments to CSS sections as needed
    *Removed Clear Functions from CSS.
    *Moved Media Queries into Proper sections in CSS
    *Broke all image links to make sure alt text was showing up correctly

**0.8 Check against Employer Requirements (Beta)**
	    *Acessibility Standards+
	    *Semantic HTML Elements+
	    *Elements Follow Logical Structure+
	    *Accessible alt Attributes+
	    *Heading Attributes in sequential order+
	    *Concise, Descriptive Titles+
	    *Links Funtion+
	    *CSS Selectors and Properties Consolidated and Organized+
	    *CSS File Properly Commented+
	    *Descriptive Commit Messages+
	    *README.md includes description, screenshot, and link to deployed application
        *Changed hero height to 100em

**0.9 (Reserved)**
    If Microsoft can skip 9, I can too.

**1.0 Initial Release**
