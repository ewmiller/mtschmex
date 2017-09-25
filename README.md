# MtSchmex
The only cryptocurrency exchange where you can trade all your bitcoins for schmeckles!

---
## About
MtSchmex is a Node JS application I'm making for fun and practice (it's a Rick and Morty cryptocurrency exchange). As I develop it further I'll talk about the technologies I'm using and interesting things I've learned along the way.

## Tech Stack

### Front End
So far the front end is built using the Materialize CSS framework with a little extra jQuery for fun animations and effects. I haven't felt the need (yet) to incorporate a full-fledged javascript framework - for now I'm just going the old school way. I use the EJS view templating language so that it looks and feels like writing regular HTML (as opposed to something like Pug which has its own simplified syntax).

I've really enjoyed using Materialize so far. It's comparable to Bootstrap in that it's a responsive grid framework, but it plays really well and looks super nice right out of the box. The components and icons and color schemes all look great together, and they make creating a visually pleasing page very simple. 

Before making this site I must admit I had very little experience with jQuery by itself. Every training course or college class I took regarding web programming forced us to use that particular teacher's favorite javascript framework - so I've seen Angular 1, Angular 2, and React, but I never went in-depth with any of them and I never had the foundation of plain ol' jQuery to begin with. Turns out it's super easy!


### Server Side
As of now the server side is incredibly simple. I plan to flesh it out into a full-fledged web application with persistent data, user accounts, etc, so by then I'll have more to write. For now it's just a standard Express application, generated with the Express CLI, using the EJS templating language as I mentioned above.