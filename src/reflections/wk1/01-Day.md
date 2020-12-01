# Day 1
__11/30/20__

## The benefits of Git

Git as a service is incredibly useful in that it allows for several benefits at the same time. First of all it creates redundancy in where the code is stored. Not only is the code maintained on the initial computer that wrote it, it is uploaded to Git's servers. This way even if your local computer stops working, the code won't be lost. Second Git allows for extremely convenient collaboration. It allows for multiple people to push and pull code. On top of that it requires a message to describe any changes that were made. This way even if someone were to upload catastrophic code to the collective, it could easily be returned to a previous save. Finally Git is reliable, free, and easy to use as a host for publishing even the most obscure or mundane projects.

## How branches could be useful

Primarily branches are useful in altering existing "live" or sensitive websites, by creating an effectively "alternate universe" you can test how changes you plan to make affect the website before potentially crashing a source of income, or ruining a database. Then once your sure your code is copacetic you can merge the branches.

At Ada County Weed, Pest, and Mosquito Abatement, I used a program to keep track of known mosquito breeding sites, and any larval findings or  pesticide applications I had made at a particular site. It wasn't particularly difficult to maneuver or understand, it had it's quirks but after messing around with it for a while it was fairly simple to navigate. The key word here being "messing." The company that developed the program included a second test website for training purposes, this allowed me to get a handle on the program without messing up any of the existing data on the actual website. Using branches to create an offshoot of the main code for this purpose is far superior to copying, pasting, and hosting an entirely seperate repository. 

## The great Git vs Github debate

In my head I liken Git to a computer, and Github to the monitor. Git is the functionality, it stores content and keeps track of changes to that content. Meanwhile Github is the method by which we can access and manage that content, all organized and easily accessible in a neatly wrapped package.