# Css-Variable

This site was build as great teamwork en a study project with JavaScript30.

## 0. Setup

> * What files do you need to create? 
- Need to create all separate files like `index.html`, `style.css`, `img`, `handler` & `listeners`.
> * What are you putting in each file? 
- In `index.html` I build a skeleton of the app with <labels> & <inputs> connecting it with my `script` and `style` files.
- In `style.css` will place my app to the center with image and declare variables.
- In `handlers` i will write `data.js`
- In `listeners` will write `change.js` & `mousemove.js`  

## 1. User Story: As a user I want to be able to change spacing, blur or color.

> * Which user story makes sense to code first?
- Create function to activate `change` , `mousemove` in `listeners` when you move the root variable  it would change size, bluriness and color on the page
> * Which files of code do you need to change?
- `css`, `handler`  and `listeners`- `change.js`, `mousemove.js`
> * What are you changing in them?
- In `css` have to declare variables in the root and asign then to an object.
- In in `handler` i will activate the action with `handlerUpdate` function to be updated ones you `mousemove` and `change` settings to make changes.
- In `listeners`- will trigger and update the settings ones user moves mouse and changes the setting to a new settings.