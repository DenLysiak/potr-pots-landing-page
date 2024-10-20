# POTR POTS 
 - [DEMO LINK](https://DenLysiak.github.io/potr-pots-landing-page/)
 - [MOCKUP LINK](https://www.figma.com/design/50zgLU65Mcd3MisFHMfLfx/POTR-POTS_FE-students?node-id=1760-281&node-type=canvas)

Landing page is built on basic HTML and SCSS. The page consist of 9 responsive blocks: 
-  'header' navigation block;
-  'For whom' block.
-  'Features' block.
-  'POTR team' block with the card reused 3 times.
-  'Materials' block with 4 process cards.
-  'POTR size' block.
-  'Benefits' block.
-  'Questions' block
-   the footer;

The navigation bar is performed with anchor tags tied to block's id, for page navigation. On mobile devices navigation is done as separate side menu.

All scss files connected to one index.scss file. Page has mixins to adapt layout according screen width, container mixin to set paddings equaly throught the page and grid mixin to keep page adaptive.

Throught app scss pseudo-classes such as: 'hover', 'active', 'visited', 'focus', '-webkit-autofill' - are used to make appropriate style changes.

To style separate elements pseudo-elements are used such as: 'placeholder', 'after/before elements', '-webkit-scrollbar'.

Slider on mobile devices performed using properties: '-webkit-overflow-scrolling', 'scroll-snap-type' with 'with display: flex' on container and 'flex-shrink: 0' on single slide,
so on user screen can be seen only one slide at the time, but whole container can be scrolled left and right smootly;

Also, to avoid style mistakes separate variables file is used to keep all repetitive styles in one place.
All images and icons are placed in separate folder, compresed and some icons are used as 'svg' files to keep best resolutions.

Fonts used on the page are located in separate folder and connected to page using 'font face'.
