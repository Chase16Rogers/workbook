# Day 2
__01/12/21__

## The relationships between data

1:1 - A single parent needs information from a single child. Child holds parent's ID, and that is used to connect them.

1:N - One to Many - A single parent needs information from multiple children. A consistent ID is kept between the children that the parent can call, recieving all of the data from each child.

N:M - Many to Many - A complicated web where multiple parents can have relationships with multiple children, ususally crossing over. Like sharing categories.

## Linking > Embedding

Embedding has a couple of problems, first if there is high traffic the object could become too large to be handled by the server. By linking, you are able to specify which data you are trying to access without haveing to pull all the other information that is probably unnecessary. Linking also allows modularity, by giving the data its own binding, it could also be used in other places, if the situation calls for it.

## Many to Many Considerations

Ultimately the amount of data, and how they interconnect is the deciding factor in how to manage a N:M database. The goal is to make it as short, simple, and easy to read as possible. Instead of making huge collections of similar things, "label" each thing instead. If the data pool is shallow, ther is no point in over engineering a complicated solution, but at the same time, an overly simple solution in a large database could be catastrophic.

## Afternoon Challenge

