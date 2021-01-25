# Day 4
__01/21/21__

## What is a nested route?

A nested route is a means by which you attatch a children array to another route, this children array then has routes of its own. The kicker is that the routes held by the children are to pages specific to the parent. So instead of invoking a seperate route you would only need to drill into the parent route. This seems dumb. While I can maybe see this functionality being useful for keeping the router page readable and making the relationship between different pages obvious. This also takes away/complicates the modularity that using a component based architecture provides, not necessarily defeating the purpose, but I think losing sight of what it could be.

## When might you use a nested route?

Nested routes seem useful for one to many page relationships. My naive and unexperienced mind harkens it to the relationship an item would have to a category in a shop. Say you're on Amazon.com, and you really want to buy a new laptop. You go up to the searchbar and type in laptop and click on the option that says laptops in computers. Now you are looking at all of the laptops in the computers category, they might be in some other categories as well, but you could navigate computers/laptops/hp-envy. It would make sense that these are nested as the relationships will be consistent and specific.

## Can you pass parameters through a nested route? When might you use them?

To my understanding a nested rout has the same limitations as a regular route, just with some extra steps. So yes you could pass parameters through a nested route. This is insanely important for keeping track of a particular item the user may have clicked on. If you are drawing a number of items from an array, you would have to pass the id for the particular item that was clicked on, then draw the page that it routes to using that id. Otherwise each route would have to connect to a uniquely coded page, which is simply inconcievable.

## Afternoon Challenge (Partner)

https://github.com/Chase16Rogers/partner-pokedex