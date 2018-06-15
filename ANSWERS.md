# Answers
1. The HTML order doesn't really matter, it's going to come down to your stylesheets and whichever class you list
last in you css stylesheets.

2. Basically 'display: block;' means it will display like a column, 'display: inline;' means it will display like
a row.

3. You're using the cross-axis.

4. A fixed site would be like the 'Good Idea' website we built the first day with set heights and weights using pixels. Adaptive would be like yesterdays site which used adaptive type of units like vh and vw, and uses media queries to 'adapt' based on certain conditions. Fluid sites are full-screen and are like an upgraded version of Adaptive, usually using percentage based units, 'no restraints' though. Finally, Responsive use all of the tricks to adjust all elements of the site based on certain break points, great user experience and also most expensive to make, mix of fixed and fluid.

5. Because sites are vertical in nature, not setting a max-width property will cause the width to go on forever, which is not in anyone's interest.


# Questions

1. If you saw this HTML: `<div class="box box1 box2 box3"></div>` which class has the most specificity weight?
2. Describe the difference between `display: block;` and `display: inline;`.
3. While using flexbox, what axis are you using when you use the property: `align-items: center`?
4. What is the difference between fixed layout, adaptive layout, fluid layout, and responsive layout?
5. Why do we need to use the CSS property max-width on the outer most container in a responsive website?
