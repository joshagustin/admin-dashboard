# admin-dashboard
An odin final project for Intermediate HTML and CSS. This project utilizes CSS Grid concepts.

TODO
- make sure to use css variables
- use self-hosted fonts
- make web-responsive

tidbits i learned / roadblocks
- i was really puzzled on why chrome devtools was showing a different actual track size compared to my specified track size. it appears to be a bug on chrome's end as the actual track size they show is **actual track size / 2**. To see the actual size, I had to rely on the computed layout.
- grid blowout; divs in card-container do not fit. i expect them to grow the size of the parent but they just result in a grid blowout
- parent's container must be display: grid too to avoid a grid blowout in the child elements
- border-radius of a parent can be hidden behind children
- setting a height on a container element causes children to shrink to minheight, if necessary, in minmax

this led me on a tangent for hours ...
<!-- TODO -->
- try setting an explicit height on announcement and trending
<!-- * -->
- if i dont want a grid parent to grow to accommodate its children, set minmax(0, {whatever})
!!!! use flexbox for grid containers within another container 
jk im still lost
<!-- ! problem -->
i want the announcements and trending sections to be smaller.
setting height: 300px on trending seems to do the trick ???? (not really)
<!-- * solved -->
final answer: setting heights on topic-container and notice-container did the trick as well as using flexbox on the individual topics and notices to get them to fit how i wanted to.
<!-- * DONE -->

- 