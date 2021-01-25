# Day 1
__01/18/21__

## Component Architecture

Component based architecture simply takes the single responsibility concept to the next level. It does this by encapsulating every single element, method, and component by functionality. The DOM is essentially sectioned off into components, then each of these components is given its own file that houses all of the html, css, and js needed for that particular component. (It's still somewhat within the mvc pattern so of course there are modular methods used between files) The best thing is that they are reusable and can be more or less just invoked wherever.

## Why the component

Components are convenient because when the data that they pull from is changed, only that one piece of the page needs to update, instead of an entire refresh. This saves on network requests and makes our websites more user friendly/responsive. Since they can be entirely modular, they can save you a lot of time in the long run, instead of having to write it out each time you need to draw a particular card, you call the component, give it the props it needs, and watch it populate the DOM.

## Why not component

Overall I have a very high opinion of component-based-architectures (exclusively Vue) because they streamline front end development. Where before I would strugle with what to draw to the DOM, now I'm working with multiple pages that have unique content that is generated based on a changing database. However, it does have it's drawbacks. Instead of the very straightforward controller->service->model, things become a bit more convoluted. Because you still have your services and models, but instead of controllers you have a network of pages and components that each have unique relationships, and the only way to figure out most of those relationships will be through hoping that whoever wrote it used a logical naming convention. In general reading component based architecture can be difficult. It's also an extremely robust and intricate framework, that quite frankly probably isn't necessary for anything we would write in this class, but it will save me TEE and headaches and I think I love VUE.

## Afternoon Challenge

https://github.com/Chase16Rogers/vue-playground