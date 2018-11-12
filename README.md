# DokuWiki tree view
Making DokuWiki site map and sidebar navigation tree beautiful. Just copy the contents of any of those CSS [files](#files), from here to your DokuWiki `/conf/userstyle.css`

Aaand... Poof!

![DokuWiki Site Map with this CSS](https://github.com/chang-zhao/dokuwiki-tree/blob/master/dw-tree-css.png)

All this is done with CSS borders and pseudo-elements, 100% virus-free. ;)

![CSS explanation](https://github.com/chang-zhao/dokuwiki-tree/blob/master/dw-tree-css-annot.png)

# Files:

 * dw-tree.css - for main site map only (parent container *`#index__tree`*)
 * simplenavi.css - the same styling, applied only to the tree of **simplenavi** plugin (parent container *`.plugin__simplenavi`*)
 * idx-tree.css - the same styling applied to all index trees (there are *`ul.idx`*), regardless of parent container. In that case, make adjustments to parent context in place if necessary.

Choose whatever of those files according to your needs. Suggestions & contributions are welcome.

Let all beings be free from suffering and delusions!

Ideas used from:

 * https://www.dokuwiki.org/plugin:indexmenu
 * https://css-tricks.com/
 * https://gist.github.com/dylancwood/7368914
 * https://jsfiddle.net/1fynun7a/1591/
