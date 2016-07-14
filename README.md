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
    /**header.html**: included in _codeweek.eu/learn/%chosen\_country\_name%_, “10th - 18th October • #codeEU“ + {% include nav.ext %};  
    /**page.html**: used on **RESOURCES**, **ABOUT** and **NEWS** pages; contains _<section id="page-title">_ and _<section id="content">_ page _{{content}}_;  
    /**post.html**: a modified version used on **NEWS** _(blog)_ page;  
    /**resource.html**: a modified version used on **RESOURCES** page;  
4. **_posts**: old posts, most recent one from 10.02.2014;
5. **about/index.html**: the **ABOUT** page;
6. **beambassador/index.html**: requirements to become an ambassador. _There are no links to this page on the website_;
7. **code/index.html**: this page is online but _the link in the nav.ext is commented out_. There are no links to this page on the website;
8. **codeweek4all/index.html**: presenting the _CodeWeek4All_ challenge;
9. **events/index.html**: archive page of 1st **_Code Week 2013_**;
10. **learn**
/**country_name%/index.html**: archive pages from **_Code Week 2013_**;
/**index.html**: archive of the **_Code Week 2013_** event page;
11. **map/index.html**: _Map of initiatives 2013_, archive page
12. **news/index.html**: archive of **_Code Week 2013_** event;
13. **odetocode/index.html**: page of **_Code Week 2015_**;
14. **privacy/index.html**: found in page footer, explains the way in which the website uses, maintains, discloses info collected from its users;
15. **resources**
    /**%country_name%/index.html**: found on **RESOURCES** under “Local resources in your language”;
    /**index.html**: main page of **RESOURCES**;
16. **sorry/index.html**: “page under maintenance” message;
17. **stylesheets/**…: website styling;
18. **video-contest/index.html**: _CodeWeekEU-2015 Video Contest_ page;
19. **index.html**: landing page content
20. **search.html**: search function, found on page header
21. **404.html**: “page not found” styling
22. **README.md**: update with info from this list





