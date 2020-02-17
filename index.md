<html>

<head>
<meta name="Keywords" content="CIW, HTML5, uCorp"/>
<meta name="Description" content="Simple XHTML page for uCorp site"/>
<meta charset="utf-8"/>
<link rel="stylesheet"  type="text/css" href="index.css"/>
<title>Welcome to uCorp</title>
</head>
<body>

<div class="sidebar-overlay"></div>

<!-- Material sidebar -->
<aside id="sidebar" class="sidebar sidebar-default open" role="navigation">
    <!-- Sidebar header -->
    <div class="sidebar-header header-cover" style="background-image: url(http://2.bp.blogspot.com/-2RewSLZUzRg/U-9o6SD4M6I/AAAAAAAADIE/voax99AbRx0/s1600/14%2B-%2B1%2B%281%29.jpg);">
        <!-- Top bar -->
        <div class="top-bar"></div>
        <!-- Sidebar toggle button -->
        <button type="button" class="sidebar-toggle">
            <i class="icon-material-sidebar-arrow"></i>
        </button>
        <!-- Sidebar brand image -->
        <div class="sidebar-image">
            <img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/53474/atom_profile_01.jpg">
        </div>
        <!-- Sidebar brand name -->
        <a data-toggle="dropdown" class="sidebar-brand" href="#settings-dropdown">
            john.doe@gmail.com
            <b class="caret"></b>
        </a>
    </div>

    <!-- Sidebar navigation -->
    <ul class="nav sidebar-nav">
        <li class="dropdown">
            <ul id="settings-dropdown" class="dropdown-menu">
                <li>
                    <a href="#" tabindex="-1">
                        Profile
                    </a>
                </li>
                <li>
                    <a href="#" tabindex="-1">
                        Settings
                    </a>
                </li>
                <li>
                    <a href="#" tabindex="-1">
                        Help
                    </a>
                </li>
                <li>
                    <a href="#" tabindex="-1">
                        Exit
                    </a>
                </li>
            </ul>
        </li>
        <li>
            <a href="#">
                <i class="sidebar-icon md-inbox"></i>
                Inbox
            </a>
        </li>
        <li>
            <a href="#">
                <i class="sidebar-icon md-star"></i>
                Starred
            </a>
        </li>
        <li>
            <a href="#">
                <i class="sidebar-icon md-send"></i>
                Sent Mail
            </a>
        </li>
        <li>
            <a href="#">
                <i class="sidebar-icon md-drafts"></i>
                Drafts
            </a>
        </li>
        <li class="divider"></li>
        <li class="dropdown">
            <a class="ripple-effect dropdown-toggle" href="#" data-toggle="dropdown">
                All Mail
                <b class="caret"></b>
            </a>
            <ul class="dropdown-menu">
                <li>
                    <a href="#" tabindex="-1">
                        Social
                        <span class="sidebar-badge">12</span>
                    </a>
                </li>
                <li>
                    <a href="#" tabindex="-1">
                        Promo
                        <span class="sidebar-badge">0</span>
                    </a>
                </li>
            </ul>
        </li>
        <li>
            <a href="#">
                Trash
                <span class="sidebar-badge">3</span>
            </a>
        </li>
        <li>
            <a href="#">
                Spam
                <span class="sidebar-badge">456</span>
            </a>
        </li>
        <li>
            <a href="#">
                Follow Up
                <span class="sidebar-badge badge-circle">i</span>
            </a>
        </li>
    </ul>
    <!-- Sidebar divider -->
    <!-- <div class="sidebar-divider"></div> -->
    
    <!-- Sidebar text -->
    <!--  <div class="sidebar-text">Text</div> -->
</aside>

<div class="wrapper">
    <!-- Sidebar Constructor -->
    <div class="constructor">
        <h2 class="headline">Material Sidebar (Profile menu)</h2>
        <p class="subhead">Based on <a href="https://www.google.com/design/spec/material-design/introduction.html" target="_blank">Material Design by Google</a>.</p>
        <p>Icons from <a href="http://zavoloklom.github.io/material-design-iconic-font" target="_blank">Material Design Iconic Font</a></p>
        <p>Tested on Win8.1 with browsers: Chrome 37,  Firefox 32, Opera 25, IE 11, Safari 5.1.7</p>
        <hr />
        <p>You can use this sidebar in Bootstrap (v3) projects. HTML-markup like <a href="http://getbootstrap.com/components/#navbar" target="_blank">Navbar bootstrap component</a> will make your work easier.</p>
        <p>Dropdown menu and sidebar toggle button works with JQuery and Bootstrap.min.js</p>
        <hr />
        <h2 class="headline">Sidebar Constructor</h2>
        <p>
            <label for="sidebar-position">Sidebar postion</label>
            <select id="sidebar-position" name="sidebar-position">
                <option value="">Default</option>
                <option value="sidebar-fixed-left">Float on left</option>
                <option value="sidebar-fixed-right">Float on right</option>
                <option value="sidebar-stacked">Stacked on left</option>
            </select>
        </p>
        <p>
            <label for="sidebar-theme">Sidebar theme</label>
            <select id="sidebar-theme" name="sidebar-theme">
                <option value="sidebar-default">Default</option>
                <option value="sidebar-inverse">Inverse</option>
                <option value="sidebar-colored">Colored</option>
                <option value="sidebar-colored-inverse">Colored-Inverse</option>
            </select>
        </p>
        <p>
            <label for="sidebar-header">Sidebar header cover</label>
            <select id="sidebar-header" name="sidebar-header">
                <option value="header-cover">Image cover</option>
                <option value="">Color cover</option>
            </select>
        </p>
        <p><button class="sidebar-toggle">Toggle sidebar</button></p>
    </div>
</div>
<!-- HEADER -->
<header>

<div id="head"><a href="index.html"><img height="65" width="250" src="aboutus/uCorp_logo.png" /></a></div>

<div id="navbar"><a href="aboutus.html"><img height="52" width="89" src="aboutus/header_button_about-us.jpg" alt="Link goes back to current page." id="aboutus" /></a><a href="contactus.html"><img height="52" width="104" src="aboutus/header_button_contact-us.jpg" alt="Click here to contact us and let us know what you think." id="contactus" /></a><img height="52" width="91" src="aboutus/header_button_products.jpg" alt="Click here to explore the catalog of products we offer." id="products" /><a href="manufacturing.html"><img height="52" width="204" src="aboutus/header_button_manufacturing-process.jpg" alt="Click here to learn about the high-quality manufacturing process that uCorp employs." id="manufacturingprocess" /></a><a href="technology.html"><img height="52" width="112" src="aboutus/header_button_technology.jpg" alt="Click here to discover the advanced technology that goes into each one of our speakers." id="technology"/></a></div>

</header>

<!--PAGE NAVIGATION -->
<nav>
<a href="aboutus.html"><img height="50" width="163" src="aboutus/nav_button_about-us_team.png" alt="Click here to read about the philosophy of our company." id="subnav_aboutus" /></a>
<br />
<a href="aboutus_the-team.html"><img height="50" width="163" src="aboutus/nav_button_the-team_team.jpg" alt="Click here to read about the people that make our mission possible." id="subnav_theteam" /></a>
<div id="catalog">
<img src="aboutus/catalog.jpg" alt="Click to download a PDF containing our full product catalog." />
<a href="aboutus/catalog.pdf">Product Catalog</a>
</div>
</nav>

<!-- ARTICLE -->

<article>

<h2>Our Creative Team</h2>

<p>Why are our products so popular? Because the men and women of uCorp work tirelessly to produce nothing but the best.</p>

<table class="center" border="1">
<caption>
<strong>The Men and Women who Keep uCorp Running</strong>
</caption>
  <tr bgcolor = "#6699ff" >
    <th>Name</th>
    <th>Job Title</th>
    <th>Email Address</th>
  </tr>
<tr>
<td class="center">Jane Doe</td>
<td class="center">CEO & Founder</td>
<td class="center">jane@ucorp.com</td>
</tr>
<tr>
<td class="center">Mike Ross</td>
<td class="center">Co-founder/Projects</td>
<td class="center">mike@ucorp.com</td>
</tr>
<tr>
<td class="center">Heather H</td>
<td class="center">Designer</td>
<td class="center">Heather@ucorp.com</td>
</tr>
<tr>
<td class="center">Peter John</td>
<td class="center">Web Developer</td>
<td class="center">peter@ucorp.com</td>
</tr>
<tr>
<td class="center">Frank Martin</td>
<td class="center">Co-founder/Operations</td>
<td class="center">Frank@ucorp.com</td>
</tr>
<tr>
<td class="center">Christopher Di</td>
<td class="center">Co-founder/Projects</td>
<td class="center">Christopher@ucorp.com</td>
</tr>
<tr>
<td class="center">Cherry John</td>
<td class="center">Fullstack Developer</td>
<td class="center">Cherry@ucorp.com</td>
</tr>
<tr>
<td class="center">Nancy Doe</td>
<td class="center">Team Lead</td>
<td class="center">Nancy@ucorp.com</td>
</tr><tr>
<td class="center">Steall John</td>
<td class="center">Account Manager</td>
<td class="center">Stella@ucorp.com</td>
</tr>
</table>


</article>


<!-- FOOTER -->
<footer>

<div id="address">
<h4>uCorp</h4>
Sunshine House, Sunville. SUN12
<br />
019223 8092344
<br/>
info@ucorp.com
</div>

<div id="follow">
<h4>Follow Us</h4>
<a href="https://twitter.com/uCorp4">Twitter</a> | <a href="https://www.facebook.com/UCorp-441272686298550/">Facebook</a> | <a href="https://www.linkedin.com/company/ucorporation/">LinkedIn</a> | <a href="https://www.instagram.com/ucorp123/">Instagram</a>
<img src="aboutus/footer_newsletter.jpg"  alt="Enter your email here to subscribe to our newsletter." />
</div>

<div id="footerlinks">
<br />
Copyright &copy All rights reserved by uCorp. <a href="terms.html">Terms</a> | <a href="privacy.html">Privacy</a> | <a href="contactus.html">Contact Us<a?
</div>

</footer>

</body>

</html>
