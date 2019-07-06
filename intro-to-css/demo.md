Customizing Hosted ArcGIS Online Apps with CSS

### CSS Basics
  - [CSS Syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax)
  - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
    - [ID](https://developer.mozilla.org/en-US/docs/Web/CSS/ID_selectors)
    - [Class](https://developer.mozilla.org/en-US/docs/Web/CSS/Class_selectors)
      - .className {}
      - Gotchas:
        - No spaces with class names in HTML;
        - Select an element with class &quot;menu&quot; and class &quot;item&quot;
          - .menu.item {}
        - Select multiple items by separating selectors with &quot;,&quot;
        - If you copy-paste class names from dev tools, you need to add a  &quot;.&quot; to the CSS selector
    - [Descendent](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator)
    - [Adjacent Sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/Adjacent_sibling_combinator)
      - Looks at the element that comes before the current one, the one that comes before must be that selector
    - [General Sibling](https://developer.mozilla.org/en-US/docs/Web/CSS/General_sibling_combinator)
      - Anything before it must be that selector
    - [Child combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Child_combinator)
  - [Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
    - **Description** : A pseudo-class is a keyword added to a selector that specifies a special state of the selected element(s)…. Pseudo-classes let you apply a style to an element not only in relation to the content of the document tree, but also in relation to external factors like the history of the navigator (:visited, for example), the status of its content (like :checked on certain form elements), or the position of the mouse (like :hover, which lets you know if the mouse is over an element or not). [[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)]
    - **Examples**
      - :nth-child(n) {}
        - :nth-child(1) {}
        - :nth-child(odd) {}
      - :nth-last-child(n) {}
        - :nth-last-child(2) {}
      - :nth-of-type(n) {}
      - :nth-last-of-type(n) {}
      - :first-of-type {}
      - :last-of-type {}
      - :last-child {}
      - :first-child {}
      - :not() {}
  - [Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
    - Description: pseudo-element is a keyword added to a selector that lets you style a specific part of the selected element(s). [[MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)]
  - [Media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries)
    - [@media](https://developer.mozilla.org/en-US/docs/Web/CSS/@media)
    - Example:
      - [EIG Website](https://eig.org/opportunityzones)
      - [Standalone app](https://esrimedia.maps.arcgis.com/apps/View/index.html?appid=77f3cad12b6c4bffb816332544f04542)
  - [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
    - Positioning
    - [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)
    - [Grid](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grids)
### Steps to CSS Customization
  - Deploy app with AGO GUI customization
  - Open app in a tab, open dev tools
  - Find and make changes
  - Copy any changes into a static css file
  - Once finished making and copying changes, copy all CSS and autoprefix
  - Copy all autoprefixed CSS and minify
  - Copy minified CSS and paste into Custom CSS box in AGO
### CSS Resources
  - [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS)
    - MDN \&gt; W3 Schools
  - [Free Code Camp](https://www.freecodecamp.org/)
  - [CSS for Geographers](http://patrickarlt.com/dev-summit-2019-talks/css-for-geographers/#/)
  - [CSS Selectors](https://learn.shayhowe.com/advanced-html-css/complex-selectors/)
### Learn CSS Layout
  - [What the Flexbox](https://flexbox.io/) by Wes Bos
  - [CSS Grid](https://cssgrid.io/) by Wes Bos
### Tools
  - [Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/)
    - Extensions:
      - [Web Developer](https://addons.mozilla.org/en-US/firefox/addon/web-developer/)
  - [PostCSS Autoprefixer](https://github.com/postcss/autoprefixer)
  - [CSS Optimizer](https://github.com/css/csso)
### A note about CSS Grid
  - Not supported in IE 10 &amp; 11
### Misc.
  - display: none;
  - generate content with CSS
    - combine content property with :before or :after
  - [Transform](https://esrimedia.maps.arcgis.com/home/item.html?id=94d6fb566dbc4fbdae4ac59656ac56ca)
### Examples of CSS customizations
  -
