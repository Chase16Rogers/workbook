# Day 3
__12/09/20__

## console.log("Writing to consoles")

The way I primarily write to the console is console.log(). This is insanely useful to determine if things are running how I want. Did this variable come out to be what I expected? Did this if statement actually run the right code on true and false? There are so many points in code, that we just don't see, so it's very nice having a non-intrusive way of visualizing code.
Another way to write to the console is console.error(""). While very similar to console.log("") I feel like the use case for this is much more specific, and much less useful. In terms of me writing it, at this stage, into my code.
Finally you could just write the code directly onto the command line. While very temporary, it could be good for testing out ideas that could be harmful to the functioning of other code, calling functions to make sure they actually work, and seeing how snippets of code could affect your website.

## Elemental my dear Watson

The elements tab shows a breakdown of the HTML page and all the styling that goes along with it. This is a particularly useful tool because of the nightmare that goes by the name of "design." The number of times I have made a change to styling and actually had it do what I want are few and far between. The elements tab gives a break down of every single visual component, where that code is coming from, and what makes it look like it looks. The pointer mode lets you quickly determine where something on screen is in the code. The styles bar on the right gives a play by play of what style is being applied to a particular element, it has a beautiful little diagram that describes the exact size of the element, its padding and margins, and it even allows you to add and adjust the styling to get the exact look you're going for. This all allows you to debug where a visual you don't want is coming from, and how changes to the style sheet will fix that particular bug.

## debugger

In JS the debugger keyword is a beautiful yet cruel mistress. Beutiful in that it gives a LINE BY LINE breakdown of what is currently happening in the code. It tells you the exact value of every binding at that exact moment, and can show you exactly where and why things go wrong. You can go back and forth as you please and is overall insanely useful. It is a cruel mistress in that once I managed to use it so poorly that it did absolutely nothing, not only did it do nothing but I also missplaced it and for the life of me couldn't find it. So everytime I wanted to run my code I had to play through a little snippet, which was very much annoying. 