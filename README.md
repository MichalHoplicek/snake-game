# snake-game
snake-game
@import url('https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap');

@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500&display=swap');

@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400&display=swap');

*, ::before, ::after{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}

::backdrop{
  --tw-border-spacing-x: 0;
  --tw-border-spacing-y: 0;
  --tw-translate-x: 0;
  --tw-translate-y: 0;
  --tw-rotate: 0;
  --tw-skew-x: 0;
  --tw-skew-y: 0;
  --tw-scale-x: 1;
  --tw-scale-y: 1;
  --tw-pan-x:  ;
  --tw-pan-y:  ;
  --tw-pinch-zoom:  ;
  --tw-scroll-snap-strictness: proximity;
  --tw-gradient-from-position:  ;
  --tw-gradient-via-position:  ;
  --tw-gradient-to-position:  ;
  --tw-ordinal:  ;
  --tw-slashed-zero:  ;
  --tw-numeric-figure:  ;
  --tw-numeric-spacing:  ;
  --tw-numeric-fraction:  ;
  --tw-ring-inset:  ;
  --tw-ring-offset-width: 0px;
  --tw-ring-offset-color: #fff;
  --tw-ring-color: rgb(59 130 246 / 0.5);
  --tw-ring-offset-shadow: 0 0 #0000;
  --tw-ring-shadow: 0 0 #0000;
  --tw-shadow: 0 0 #0000;
  --tw-shadow-colored: 0 0 #0000;
  --tw-blur:  ;
  --tw-brightness:  ;
  --tw-contrast:  ;
  --tw-grayscale:  ;
  --tw-hue-rotate:  ;
  --tw-invert:  ;
  --tw-saturate:  ;
  --tw-sepia:  ;
  --tw-drop-shadow:  ;
  --tw-backdrop-blur:  ;
  --tw-backdrop-brightness:  ;
  --tw-backdrop-contrast:  ;
  --tw-backdrop-grayscale:  ;
  --tw-backdrop-hue-rotate:  ;
  --tw-backdrop-invert:  ;
  --tw-backdrop-opacity:  ;
  --tw-backdrop-saturate:  ;
  --tw-backdrop-sepia:  ;
  --tw-contain-size:  ;
  --tw-contain-layout:  ;
  --tw-contain-paint:  ;
  --tw-contain-style:  ;
}

/*
! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com
*/

/*
1. Prevent padding and border from affecting element width. (https://github.com/mozdevs/cssremedy/issues/4)
2. Allow adding a border to an element by just adding a border-width. (https://github.com/tailwindcss/tailwindcss/pull/116)
*/

*,
::before,
::after {
  box-sizing: border-box;
  /* 1 */
  border-width: 0;
  /* 2 */
  border-style: solid;
  /* 2 */
  border-color: #e5e7eb;
  /* 2 */
}

::before,
::after {
  --tw-content: '';
}

/*
1. Use a consistent sensible line-height in all browsers.
2. Prevent adjustments of font size after orientation changes in iOS.
3. Use a more readable tab size.
4. Use the user's configured `sans` font-family by default.
5. Use the user's configured `sans` font-feature-settings by default.
6. Use the user's configured `sans` font-variation-settings by default.
7. Disable tap highlights on iOS
*/

html,
:host {
  line-height: 1.5;
  /* 1 */
  -webkit-text-size-adjust: 100%;
  /* 2 */
  -moz-tab-size: 4;
  /* 3 */
  -o-tab-size: 4;
     tab-size: 4;
  /* 3 */
  font-family: Inter, sans-serif;
  /* 4 */
  font-feature-settings: normal;
  /* 5 */
  font-variation-settings: normal;
  /* 6 */
  -webkit-tap-highlight-color: transparent;
  /* 7 */
}

/*
1. Remove the margin in all browsers.
2. Inherit line-height from `html` so users can set them as a class directly on the `html` element.
*/

body {
  margin: 0;
  /* 1 */
  line-height: inherit;
  /* 2 */
}

/*
1. Add the correct height in Firefox.
2. Correct the inheritance of border color in Firefox. (https://bugzilla.mozilla.org/show_bug.cgi?id=190655)
3. Ensure horizontal rules are visible by default.
*/

hr {
  height: 0;
  /* 1 */
  color: inherit;
  /* 2 */
  border-top-width: 1px;
  /* 3 */
}

/*
Add the correct text decoration in Chrome, Edge, and Safari.
*/

abbr:where([title]) {
  -webkit-text-decoration: underline dotted;
          text-decoration: underline dotted;
}

/*
Remove the default font size and weight for headings.
*/

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: inherit;
  font-weight: inherit;
}

/*
Reset links to optimize for opt-in styling instead of opt-out.
*/

a {
  color: inherit;
  text-decoration: inherit;
}

/*
Add the correct font weight in Edge and Safari.
*/

b,
strong {
  font-weight: bolder;
}

/*
1. Use the user's configured `mono` font-family by default.
2. Use the user's configured `mono` font-feature-settings by default.
3. Use the user's configured `mono` font-variation-settings by default.
4. Correct the odd `em` font sizing in all browsers.
*/

code,
kbd,
samp,
pre {
  font-family: JetBrains Mono, monospace;
  /* 1 */
  font-feature-settings: normal;
  /* 2 */
  font-variation-settings: normal;
  /* 3 */
  font-size: 1em;
  /* 4 */
}

/*
Add the correct font size in all browsers.
*/

small {
  font-size: 80%;
}

/*
Prevent `sub` and `sup` elements from affecting the line height in all browsers.
*/

sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}

sub {
  bottom: -0.25em;
}

sup {
  top: -0.5em;
}

/*
1. Remove text indentation from table contents in Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=999088, https://bugs.webkit.org/show_bug.cgi?id=201297)
2. Correct table border color inheritance in all Chrome and Safari. (https://bugs.chromium.org/p/chromium/issues/detail?id=935729, https://bugs.webkit.org/show_bug.cgi?id=195016)
3. Remove gaps between table borders by default.
*/

table {
  text-indent: 0;
  /* 1 */
  border-color: inherit;
  /* 2 */
  border-collapse: collapse;
  /* 3 */
}

/*
1. Change the font styles in all browsers.
2. Remove the margin in Firefox and Safari.
3. Remove default padding in all browsers.
*/

button,
input,
optgroup,
select,
textarea {
  font-family: inherit;
  /* 1 */
  font-feature-settings: inherit;
  /* 1 */
  font-variation-settings: inherit;
  /* 1 */
  font-size: 100%;
  /* 1 */
  font-weight: inherit;
  /* 1 */
  line-height: inherit;
  /* 1 */
  letter-spacing: inherit;
  /* 1 */
  color: inherit;
  /* 1 */
  margin: 0;
  /* 2 */
  padding: 0;
  /* 3 */
}

/*
Remove the inheritance of text transform in Edge and Firefox.
*/

button,
select {
  text-transform: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Remove default button styles.
*/

button,
input:where([type='button']),
input:where([type='reset']),
input:where([type='submit']) {
  -webkit-appearance: button;
  /* 1 */
  background-color: transparent;
  /* 2 */
  background-image: none;
  /* 2 */
}

/*
Use the modern Firefox focus style for all focusable elements.
*/

:-moz-focusring {
  outline: auto;
}

/*
Remove the additional `:invalid` styles in Firefox. (https://github.com/mozilla/gecko-dev/blob/2f9eacd9d3d995c937b4251a5557d95d494c9be1/layout/style/res/forms.css#L728-L737)
*/

:-moz-ui-invalid {
  box-shadow: none;
}

/*
Add the correct vertical alignment in Chrome and Firefox.
*/

progress {
  vertical-align: baseline;
}

/*
Correct the cursor style of increment and decrement buttons in Safari.
*/

::-webkit-inner-spin-button,
::-webkit-outer-spin-button {
  height: auto;
}

/*
1. Correct the odd appearance in Chrome and Safari.
2. Correct the outline style in Safari.
*/

[type='search'] {
  -webkit-appearance: textfield;
  /* 1 */
  outline-offset: -2px;
  /* 2 */
}

/*
Remove the inner padding in Chrome and Safari on macOS.
*/

::-webkit-search-decoration {
  -webkit-appearance: none;
}

/*
1. Correct the inability to style clickable types in iOS and Safari.
2. Change font properties to `inherit` in Safari.
*/

::-webkit-file-upload-button {
  -webkit-appearance: button;
  /* 1 */
  font: inherit;
  /* 2 */
}

/*
Add the correct display in Chrome and Safari.
*/

summary {
  display: list-item;
}

/*
Removes the default spacing and border for appropriate elements.
*/

blockquote,
dl,
dd,
h1,
h2,
h3,
h4,
h5,
h6,
hr,
figure,
p,
pre {
  margin: 0;
}

fieldset {
  margin: 0;
  padding: 0;
}

legend {
  padding: 0;
}

ol,
ul,
menu {
  list-style: none;
  margin: 0;
  padding: 0;
}

/*
Reset default styling for dialogs.
*/

dialog {
  padding: 0;
}

/*
Prevent resizing textareas horizontally by default.
*/

textarea {
  resize: vertical;
}

/*
1. Reset the default placeholder opacity in Firefox. (https://github.com/tailwindlabs/tailwindcss/issues/3300)
2. Set the default placeholder color to the user's configured gray 400 color.
*/

input::-moz-placeholder, textarea::-moz-placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

input::placeholder,
textarea::placeholder {
  opacity: 1;
  /* 1 */
  color: #9ca3af;
  /* 2 */
}

/*
Set the default cursor for buttons.
*/

button,
[role="button"] {
  cursor: pointer;
}

/*
Make sure disabled buttons don't get the pointer cursor.
*/

:disabled {
  cursor: default;
}

/*
1. Make replaced elements `display: block` by default. (https://github.com/mozdevs/cssremedy/issues/14)
2. Add `vertical-align: middle` to align replaced elements more sensibly by default. (https://github.com/jensimmons/cssremedy/issues/14#issuecomment-634934210)
   This can trigger a poorly considered lint error in some tools but is included by design.
*/

img,
svg,
video,
canvas,
audio,
iframe,
embed,
object {
  display: block;
  /* 1 */
  vertical-align: middle;
  /* 2 */
}

/*
Constrain images and videos to the parent width and preserve their intrinsic aspect ratio. (https://github.com/mozdevs/cssremedy/issues/14)
*/

img,
video {
  max-width: 100%;
  height: auto;
}

/* Make elements with the HTML hidden attribute stay hidden by default */

[hidden]:where(:not([hidden="until-found"])) {
  display: none;
}

body {
  font-family: 'Inter', sans-serif;
  background-color: var(--color-background);
  color: var(--color-text-primary);
}

h1, h2, h3, h4, h5, h6 {
  font-family: 'Space Mono', monospace;
}

.font-mono {
  font-family: 'JetBrains Mono', monospace;
}

.container{
  width: 100%;
}

@media (min-width: 640px){
  .container{
    max-width: 640px;
  }
}

@media (min-width: 768px){
  .container{
    max-width: 768px;
  }
}

@media (min-width: 1024px){
  .container{
    max-width: 1024px;
  }
}

@media (min-width: 1280px){
  .container{
    max-width: 1280px;
  }
}

@media (min-width: 1536px){
  .container{
    max-width: 1536px;
  }
}

.btn-primary{
  border-radius: 0.5rem;
  --tw-bg-opacity: 1;
  background-color: rgb(0 255 136 / var(--tw-bg-opacity, 1));
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  font-weight: 700;
  --tw-text-opacity: 1;
  color: rgb(10 10 15 / var(--tw-text-opacity, 1));
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 200ms;
  transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
}

.btn-primary:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(0 230 122 / var(--tw-bg-opacity, 1));
}

.btn-primary:active{
  --tw-scale-x: .95;
  --tw-scale-y: .95;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.btn-primary {
  font-family: 'Space Mono', monospace;
}

.btn-secondary{
  border-radius: 0.5rem;
  border-width: 1px;
  --tw-border-opacity: 1;
  border-color: rgb(0 255 136 / var(--tw-border-opacity, 1));
  --tw-bg-opacity: 1;
  background-color: rgb(26 26 46 / var(--tw-bg-opacity, 1));
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
  padding-left: 1.5rem;
  padding-right: 1.5rem;
  font-weight: 700;
  --tw-text-opacity: 1;
  color: rgb(0 255 136 / var(--tw-text-opacity, 1));
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 200ms;
  transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
}

.btn-secondary:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(0 255 136 / var(--tw-bg-opacity, 1));
  --tw-text-opacity: 1;
  color: rgb(10 10 15 / var(--tw-text-opacity, 1));
}

.btn-secondary:active{
  --tw-scale-x: .95;
  --tw-scale-y: .95;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.btn-secondary {
  font-family: 'Space Mono', monospace;
}

.game-shadow {
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.3);
}

.achievement-shadow {
  box-shadow: 0 8px 32px rgba(0, 255, 136, 0.2);
}

.sr-only{
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap;
  border-width: 0;
}

.static{
  position: static;
}

.fixed{
  position: fixed;
}

.absolute{
  position: absolute;
}

.relative{
  position: relative;
}

.sticky{
  position: sticky;
}

.inset-0{
  inset: 0px;
}

.-right-2{
  right: -0.5rem;
}

.-top-2{
  top: -0.5rem;
}

.-top-4{
  top: -1rem;
}

.left-1\/2{
  left: 50%;
}

.left-4{
  left: 1rem;
}

.right-4{
  right: 1rem;
}

.top-0{
  top: 0px;
}

.top-1\/2{
  top: 50%;
}

.top-4{
  top: 1rem;
}

.z-50{
  z-index: 50;
}

.mx-auto{
  margin-left: auto;
  margin-right: auto;
}

.mb-1{
  margin-bottom: 0.25rem;
}

.mb-2{
  margin-bottom: 0.5rem;
}

.mb-3{
  margin-bottom: 0.75rem;
}

.mb-4{
  margin-bottom: 1rem;
}

.mb-6{
  margin-bottom: 1.5rem;
}

.mb-8{
  margin-bottom: 2rem;
}

.mr-2{
  margin-right: 0.5rem;
}

.mt-0\.5{
  margin-top: 0.125rem;
}

.mt-1{
  margin-top: 0.25rem;
}

.mt-2{
  margin-top: 0.5rem;
}

.mt-4{
  margin-top: 1rem;
}

.mt-6{
  margin-top: 1.5rem;
}

.mt-8{
  margin-top: 2rem;
}

.block{
  display: block;
}

.inline-block{
  display: inline-block;
}

.inline{
  display: inline;
}

.flex{
  display: flex;
}

.inline-flex{
  display: inline-flex;
}

.grid{
  display: grid;
}

.hidden{
  display: none;
}

.h-10{
  height: 2.5rem;
}

.h-12{
  height: 3rem;
}

.h-16{
  height: 4rem;
}

.h-2{
  height: 0.5rem;
}

.h-20{
  height: 5rem;
}

.h-24{
  height: 6rem;
}

.h-3{
  height: 0.75rem;
}

.h-4{
  height: 1rem;
}

.h-5{
  height: 1.25rem;
}

.h-6{
  height: 1.5rem;
}

.h-64{
  height: 16rem;
}

.h-8{
  height: 2rem;
}

.h-auto{
  height: auto;
}

.min-h-screen{
  min-height: 100vh;
}

.w-10{
  width: 2.5rem;
}

.w-11{
  width: 2.75rem;
}

.w-12{
  width: 3rem;
}

.w-16{
  width: 4rem;
}

.w-2{
  width: 0.5rem;
}

.w-20{
  width: 5rem;
}

.w-24{
  width: 6rem;
}

.w-3{
  width: 0.75rem;
}

.w-32{
  width: 8rem;
}

.w-4{
  width: 1rem;
}

.w-5{
  width: 1.25rem;
}

.w-6{
  width: 1.5rem;
}

.w-8{
  width: 2rem;
}

.w-full{
  width: 100%;
}

.max-w-2xl{
  max-width: 42rem;
}

.max-w-48{
  max-width: 12rem;
}

.max-w-full{
  max-width: 100%;
}

.max-w-md{
  max-width: 28rem;
}

.flex-1{
  flex: 1 1 0%;
}

.flex-shrink-0{
  flex-shrink: 0;
}

.-translate-x-1\/2{
  --tw-translate-x: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.-translate-y-1\/2{
  --tw-translate-y: -50%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.translate-x-1{
  --tw-translate-x: 0.25rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.translate-x-6{
  --tw-translate-x: 1.5rem;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.translate-x-full{
  --tw-translate-x: 100%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.transform{
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.cursor-pointer{
  cursor: pointer;
}

.resize{
  resize: both;
}

.grid-cols-1{
  grid-template-columns: repeat(1, minmax(0, 1fr));
}

.grid-cols-2{
  grid-template-columns: repeat(2, minmax(0, 1fr));
}

.grid-cols-3{
  grid-template-columns: repeat(3, minmax(0, 1fr));
}

.flex-col{
  flex-direction: column;
}

.flex-wrap{
  flex-wrap: wrap;
}

.items-start{
  align-items: flex-start;
}

.items-end{
  align-items: flex-end;
}

.items-center{
  align-items: center;
}

.justify-center{
  justify-content: center;
}

.justify-between{
  justify-content: space-between;
}

.gap-1{
  gap: 0.25rem;
}

.gap-2{
  gap: 0.5rem;
}

.gap-3{
  gap: 0.75rem;
}

.gap-4{
  gap: 1rem;
}

.gap-6{
  gap: 1.5rem;
}

.space-x-1 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(0.25rem * var(--tw-space-x-reverse));
  margin-left: calc(0.25rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-2 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(0.5rem * var(--tw-space-x-reverse));
  margin-left: calc(0.5rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-3 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(0.75rem * var(--tw-space-x-reverse));
  margin-left: calc(0.75rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-4 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(1rem * var(--tw-space-x-reverse));
  margin-left: calc(1rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-x-6 > :not([hidden]) ~ :not([hidden]){
  --tw-space-x-reverse: 0;
  margin-right: calc(1.5rem * var(--tw-space-x-reverse));
  margin-left: calc(1.5rem * calc(1 - var(--tw-space-x-reverse)));
}

.space-y-2 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.5rem * var(--tw-space-y-reverse));
}

.space-y-3 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(0.75rem * var(--tw-space-y-reverse));
}

.space-y-4 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(1rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1rem * var(--tw-space-y-reverse));
}

.space-y-6 > :not([hidden]) ~ :not([hidden]){
  --tw-space-y-reverse: 0;
  margin-top: calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));
  margin-bottom: calc(1.5rem * var(--tw-space-y-reverse));
}

.divide-y > :not([hidden]) ~ :not([hidden]){
  --tw-divide-y-reverse: 0;
  border-top-width: calc(1px * calc(1 - var(--tw-divide-y-reverse)));
  border-bottom-width: calc(1px * var(--tw-divide-y-reverse));
}

.divide-surface-700 > :not([hidden]) ~ :not([hidden]){
  --tw-divide-opacity: 1;
  border-color: rgb(46 46 71 / var(--tw-divide-opacity, 1));
}

.overflow-hidden{
  overflow: hidden;
}

.rounded{
  border-radius: 0.25rem;
}

.rounded-full{
  border-radius: 9999px;
}

.rounded-lg{
  border-radius: 0.5rem;
}

.rounded-sm{
  border-radius: 0.125rem;
}

.rounded-t{
  border-top-left-radius: 0.25rem;
  border-top-right-radius: 0.25rem;
}

.border{
  border-width: 1px;
}

.border-2{
  border-width: 2px;
}

.border-4{
  border-width: 4px;
}

.border-b{
  border-bottom-width: 1px;
}

.border-b-2{
  border-bottom-width: 2px;
}

.border-l-4{
  border-left-width: 4px;
}

.border-t{
  border-top-width: 1px;
}

.border-accent{
  --tw-border-opacity: 1;
  border-color: rgb(0 212 255 / var(--tw-border-opacity, 1));
}

.border-primary{
  --tw-border-opacity: 1;
  border-color: rgb(0 255 136 / var(--tw-border-opacity, 1));
}

.border-secondary{
  --tw-border-opacity: 1;
  border-color: rgb(255 107 53 / var(--tw-border-opacity, 1));
}

.border-surface-700{
  --tw-border-opacity: 1;
  border-color: rgb(46 46 71 / var(--tw-border-opacity, 1));
}

.border-text-secondary{
  --tw-border-opacity: 1;
  border-color: rgb(160 160 176 / var(--tw-border-opacity, 1));
}

.bg-accent{
  --tw-bg-opacity: 1;
  background-color: rgb(0 212 255 / var(--tw-bg-opacity, 1));
}

.bg-background{
  --tw-bg-opacity: 1;
  background-color: rgb(10 10 15 / var(--tw-bg-opacity, 1));
}

.bg-background-800{
  --tw-bg-opacity: 1;
  background-color: rgb(20 20 25 / var(--tw-bg-opacity, 1));
}

.bg-blue-500{
  --tw-bg-opacity: 1;
  background-color: rgb(59 130 246 / var(--tw-bg-opacity, 1));
}

.bg-error{
  --tw-bg-opacity: 1;
  background-color: rgb(255 71 87 / var(--tw-bg-opacity, 1));
}

.bg-primary{
  --tw-bg-opacity: 1;
  background-color: rgb(0 255 136 / var(--tw-bg-opacity, 1));
}

.bg-secondary{
  --tw-bg-opacity: 1;
  background-color: rgb(255 107 53 / var(--tw-bg-opacity, 1));
}

.bg-success{
  --tw-bg-opacity: 1;
  background-color: rgb(0 255 136 / var(--tw-bg-opacity, 1));
}

.bg-surface{
  --tw-bg-opacity: 1;
  background-color: rgb(26 26 46 / var(--tw-bg-opacity, 1));
}

.bg-surface-700{
  --tw-bg-opacity: 1;
  background-color: rgb(46 46 71 / var(--tw-bg-opacity, 1));
}

.bg-surface-800{
  --tw-bg-opacity: 1;
  background-color: rgb(36 36 56 / var(--tw-bg-opacity, 1));
}

.bg-warning{
  --tw-bg-opacity: 1;
  background-color: rgb(255 184 0 / var(--tw-bg-opacity, 1));
}

.bg-white{
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
}

.bg-opacity-20{
  --tw-bg-opacity: 0.2;
}

.bg-opacity-90{
  --tw-bg-opacity: 0.9;
}

.object-cover{
  -o-object-fit: cover;
     object-fit: cover;
}

.p-2{
  padding: 0.5rem;
}

.p-3{
  padding: 0.75rem;
}

.p-4{
  padding: 1rem;
}

.p-6{
  padding: 1.5rem;
}

.px-2{
  padding-left: 0.5rem;
  padding-right: 0.5rem;
}

.px-3{
  padding-left: 0.75rem;
  padding-right: 0.75rem;
}

.px-4{
  padding-left: 1rem;
  padding-right: 1rem;
}

.px-6{
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}

.py-1{
  padding-top: 0.25rem;
  padding-bottom: 0.25rem;
}

.py-2{
  padding-top: 0.5rem;
  padding-bottom: 0.5rem;
}

.py-3{
  padding-top: 0.75rem;
  padding-bottom: 0.75rem;
}

.py-6{
  padding-top: 1.5rem;
  padding-bottom: 1.5rem;
}

.pb-1{
  padding-bottom: 0.25rem;
}

.pb-4{
  padding-bottom: 1rem;
}

.pl-12{
  padding-left: 3rem;
}

.pr-4{
  padding-right: 1rem;
}

.pt-4{
  padding-top: 1rem;
}

.text-left{
  text-align: left;
}

.text-center{
  text-align: center;
}

.text-right{
  text-align: right;
}

.font-display{
  font-family: Space Mono, monospace;
}

.font-mono{
  font-family: JetBrains Mono, monospace;
}

.font-sans{
  font-family: Inter, sans-serif;
}

.text-2xl{
  font-size: 1.5rem;
  line-height: 2rem;
}

.text-3xl{
  font-size: 1.875rem;
  line-height: 2.25rem;
}

.text-4xl{
  font-size: 2.25rem;
  line-height: 2.5rem;
}

.text-lg{
  font-size: 1.125rem;
  line-height: 1.75rem;
}

.text-sm{
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.text-xl{
  font-size: 1.25rem;
  line-height: 1.75rem;
}

.text-xs{
  font-size: 0.75rem;
  line-height: 1rem;
}

.font-bold{
  font-weight: 700;
}

.font-medium{
  font-weight: 500;
}

.text-accent{
  --tw-text-opacity: 1;
  color: rgb(0 212 255 / var(--tw-text-opacity, 1));
}

.text-background{
  --tw-text-opacity: 1;
  color: rgb(10 10 15 / var(--tw-text-opacity, 1));
}

.text-error{
  --tw-text-opacity: 1;
  color: rgb(255 71 87 / var(--tw-text-opacity, 1));
}

.text-primary{
  --tw-text-opacity: 1;
  color: rgb(0 255 136 / var(--tw-text-opacity, 1));
}

.text-secondary{
  --tw-text-opacity: 1;
  color: rgb(255 107 53 / var(--tw-text-opacity, 1));
}

.text-success{
  --tw-text-opacity: 1;
  color: rgb(0 255 136 / var(--tw-text-opacity, 1));
}

.text-text-primary{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.text-text-secondary{
  --tw-text-opacity: 1;
  color: rgb(160 160 176 / var(--tw-text-opacity, 1));
}

.text-warning{
  --tw-text-opacity: 1;
  color: rgb(255 184 0 / var(--tw-text-opacity, 1));
}

.text-warning-600{
  --tw-text-opacity: 1;
  color: rgb(230 166 0 / var(--tw-text-opacity, 1));
}

.text-white{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.placeholder-text-secondary::-moz-placeholder{
  --tw-placeholder-opacity: 1;
  color: rgb(160 160 176 / var(--tw-placeholder-opacity, 1));
}

.placeholder-text-secondary::placeholder{
  --tw-placeholder-opacity: 1;
  color: rgb(160 160 176 / var(--tw-placeholder-opacity, 1));
}

.opacity-30{
  opacity: 0.3;
}

.opacity-40{
  opacity: 0.4;
}

.opacity-50{
  opacity: 0.5;
}

.opacity-60{
  opacity: 0.6;
}

.opacity-70{
  opacity: 0.7;
}

.opacity-80{
  opacity: 0.8;
}

.opacity-90{
  opacity: 0.9;
}

.opacity-95{
  opacity: 0.95;
}

.shadow-lg{
  --tw-shadow: 0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow);
}

.filter{
  filter: var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow);
}

.backdrop-blur-sm{
  --tw-backdrop-blur: blur(4px);
  -webkit-backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
  backdrop-filter: var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);
}

.transition{
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-backdrop-filter;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.transition-all{
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.transition-colors{
  transition-property: color, background-color, border-color, text-decoration-color, fill, stroke;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.transition-transform{
  transition-property: transform;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.duration-300{
  transition-duration: 300ms;
}

.ease-out{
  transition-timing-function: cubic-bezier(0, 0, 0.2, 1);
}

:root {
  /* Primary Colors */
  --color-primary: #00FF88;
  /* snake-green */
  --color-primary-50: #E6FFF4;
  /* snake-green-50 */
  --color-primary-100: #CCFFE9;
  /* snake-green-100 */
  --color-primary-500: #00FF88;
  /* snake-green-500 */
  --color-primary-600: #00E67A;
  /* snake-green-600 */
  --color-primary-700: #00CC6C;
  /* snake-green-700 */
  --color-primary-900: #009954;
  /* snake-green-900 */
  /* Secondary Colors */
  --color-secondary: #FF6B35;
  /* target-orange */
  --color-secondary-50: #FFF2ED;
  /* target-orange-50 */
  --color-secondary-100: #FFE5DB;
  /* target-orange-100 */
  --color-secondary-500: #FF6B35;
  /* target-orange-500 */
  --color-secondary-600: #E65F30;
  /* target-orange-600 */
  --color-secondary-700: #CC532B;
  /* target-orange-700 */
  --color-secondary-900: #994020;
  /* target-orange-900 */
  /* Accent Colors */
  --color-accent: #00D4FF;
  /* neon-cyan */
  --color-accent-50: #E6F9FF;
  /* neon-cyan-50 */
  --color-accent-100: #CCF3FF;
  /* neon-cyan-100 */
  --color-accent-500: #00D4FF;
  /* neon-cyan-500 */
  --color-accent-600: #00BFE6;
  /* neon-cyan-600 */
  --color-accent-700: #00AACC;
  /* neon-cyan-700 */
  --color-accent-900: #008099;
  /* neon-cyan-900 */
  /* Background Colors */
  --color-background: #0A0A0F;
  /* deep-space */
  --color-background-50: #F5F5F6;
  /* deep-space-50 */
  --color-background-100: #EBEBED;
  /* deep-space-100 */
  --color-background-800: #141419;
  /* deep-space-800 */
  --color-background-900: #0A0A0F;
  /* deep-space-900 */
  /* Surface Colors */
  --color-surface: #1A1A2E;
  /* game-board */
  --color-surface-50: #F6F6F8;
  /* game-board-50 */
  --color-surface-100: #EDEDF1;
  /* game-board-100 */
  --color-surface-200: #DBDBE3;
  /* game-board-200 */
  --color-surface-700: #2E2E47;
  /* game-board-700 */
  --color-surface-800: #242438;
  /* game-board-800 */
  --color-surface-900: #1A1A2E;
  /* game-board-900 */
  /* Text Colors */
  --color-text-primary: #FFFFFF;
  /* white */
  --color-text-secondary: #A0A0B0;
  /* gray-400 */
  --color-text-muted: #6B7280;
  /* gray-500 */
  /* Status Colors */
  --color-success: #00FF88;
  /* snake-green */
  --color-warning: #FFB800;
  /* amber-alert */
  --color-warning-50: #FFFBEB;
  /* amber-alert-50 */
  --color-warning-100: #FEF3C7;
  /* amber-alert-100 */
  --color-warning-500: #FFB800;
  /* amber-alert-500 */
  --color-warning-600: #E6A600;
  /* amber-alert-600 */
  --color-warning-700: #CC9500;
  /* amber-alert-700 */
  --color-warning-900: #996F00;
  /* amber-alert-900 */
  --color-error: #FF4757;
  /* helpful-red */
  --color-error-50: #FEF2F2;
  /* helpful-red-50 */
  --color-error-100: #FEE2E2;
  /* helpful-red-100 */
  --color-error-500: #FF4757;
  /* helpful-red-500 */
  --color-error-600: #E63E4D;
  /* helpful-red-600 */
  --color-error-700: #CC3544;
  /* helpful-red-700 */
  --color-error-900: #992833;
  /* helpful-red-900 */
}

.after\:absolute::after{
  content: var(--tw-content);
  position: absolute;
}

.after\:left-\[2px\]::after{
  content: var(--tw-content);
  left: 2px;
}

.after\:top-\[2px\]::after{
  content: var(--tw-content);
  top: 2px;
}

.after\:h-5::after{
  content: var(--tw-content);
  height: 1.25rem;
}

.after\:w-5::after{
  content: var(--tw-content);
  width: 1.25rem;
}

.after\:rounded-full::after{
  content: var(--tw-content);
  border-radius: 9999px;
}

.after\:bg-white::after{
  content: var(--tw-content);
  --tw-bg-opacity: 1;
  background-color: rgb(255 255 255 / var(--tw-bg-opacity, 1));
}

.after\:transition-all::after{
  content: var(--tw-content);
  transition-property: all;
  transition-timing-function: cubic-bezier(0.4, 0, 0.2, 1);
  transition-duration: 150ms;
}

.after\:content-\[\'\'\]::after{
  --tw-content: '';
  content: var(--tw-content);
}

.hover\:border-accent:hover{
  --tw-border-opacity: 1;
  border-color: rgb(0 212 255 / var(--tw-border-opacity, 1));
}

.hover\:border-primary:hover{
  --tw-border-opacity: 1;
  border-color: rgb(0 255 136 / var(--tw-border-opacity, 1));
}

.hover\:bg-error-600:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(230 62 77 / var(--tw-bg-opacity, 1));
}

.hover\:bg-surface-700:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(46 46 71 / var(--tw-bg-opacity, 1));
}

.hover\:bg-surface-800:hover{
  --tw-bg-opacity: 1;
  background-color: rgb(36 36 56 / var(--tw-bg-opacity, 1));
}

.hover\:text-accent:hover{
  --tw-text-opacity: 1;
  color: rgb(0 212 255 / var(--tw-text-opacity, 1));
}

.hover\:text-accent-600:hover{
  --tw-text-opacity: 1;
  color: rgb(0 191 230 / var(--tw-text-opacity, 1));
}

.hover\:text-primary:hover{
  --tw-text-opacity: 1;
  color: rgb(0 255 136 / var(--tw-text-opacity, 1));
}

.hover\:text-text-primary:hover{
  --tw-text-opacity: 1;
  color: rgb(255 255 255 / var(--tw-text-opacity, 1));
}

.hover\:text-warning:hover{
  --tw-text-opacity: 1;
  color: rgb(255 184 0 / var(--tw-text-opacity, 1));
}

.hover\:text-warning-600:hover{
  --tw-text-opacity: 1;
  color: rgb(230 166 0 / var(--tw-text-opacity, 1));
}

.focus\:border-primary:focus{
  --tw-border-opacity: 1;
  border-color: rgb(0 255 136 / var(--tw-border-opacity, 1));
}

.focus\:outline-none:focus{
  outline: 2px solid transparent;
  outline-offset: 2px;
}

.active\:scale-95:active{
  --tw-scale-x: .95;
  --tw-scale-y: .95;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.peer:checked ~ .peer-checked\:bg-primary{
  --tw-bg-opacity: 1;
  background-color: rgb(0 255 136 / var(--tw-bg-opacity, 1));
}

.peer:checked ~ .peer-checked\:after\:translate-x-full::after{
  content: var(--tw-content);
  --tw-translate-x: 100%;
  transform: translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y));
}

.peer:checked ~ .peer-checked\:after\:border-white::after{
  content: var(--tw-content);
  --tw-border-opacity: 1;
  border-color: rgb(255 255 255 / var(--tw-border-opacity, 1));
}

.peer:focus ~ .peer-focus\:outline-none{
  outline: 2px solid transparent;
  outline-offset: 2px;
}

@media (min-width: 640px){
  .sm\:flex-row{
    flex-direction: row;
  }
}

@media (min-width: 768px){
  .md\:flex{
    display: flex;
  }

  .md\:hidden{
    display: none;
  }

  .md\:grid-cols-2{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .md\:grid-cols-3{
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .md\:grid-cols-4{
    grid-template-columns: repeat(4, minmax(0, 1fr));
  }

  .md\:flex-row{
    flex-direction: row;
  }

  .md\:items-center{
    align-items: center;
  }

  .md\:text-5xl{
    font-size: 3rem;
    line-height: 1;
  }
}

@media (min-width: 1024px){
  .lg\:col-span-2{
    grid-column: span 2 / span 2;
  }

  .lg\:w-80{
    width: 20rem;
  }

  .lg\:grid-cols-2{
    grid-template-columns: repeat(2, minmax(0, 1fr));
  }

  .lg\:grid-cols-3{
    grid-template-columns: repeat(3, minmax(0, 1fr));
  }

  .lg\:flex-row{
    flex-direction: row;
  }
}
