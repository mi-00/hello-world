# hello-world
my first repository

##Documenting the 2 websites and making it easy for people to contribute

Events website - http://events.codeweek.eu: **EVENTS** & **AMBASSADORS**  
[GitHub Repo]: (https://github.com/codeeu/coding-events)   

Static website - http://codeweek.eu: HOME, RESOURCES, ABOUT  
[GitHub Repo]: (https://github.com/codeeu/codeeu.github.io)  

[Blog] - (http://blog.codeweek.eu): NEWS  
Tumblr with a custom theme (HTML & CSS).  
==================================================================



[STATIC WEBSITE:] (http://codeweek.eu/) GitHub directory content:

1. **_design_assets**: contains logo .pxm files;
2. **_includes/nav.ext**: main navigation on default layout (eg. on landing page);
3. **_layouts**  
    /**country.html**: included in codeweek.eu/learn/%chosen_country_name%, “Note: This is an archive of main #codeEU events, which took place during the first Code Week from November 25 to 30, 2013. To add and view new events, please visit the new events website.”;  
    /**default.html**: included in all pages, contains #header (includes nav.ext) and #footer, page content is /index.html, included as {{content}};  
    /**header.html**: included in codeweek.eu/learn/%chosen_country_name%, “10th - 18th October • #codeEU“ + {% include nav.ext %};  
    /**page.html**: used on **RESOURCES**, **ABOUT** and **NEWS** pages; contains <section id="page-title"> and <section id="content"> page {{content}};  
    /**post.html**: a modified version used on **NEWS** _(blog)_ page;  
    /**resource.html**: a modified version used on **RESOURCES** page;  
4. **_posts**: old posts, most recent one from 10.02.2014;
5. **about/index.html**: the **ABOUT** page;
6. **beambassador/index.html**: requirements to become an ambassador. There are no links to this page on the website;
7. **code/index.html**: this page is online but the link in the nav.ext is commented out. There is no link to this page on the website;
8. **codeweek4all/index.html**: presenting the _CodeWeek4All_ challenge;
9. **events/index.html**: archive page of 1st code week 2013;
10. **learn**
/**country_name%/index.html**: archive pages from code week 2013;
/**index.html**: archive of the code week 2013 event page;
11. **map/index.html**: Map of initiatives 2013, archive page
12. **news/index.html**: archive of 2013 event;
13. **odetocode/index.html**: page of the 2015 coding event;
14. **privacy/index.html**: found in page footer, explains the way in which the website uses, maintains, discloses info collected from its users;
15. **resources**
    /**%country_name%/index.html**: found on RESOURCES under “Local resources in your language”;
    /**index.html**: main page of RESOURCES;
16. **sorry/index.html**: “page under maintenance” message;
17. **stylesheets/**…: website styling;
18. **video-contest/index.html**: CodeWeekEU-2015 Video Contest page;
19. **index.html**: landing page content
20. **search.html**: search function, found on page header
21. **404.html**: “page not found” styling
22. **README.md**: update with info from this list





