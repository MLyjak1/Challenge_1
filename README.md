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

To be Added

## Instructions for Future Developers:

To be Added

## Known Bugs:

To be Added

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
	    *Acessibility Standards
	    *Semantic HTML Elements
	    *Elements Follow Logical Structure
	    *Accessible alt Attributes
	    *Heading Attributes in sequential order
	    *Concise, Descriptive Titles
	    *Links Funtion
	    *CSS Selectors and Properties Consolidated and Organized
	    *CSS File Properly Commented
	    *Descriptive Commit Messages
	    *README.md includes description screenshot and link to deployed application
        *Changed hero height to 100em
