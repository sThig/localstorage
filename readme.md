# Local Storage

Finally! I've been dying to get a tutorial for this ever since Justin showed me it a few months back on a project

#TIL

* event listener on nothing, (how to do it) by adding it to the submit event, not the button (so when they hit enter)
* Preseve log will contain events that happen quickly (like hitting enter)
* e.preventDefault(); will stop the page from preloading
* es6 shorthand property example:     const text = (this.querySelector('[name=item]')).value;
    text,  (mind blown)
* you can .push something from a function into an array, neat
* console.table(items) to see your array in the console.log
* mapping over an array is "plates.map((plate, i) =>"
* also you can pass in an array in an argument so when it loops over it won't break your js
* map will take in raw data and return some other data
* .join('') takes everything in an array and turns it into one big string
* ternary operator... I kinda get it now.  So this is where you want to make a check box checked or not through es6 (I probably f'd that up pretty bad, but I think I got it in my head, basically it's this "${plate.done ? 'checked' : ''}"  I don't get the done part, yet.
* learned what localStorage.setItem does (we touched on getItem and removeItem, too)
* I realize that JS is like a spoken language and once you start to learn a few principles, the rest is just part of the collective of words (like ES6 could be considered contractions in English)
* JSON.stringify - I saw justin use this once and I was just confused as hell. Not as much anymore.
* JSON.parse, kinda understood this... looks like it converts it to something readable by a human? ex:   const items = JSON.parse(localStorage.getItem('items')) || [];
* watching Wes's videos with CC enabled is mighty helpful
* you can .target an event console.log(e.target);
* also learned some shortcuts for gitHub
# localstorage
