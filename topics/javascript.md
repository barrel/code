# Javascript or: How I Learned to Stop Worrying and Drop jQuery

jQuery is a beautiful piece of code and is incredibly useful, especially for projects that require us to support IE9. But fortunately, it's now possible to plan for IE10+ using only plain javascript, with very little difficulty.

## Vanilla (plain) Javascript Refresher
- Globals 
  - document.body
  - document.documentElement
  - window
- Selecting elements
  - `.querySelector()`
  - `.querySelectorAll()``
    - Nodelist vs Array 
    - `Array.prototype.slice.call()`
  - `.getElementById()`
  - `.getElementsByTagName()`
- Element attributes
  - `.getAttribute()`
  - `.setAttribute()`
  - `classList`
  - style 
    - individual props vs `cssText` or attribute
    - most values need units
- Events ([jsbin](http://jsbin.com/fomuceh/edit?js,console,output))
  - `.addEventListener()` `.removeEventListener()`
  - on<event> (overrides previous handlers)
  - delegation 
- Arrays 
  - `for`, `.forEach()` ([jsbin](http://jsbin.com/nesizu/edit?js,console))
  - `.map()`, `.filter()` ([jsbin](http://jsbin.com/jaxixiq/edit?js,console))
- Math ([jsbin](https://jsbin.com/vidixob/edit?html,js,console,output))
  - `.min` `.max`
- Height/width/scrollY/offsets ([jsbin](http://jsbin.com/kiyomo/edit?js,console))
  - heights, widths
  - offset top 

## ES2015 (ECMAScript 2015, or ES6)
- Block scope
  - `let` `const` vs. `var` 
- Arrow functions ([jsbin](https://jsbin.com/nabenuj/5/edit?html,js,console,output))
  - When to use curly brackets and what it means if you don't
  - Scoping / context / this
  - Leave binding in the dust..
- Template literals 
- Object and Array De-structuring
- Default parameter values
- `import` and `export` 
- Classes
- Spread operators
  - arrays
  - objects (not yet in the spec)

## Useful Libraries
- AJAX
  - [nanoajax](https://github.com/yanatan16/nanoajax)
  - [reqwest](https://github.com/ded/reqwest)
- Events
  - [delegate](https://github.com/zenorocha/delegate)
- DOM Traversal
  - [closest](https://github.com/ForbesLindesay/closest)
