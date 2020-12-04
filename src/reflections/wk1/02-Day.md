# Day 2
__12/1/20__

## What I know about pseudo-classes

Essentially a pseudo-class is meant for temporary formatting when some action takes place. The biggest instance of this seems to be :hover. While the pointer icon is over an element with the pseudo-class hover, the properties defined in that particular rule are overwritten by the properties defined in the :hover rule. This is primarily useful for making buttons more obvious. If you weren't sure before, when the background color changes and the arrow becomes a little hand, it's pretty obvious you're dealing with something that can be clicked. The :link pseudo-class also seems useful as a nice touch kind of detail, and together with :hover, seems like the pseudo-classes I will be using the most going forward.

## Specifying specificity

Specificity is the way CSS knows which rule applies to which element. First it specifies which elements are targeted, whether it be through id, class, tag, attribute, etc...  Specificity then comes into play again when two or more rules are trying to change an element, like formatting a div, then formatting a span within that div. Which ever rule is more specific, targets the most aspects of a particular element, wins the struggle and is applied to that element. Tags have the lowest specificity because it targets absolutely anything that has that tag. Then class, because you have to set a particular class for each instance. Finally ID which is unique to a particular element. By keeping specificity in mind I can keep my CSS nicely formatted and I won't have to pull out my hair trying to figure out why this image won't center, when everything else centered. I've changed the margins and padding, tried text-centering (which did nothing), but the cat that does not exist, is just a little to the left. If I had payed more attention to the css, and divided my project a little better, everything could have gone much nicer.

## !important !important !important !important !important

In css specificity everything is delicately balanced, this (0 1 1) specificity is prioritized over this (0 1 0), and everything is as it should be. You can use an Id to set the specificity to (1 0 0) and that should priority format almost any element. But lets say you really need a particular property to format, no matter what. !important sets the specificity to (1 0 0 0) so that it will run come hell or high water. But, later you really really need this other property on the same element, there's no way you're overwriting 1000 with 10s and 1s, so you use another !important to get it up to speed, and another !important for good luck. Before you know it your .css is just a bunch of !important stacked ontop of eachother to balance out a different !important. Now your counting !importants to try and figure out how many your next property needs in order to get formatted. It's been recomended we not use them at all, but I think there are a few exceptions, though few and far between they may be.