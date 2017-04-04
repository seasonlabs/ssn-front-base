# Component Partials

Consider a component anything that should have the same styling definition regardless of their location between the website, and is made up of several elements.

Take as an example a news item element. You could do something like:

File                  | Purpose
--------------------- | ---------------------------------------------
`_news--promoted.scss`| Specific news promoted display styling
`_news--teaser.scss`  | Specific news teaser display styling
`_news--detail.scss`  | Specific news detail page styling

