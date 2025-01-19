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