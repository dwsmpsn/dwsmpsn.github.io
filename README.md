## Website Performance Optimization portfolio project



### Optimizations Made:

#### 1. index.html
1. All images have been resized and compressed.
2. Added media tag to print stylesheet
3. Moved analytics to bottom of HTML and added async attribute

#### 2. style.css
1. added will-change to body
2. added will-change to pizzaGenerator id and mover class
3. edited CSS to look up single IDs instead of multiple levels of class lookups

#### 3. views/pizza.html
1. no changes necessary to this html

#### 4. views/css/style.css
1. added will-change to pizzaGenerator

#### 5. views/js/main.js
1. fixed resizePizzas, referencing solution from a previous lesson
2. changed querySelector to getElementById at the suggestion of project reviewer
3. changed querySelectorAll to getElementsByClassName at the suggestion of project reviewer
4. declared phase in the for loop initialization and refactored variable so that each loop doesn't need to redo the same calculations