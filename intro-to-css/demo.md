Customizing Hosted ArcGIS Online Apps with CSS

1. CSS Basics
  1. [CSS Syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax)
  2. [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
    1. [ID](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors)
    2. [Class](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
      1. .className {}
      2. Gotchas:
        1. No spaces with class names in HTML;
        2. Select an element with class &quot;menu&quot; and class &quot;item&quot;
          1. .menu.item {}
        3. Select multiple items by separating selectors with &quot;,&quot;
        4. If you copy-paste class names from dev tools, you need to add a  &quot;.&quot; to the CSS selector
    3. [Descendent](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator)
    4. [Adjacent Sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator)
      1. Looks at the element that comes before the current one, the one that comes before must be that selector
    5. [General Sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator)
      1. Anything before it must be that selector
    6. [Child combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator)
  3. [Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
    1. **Description** : A pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s)…. Pseudo-classes let you apply a style to an element not only in relation to the content of the document tree, but also in relation to external factors like the history of the navigator (:visited, for example), the status of its content (like :checked on certain form elements), or the position of the mouse (like :hover, which lets you know if the mouse is over an element or not). [[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)]
    2. **Examples**
      1. :nth-child(n) {}
        1. :nth-child(1) {}
        2. :nth-child(odd) {}
      2. :nth-last-child(n) {}
        1. :nth-last-child(2) {}
      3. :nth-of-type(n) {}
      4. :nth-last-of-type(n) {}
      5. :first-of-type {}
      6. :last-of-type {}
      7. :last-child {}
      8. :first-child {}
      9. :not() {}
  4. [Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
    1. Description: pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s). [[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)]
  5. [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
    1. [@media](https://developer.mozilla.org/en-US/docs/Web/CSS/@media)
    2. Example:
      1. [EIG Website](https://eig.org/opportunityzones)
      2. [Standalone app](https://esrimedia.maps.arcgis.com/apps/View/index.html?appid=77f3cad12b6c4bffb816332544f04542)
  6. [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
    1. Positioning
    2. [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
    3. [Grid](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
2. Steps to CSS Customization
  1. Deploy app with AGO GUI customization
  2. Open app in a tab, open dev tools
  3. Find and make changes
  4. Copy any changes into a static css file
  5. Once finished making and copying changes, copy all CSS and autoprefix
  6. Copy all autoprefixed CSS and minify
  7. Copy minified CSS and paste into Custom CSS box in AGO
3. CSS Resources
  1. [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS)
    1. MDN \&gt; W3 Schools
  2. [Free Code Camp](https://www.freecodecamp.org/)
  3. [CSS for Geographers](http://patrickarlt.com/dev-summit-2019-talks/css-for-geographers/#/)
  4. [CSS Selectors](https://learn.shayhowe.com/advanced-html-css/complex-selectors/)
4. Learn CSS Layout
  1. [What the Flexbox](https://flexbox.io/) by Wes Bos
  2. [CSS Grid](https://cssgrid.io/) by Wes Bos
5. Tools
  1. [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
    1. Extensions:
      1. [Web Developer](https://addons.mozilla.org/en-US/firefox/addon/web-developer/)
  2. [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer)
  3. [CSS Optimizer](https://github.com/css/csso)
  4.
6. A note about CSS Grid
  1. Not supported in IE 10 &amp; 11
7. Misc.
  1. display: none;
  2. generate content with CSS
    1. combine content property with :before or :after
  3. [Transform](https://esrimedia.maps.arcgis.com/home/item.html?id=94d6fb566dbc4fbdae4ac59656ac56ca)
8. Examples of CSS customizations
  1.
