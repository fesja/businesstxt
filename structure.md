Structure of a business.txt file
=================================

A business.txt is just a list of keys and values written in a very human friendly way.

Fields
------

**Name**

Name of the business.

```
Name: RJ Grunts
```

**Categories**

Categories of the business. There isn't yet a list of categories. The business owner decides. 

```
Categories: American Restaurant, Bar
```

**Location**

Location of the business.

```
Street: 2056 North Lincoln Park W (at Dickens Ave.)
Zip: 60614
City: Chicago
State: Illinois
Country: United States
Coordinates: 41.92012, -87.63645
```

Outside the US you may use "Postal Code:" instead of "Zip:"

You can read about [having several locations](#several-locations).

**Phone**

Phone of the business

```
Phone: (1) 773-929-5363
```

**Fax**

Fax of the business

```
Fax: (1) 773-929-5364
```

**Email**

Email of the business

```
Email: info@example.com
```

**Prices**

What's the price range of the business. There are 4 ranges:

* $: Cheap
* $$: Normal
* $$$: Expensive
* $$$$: Luxury

This is mostly used by restaurants, bars and accommodation. Business owners should be honest because depending on the price category they will be targeting different user profiles.

```
Price range: $$
```

Businesses can add specific information about their prices. There is no limit on the length.

```
Price description: $9.95 burger, $11.95 salad and soup bar. You can eat for $10-20.
```

**Menu**

Link to see the menu of the restaurant

```
Menu: http://www.leye.com/files/Menus/Grunts%20Menu.pdf
```

**Opening hours**

What are the opening hours of the business. Let's see several examples.

* If it opens everyday from 10 in the morning to 6 in the evening:

	```
	Open: Mon-Sun 10am-6pm
	```

* If it opens on different hours each day:

	```
	Open: Mon-Fri 11.30am-12am, Sat 10am-12am, Sun 10am-9pm
	```

The hours can also be written in a 24 hour time format. For example, the last example would be:

```
Open: Mon-Fri 11.30-0, Sat 10-0, Sun 10-21
```

You can read about [day abbreviations](#day-abbreviations).


**Kitchen hours**

The kitchen hours may be different from the opening hours.

```
Kitchen hours: Mon-Sun 12am-3pm 6pm-9pm
```

The hours can also be written in a 24 hour time format. For example, the example would be:

```
Kitchen hours: Mon-Sun 12-15 18-21
```

You can read about [day abbreviations](#day-abbreviations).

**Closed**

Which days the business is closed. Let's see several examples.

* If it closes some specific days:

	```
	Closed: Jan 1st, Jul 4th, Dec 24th 25th 31st
	```

* If it also closes in a range of days (vacations for example):

	```
	Closed: Jan 1st, Jul 4th 15th-25th, Dec 24th 25th 31st
	```

You can read about [month abbreviations](#month-abbreviations).


**Reservations**

If the local businesses takes reservations.

```
Reservations: Yes
```

**Payment**

Which types of payments are accepted separated by commas. It's very flexible. Some of the options yoy may consider: Cash`, `Credit Card`, `Visa`, `Mastercard`, `Amex`

```
Payment: Cash, Visa, Mastercard
```

**Short description**

A short description of the business with less than 200 characters.

```
Short description: Great place to have a great burger and a salad bar. It's near Lincoln Park & Zoo.
```

**Photos**

There can be several links to photos. These photos can be used without any kind of restriction.

```
Photo: http://s3.amazonaws.com/foodspotting-ec2/reviews/726216/thumb_600.jpg?1311709901?1345984786
Photo: http://s3.amazonaws.com/foodspotting-ec2/reviews/1315305/thumb_600.jpg?1328929303?1345984802
Photo: http://s3.amazonaws.com/foodspotting-ec2/reviews/611768/thumb_600.jpg?1307222927?1345984826
```

**Website**

Business website

```
Website: http://www.rjgruntschicago.com/
```

**The business in other websites**

This is a flexible section. The business owner can add a line for each provider on which the website is in. So for example, the business can be in twitter, facebook, foursquare and yelp:

```
Twitter: @RJGruntsChicago
Facebook: http://www.facebook.com/rjgrunts
Foursquare: https://foursquare.com/v/rj-grunts/42153000f964a5208c1f1fe3
Yelp: http://www.yelp.com/biz/rj-grunts-chicago
```

Internationalization
--------------------

There should be a way for businesses to add some fields in other languages. The following fields support internationalization:

* Name
* Price description
* Short description

An example:

```
Name: The Prado Museum
[ES] Name: El museo del Prado
[FR] Name: Le musée du Prado

Short description: The Prado Museum is the main Spanish national art museum, located in central Madrid.
[ES] Short description: El Museo del Prado es el principal museo de arte español, que se encuentra en el centro de Madrid.
[FR] Short description: Le musée du Prado est le principal musée d'art national espagnol, situé dans le centre de Madrid.
```

Several locations
-----------------

Business.txt supports also the option to have several spots on the same business.txt file. You can have different data for each spot.

* Start with the common data
* Add a location block for each spot starting with the `Street` field adding any extra field of the business.txt standard. You can override any field of the common data. So for example, you can have a common schedule in all spots except in one that it's different.

```
Name: Starbucks
Categories: Coffee
Website: http://www.starbucks.com/
Price: $$
Open: Mon-Fri 7am-8pm, Sat-Sun 8am-7pm

Street: Frnt A, 291 Broadway
Zip: 10007
City: New York
State: New York
Country: United States
Coordinates: 40.7147, -74.0060

Street: 241, Canal St
Zip: 10013
City: New York
State: New York
Country: United States
Coordinates: 40.7182, -74.0001

Street: 725 5th Ave # 2
Zip: 10022
City: New York
State: New York
Country: United States
Coordinates: 40.76245, -73.97419
Open: Mon-Fri 7am-8pm, Sat-Sun 8am-9pm
```

Day abbreviations
-----------------

* _Mon_ – Monday
* _Tues_ – Tuesday
* _Weds_ – Wednesday
* _Thurs_ – Thursday
* _Fri_ – Friday
* _Sat_ – Saturday
* _Sun_ – Sunday


Months abbreviations
--------------------

* _Jan_ – January
* _Feb_ – February
* _Mar_ – March
* _Apr_ – April
* _May_ – May
* _Jun_ – June
* _Jul_ – July
* _Aug_ – August
* _Sep_ – September
* _Oct_ – October
* _Nov_ – November
* _Dec_ – December


