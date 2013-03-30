---
layout: post
title: "My findings on JS MV... libs"
date: 2013-03-30 23:24
comments: true
categories: [Javascript, MVC, Frameworks]
---

**[Knockout JS](http://http://knockoutjs.com/)**
---
* Nice tutorials and documentation.
* Nice to have in the smaller project, especially when you are satisfied with something which just provides UI data bindings.
* Difficult to unit test.
* Code separations is a concern.
* If routing is required, then we need to include a new library for it.

**[Angular JS](http://angularjs.org/)**
---
* All-in-one package. Provides everything you expect from a MVC framework.
* Built and maintained by Google. ;-)
* Extends HTML and at the same time pollutes DOM!!!
* Quick development.
* Easier to unit test. It provides a unit testing API.
* Steep learning curve.
* Very little boilerplate.
* Fewer tutorials and not very good documentation.
* Becoming very popular with dev community.

**[Backbone JS](http://backbonejs.org/)**
---
* Nicely documented and very stable.
* Relatively old and extensively used.
* Lightweight and small. Therefore widely used on phone also.
* Incomplete framework.
* A lot of boilerplate.
* Clean separation of concerns.
* Strong force to follow certain pattern. Results less reusable code.
* Misses on UI bindings.

**[Ember JS](http://emberjs.com/)**
---
* Relatively new.
* Need a better documentation.
* Unique support for composed views which increases code reusability.
* Provides everything which angularjs does.
* Uses Handlebarsjs for tempting views.


**Things not covered and assumptions made in the assessment:
**

* **Performance**: It is a very subjective matter and depend a lots on the bottlenecks of your application and on the criteria you use to judge it. Backbone is quite extensively used in mobiles and tablets so shouldn't be a problem at all. Both Ember and Angular claim that they give snappy performance on phone though there is no use case to support this, at least I didn't find any.
* **Sources**: I am not at all sharing my experience here as I haven't used them myself. I just gathered all this information from various resources which I consider reliable.
