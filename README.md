# DokuWiki tree beautiful view
Making DokuWiki **site map** and **sidebar navigation trees** beautiful. Just copy the contents of any of those CSS [files](#files) - from here to your DokuWiki`/conf/userstyle.css`

Aaand... Poof!

![DokuWiki Site Map with this CSS](https://github.com/chang-zhao/dokuwiki-tree/blob/master/dw-tree-css.png)

All this is done with CSS borders and pseudo-elements, 100% virus-free. ;)

![CSS explanation](https://github.com/chang-zhao/dokuwiki-tree/blob/master/dw-tree-css-annot.png)

# Files:

 * **dw-tree.css** - for styling the main site map only (parent container *`#index__tree`*). Thus, `?do=index` would be styled, but not other index trees.
 * **simplenavi.css** - the same kind of styling, applied only to the tree of [SimpleNavi plugin](https://www.dokuwiki.org/plugin:simplenavi) (parent container *`.plugin__simplenavi`*)
 * **idx-tree.css** - the styling will be applied to all index trees (with *`ul.idx`*), regardless of parent container. It should work anywhere, but who knows... If necessary, make CSS adjustments to parent context in place.

So choose whichever of those files suits your needs (`idx-tree.css` if you want max beauty everywhere).

Suggestions & contributions are welcome.

Let all beings be free from suffering and delusions!

Ideas used from:

 * https://www.dokuwiki.org/plugin:indexmenu
 * https://css-tricks.com/
 * https://gist.github.com/dylancwood/7368914
 * https://jsfiddle.net/1fynun7a/1591/
