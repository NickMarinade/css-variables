# Css-Variable

This site was build as a study project with JavaScript30.

## 0. Setup

> * What files do you need to create? 
- Need to create all separate files like `index.html`, `style.css`, `img`, `handler` & `listeners`.
> * What are you putting in each file? 
- In `index.html` I build a skeleton of the app with <labels> & <inputs> connecting it with my `script` and `style` files.
- In `style.css` will place my app to the center with image .
- In `handlers` i will put `handlerRemove.js` & `handlerSound.js`
- In `listeners` will put `listenerRemove.js` & `listenerSound.js`  

## 1. User Story: As a user I want to press key and hear different sounds.

> * Which user story makes sense to code first?
- Create keydown function to activate `audio` sound of each key user presses.
> * Which files of code do you need to change?
- `handlers` - `handlerSound.js` and `listeners` - `listenerSound.js`.
> * What are you changing in them?
- In `handlers`-`handlerSound.js` will return `audio` sound of each key user will press. 
- In `listeners`-`listenerSound.js` will trigger the handlers data on `keydown`.

## 2. User Story: As a user I want that ones button is released the sound stops.
> * Which user story makes sense to code first?
- Ones button is released the sound stops.
> * Which files of code do you need to change?
- `handlers` - `handlerRemove.js` and `listeners` - `listenerRemove.js` will end the sound. 
> * What are you changing in them?
- In `handlers` - `handlerRemove.js` will remove sound transition on the key release. 
- In `listeners` - `listenerRemove.js` will trigger the handlers data on `transitionend`.