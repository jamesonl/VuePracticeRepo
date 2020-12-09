## First tutorial of Vue.js

 - The DOM (the HTML document) is reactively linked to the javascript files that I create
 - within the tutorial, the "script" section is used to code up preliminary examples, but I will eventually migrate these to independent javascript files
 - `directives` are any commands within the DOM that begin with `v-`, and correspond to anything that is included as part of the data attributes of an element
 - something that I noticed is that the use of the word `this` is pervasive throughout all javascript nomenclature
      - after [reading a post on this concept](https://codeburst.io/all-about-this-and-new-keywords-in-javascript-38039f71780c), it appears to be very similar in nature to that of a object-oriented class within Python, but typically formatted as a function

### Composing with Components

 >The component system is another important concept in Vue, because it’s an abstraction that allows us to build large-scale applications composed of small, self-contained, and often reusable components. If we think about it, almost any type of application interface can be abstracted into a tree of components.

  - It would appear, based off of this logic, that the concept of inheritance applies to components that are created through Vue.js
  - The workflow for building components was inspired by the [MVVM software architectural pattern](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93viewmodel)
  - when instantiating a Vue object, if I want an object to reflect a change in the visual interface, then I’ll need to set some initial value.

 - In the process of searching for more information on Vue.js, I discovered the [Vuetify](https://vuetifyjs.com/en/components/buttons/#usage) framework, which builds off of Vue, and adds in the Material Design Framework
    - What is interesting about this is that it convinces me that I don't ACTUALLY need to learn how to use things like javascript or Vue, and that I can simply source components from these design frameworks
    - different from analytic work, I don't to entirely make everything from scratch, and this idea extends from simple things like buttons and bobs to Single Page Applications (SPA).
