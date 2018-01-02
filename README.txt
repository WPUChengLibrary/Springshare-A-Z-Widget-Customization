LibGuides/SpringShare A-Z List widget customization

Updated 1/2/2018
Please report any bugs to Tony Joachim (joachima1@wpunj.edu)

In an effort to more seamlessly use the SpringShare (LibGuides, LibCal, etc.) widgets on our dotCMS site, Hao Zeng (hao.zeng@yu.edu) and I worked on the functionality and styling of the A-Z widget to fit the look of the University pages.

Using Javascript widget embedding, changes have been implemented using CSS and Javascript/JQuery, to achieve the desired affect.

Robust sitewide stylesheets required that we reference individual objects (tags, classes, and IDs) carefully, so as not to inadvertently affect other page content.  Please be careful of this when creating new styles for your own pages.  The code presented here is specific to the William Paterson Universty, David & Lorraine Cheng Library website.  Styles and style designators may vary, depending on the structure of your site/page.  Additional changes may be necessary.

All widget content can be found in your LibGuides administrative login.  In order to use the Subject dropdown, you must first have assigned Subject categories to individual databases (see html file for more details).  Be sure to replace the site_id=915 reference with your institution's site ID.

All CSS and scripting can eb found in the A-Zwidget.html file.