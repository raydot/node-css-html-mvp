# node-css-html-mvp
The goal is to get a node server working that can compile HTML and CSS and auto-refresh a browser.  

Attempt 1: browser-sync.  
This actually works!  Trick was finding the right start command:
`npx browser-sync start --server --files "css/*.css"`

Run that from `root`, with `index.html` at `root` and css files in `root/css`.
