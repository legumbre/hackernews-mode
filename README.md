# hackernews-mode

A HN page-mode for Conkeror.

## Setup
Just copy hackernews.js in your [.conkerorrc directory](http://conkeror.org/ConkerorRC)

Alternatively, add ```require("/path/to/hackernews.js")``` to your ```.conkerrorc``` file.

## Commands and default keybindings 

### Frontpage view
 - ```j, k  (hackernews-next-post, hackernews-prev-post)```: navigate posts.
 - ```h (hackernews-view-comments)```: view selected post comments
 - ```, (hackernews-vote-up-post)```: vote selected post
 
### Comments view
 - ```j, k (hackernews-next-comment, hackernews-prev-comment)```: navigate comments
 - ```J, K (hackernews-next-top-level-comment, hackernews-prev-top-level-comment)```: navigate top-level comments
 - ```C-j, C-k (hackernews-next-same-or-higher-level-comment, hackernews-prev-same-or-higher-level-comment)```: navigate same-or-higher-level comments
 - ```C-J, C-K (hackernews-next-same-author-comment, hackernews-prev-same-author-comment)```: navigate same-author comments
 - ```a (hackernews-reply)```: reply to selected comment
 - ```, (hackernews-vote-up-post)```: vote selected comment

### Misc
The page-mode also adds a link relationship attribute to the "More" link so that ```]]``` will follow the next page.
