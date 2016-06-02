---
layout: post
title: Learning data mining with Coursera: Part 2
---

![A dual network plot of hospital ward contact]({{ site.url }}/assets/jturman_week3_network-dual.png)

The data-vis class from the U of Illinois is winding down. There were two assignments that students had to complete and grade for each other:
1. The display of numerical data (essential plot design)
2. Network visualization (pertaining to nominal data, edges, nodes, centralities, equivalency matrices, etc.)

The first assignment was boring for all the students of the class, and it may have thinned the ranks significantly due to its open-ended wording. Basically do what ever you want as long as you're visuallizing numerical data. I hadn't actually worked with visualization tools like Rstudio or Tableau. It went okay, but I had a hard time finding data that interested me. I ended up using the climate data ("hockey-stick") the whole class could access. Very boring. Overdone, like blackened toast.

The second assignment turned out much better. I still had a very hard time finding the data-set and graphical tool combination to satisfy me (on time). I eventually settled on [Gephi](http://gephi.org), an open-source tool. It works terribly on Linux, but okay on the Mac. Then I had to find a data-set that wouldn't fyr my poor MBA. Basically, I couldn't use any "big" data. I had to find some _medium_ data, whatever that would turn out to be. For a network (edge-list) plot, I figured I couldn't use anything with more than 20,000 records, or else my Mac would freeze for too long for me to actually finish the assignment on time. Not surprisingly, it was hard to find a small, yet interesting, graph of data.

