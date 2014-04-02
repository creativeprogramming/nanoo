nanoo
=====

Joomla! CMS rewritten in node.js

I really like the Joomla! CMS software architecture: look at the joomla plugins, they are Event Driven, Joomla is a powerful event driven platform, with one drawback: PHP the language in which it's written is not event driven. They did magic to add this, but this magic is paid in limits and overheads (think also at the fact that node is deploy once, run always, instead Joomla redeclares all it's classes and util methods at each request, yes also if you have opcode caching on, that's big overhead, with node a CMS like Joomla will be bleezing fast!).

Let's take all the architecture of the Joomla! CMS and let's write this in node, and here it comes, the CMS of the future.

Anyone interesting in helping me with this project idea? Contact me at <stefano AT creativeprogramming DOT it>, let's make this born.
