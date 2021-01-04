# Day 1
__12/14/20__

## The export solution

Before export, the only way to link multiple js documents was to carefully line them up on the html file, this would force each one to load everytime the page was refreshed, or the code ran. By using exports you reference specific pages which reduces the number of pages that have to be run. It also makes it less convoluted in figuring out which page needs to be loaded when in relation to how it affects other pages.

## Export Default Export

Export exports a single binding. An instance of a class, a single funtion, etc... This is useful for items that only need to be created once, as in our service page, as we only ever need/reuse a single instance of the service class. Export Default is similar in that it exports a "single" complex object. This is good when multiple unique instances of the Export are necessary, it allows you to reference a "vague" template like object for each instance it is necessary. We use this in the case of our models, we can just say new Model() and it goes straight to the exact class we need without any further fluff.

## Modular benefits

The modular system is convenient for many reasons. First and foremost is in reference to single responsiblity. Each js page has a unique purpose, whatever it's task is that's all it controls. This makes the pages shorter, so in order to debug you wouldn't have to scroll through potentially hundreds of lines, one is immediately able to know, this does that so it is on this page. 