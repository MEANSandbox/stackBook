# CSS Position Property

this property defines type of positioning of an element

There are 4 different values 
1. static(default)
2. relative
3. fixed
4. absolute

after this elements are then positioned using Top,Left,Right,Bottom(make sure this property will not work unless the position property is set first)

1. static: is not affected by top,bottom,left,right property
##### it is always positioned according to the normal flow of the page
2. relative: set relative to it's normal position
3. fixed: this is positioned relative to the viewport (it means it always stays in the same place even if the page is scrolled down)
##### A fixed element does not leave a gap in the page where it would normally have been located
4. absolute: positioned relative to it's nearest positioned ancestor (instead of positioning relative to the viewport, liked ##### fixed)
##### However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling



# Overlapping Elements
#### use z-index property (to specifies the stack order)
