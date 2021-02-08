# Day 4
__02/04/21__

## What are the three main types of testing we can accomplish in vue? What does each method provide?

Unit testing - The smallest measure of testing, it tests an individual unit of code, like a function. Provides security to developers, they know that what they wrote won't break the existing code/what they wrote is functional in good ways.

Component testing - Components are tested as they are mounted to the DOM, it is important what is showed upon which conditions being met.

End to End - Tests the entire application from start to finish, in that it gives the application certain inputs, and reads the expected outputs. Provides security in knowing what users are able to do to/with your application (preventing malicious/stupid people)

## What testing method do you think is the most useful? Why?

End to end testing seems the most useful. It covers the essentials, does your application do what it is supposed to do and can it be broken by malicious users, while the other methods can be useful, this is the most encompassing while still giveing the developer room to figure out their own solutions to problems.

## What testing method do you think is the least useful? Why?

Component testing, while front end development can be tricky, the nice thing about it is how easily visible it is. If something is showing up on screen when it is not wanted/not showing up the developer is able to observe these changes or lack thereof. 