Business.txt
============

Business.txt is a file that local businesses upload to their website with their business information so all website providers can update it whenever something is changed.

**Sections**

* [How this works](#how-this-works)
* [For local businesses](#for-local-business)
* [For websites](#for-websites)
* [Why current solutions don't work?](#why-current-solutions-dont-work)
* [Examples](#examples)
* [Documentation](#documentation)
* [Next steps](#next-steps)
* [Help us make it better](#help-us-make-it-better)

**Discussions**

* [Should we use a txt file, json, microformat or hCard?](https://github.com/fesja/businesstxt/wiki/Which-format)


How this works
--------------

1. Joe owns a restaurant in San Francisco. He is going to change the schedule.

2. He has two options:

    1. Without business.txt he would have to go to all the websites like Yelp and Foursquare and update the info one by one. Even after that, there would still be thousands of websites with the incorrect schedule.

    2. With business.txt he just updates the schedule on his website, and all the websites that support business.txt will update their info accordingly.


For local businesses
--------------------

* Add a business.txt file to the root of your website with all your business info.
* Whenever you change it, it will be updated on all the websites that support the business.txt standard.
* It’s really easy to add.
* It’s free!
* [Create your business.txt file now](https://github.com/fesja/businesstxt/blob/master/structure.md).
* Any question? Read the [FAQ](https://github.com/fesja/businesstxt/blob/master/faq.md)


For websites
------------

* You will get the last updated info from the businesses.
* It’s easy to implement.
* It’s free!
* [Start supporting business.txt](https://github.com/fesja/businesstxt/blob/master/structure.md)!
* Any question? Read the [FAQ](https://github.com/fesja/businesstxt/blob/master/faq.md)


Why current solutions don't work?
-----------------------------------

There are three options that local businesses currently have to update the latest info:

1. Some local businesses go to every website to update their info. It's too time consuming and there are literally thousands of websites with their information. On many of them the information can't be edited.

2. Other local businesses pay for a service like http://www.yext.com that can cost more than $500 a year. They update the information on the main websites, but there are literally thousands of websites with their information.

3. Other local businesses may think on adding to their website some metadata (using http://schema.org/). The problem is that it's too complicated for a non-developer.

On the other side, right now websites have to convince their users or local businesses to update the latest info. It's too time consuming. And an outdated info can ruin someone experience with the website or app. 

There isn't a simple, cheap and worldwide solution to get the latest information of local businesses. There should be one! Website providers need it. Local businesses need it. Let's do it ;)


Examples
--------

```
Name: RJ Grunts
Categories: American Restaurant, Bar
Street: 2056 North Lincoln Park W (at Dickens Ave.)
Zip: 60614
City: Chicago
State: Illinois
Country: United States
Coordinates: 41.92012, -87.63645
Phone: (1) 773-929-5363
Price range: $$
Price description: $9.95 burger, $11.95 salad and soup bar. You can eat for $10-20.
Open: Mon-Fri 11.30am-12am, Sat 10am-12am, Sun 10am-9pm
Short description: Great place to have a great burger and salad bar

Website: http://www.rjgruntschicago.com/
Twitter: RJGruntsChicago
Facebook: http://www.facebook.com/rjgrunts
Foursquare: https://foursquare.com/v/rj-grunts/42153000f964a5208c1f1fe3
Google: https://plus.google.com/108935673850120788149/about?hl=en
Yelp: http://www.yelp.com/biz/rj-grunts-chicago
Urbanspoon: http://www.urbanspoon.com/r/2/15875/restaurant/Lincoln-Park/R-J-Grunts-Chicago
Foodspotting: http://www.foodspotting.com/places/186358-r-j-grunts-chicago
TouristEye: http://www.touristeye.com/RJ-Grunts-Chicago-p-2127
```

More examples:

* [Basic info](https://raw.github.com/fesja/businesstxt/master/examples/basic_info.txt)
* [Extra info](https://raw.github.com/fesja/businesstxt/master/examples/extra_info.txt)
* [Several locations](https://raw.github.com/fesja/businesstxt/master/examples/several_locations.txt)

Documentation
-------------

Learn about [all the options of a business.txt file](https://github.com/fesja/businesstxt/blob/master/structure.md).

Supporting business.txt
--------------------------------

**Local businesses**

* [Pierlis](http://pierlis.com/business.txt)

Send me an email to javier at touristeye.com

**Websites**

* [TouristEye](http://www.touristeye.com)

Send me an email to javier at touristeye.com or a pull request to add your website if you are supporting or plan to support business.txt in the near future.

Next steps
----------

1. Convince websites to join
2. Discuss and improve the standard
3. Build a website and some plugins for Wordpress and other CMSs to create a business.txt file
4. Tell local businesses to join.


Help us make it better
----------------------

Please tell us how we can make this soon-to-be standard better. If you have a specific feature request or if you found a bug, please [open a support ticket](https://github.com/fesja/businesstxt/issues). Also, feel free to fork these docs and send a pull request with improvements!
