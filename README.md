# Roam Setup
How I like my Roam. Basically [Roam Research Dark by Daniel](https://github.com/vandermerwed/Roam-Research-Dark) with a stripped down pure CSS approach.

## Installation
Paste the below in a code block (with language set as CSS) to a Roam page called `roam/css`

```css
/* change body font */
body,
html,
div,
textarea {
  font-family: Arial, Helvetica, sans-serif;
}
.kanban-card {
  color: white;
  background-color: rgba(10, 10, 10, 0.25) !important;
}
.kanban-board {
  background-color: #1e272e !important;
}
.kanban-column {
  background-color: rgba(56, 64, 71, 0.8) !important;
}
.kanban-title {
  color: rgba(255, 152, 0, 1);
  font-weight: bold;
}

#right-sidebar .rm-reference-main {
  padding-right: 5px;
}

/* change font for headings */
#right-sidebar .rm-level2,
.rm-reference-main .rm-level3,
.roam-log-preview h1,
h1.rm-title-display,
h1.rm-title-display textarea,
.level1,
.level2 {
  font-family: Menlo, monospace;
  font-weight: 300 !important;
  letter-spacing: -0.08em;
  color: #d5d6d7 !important;
}

h1,
h1 div,
h1 textarea,
.rm-level1 textarea,
.rm-level1 div {
  font-family: Menlo, monospace;
  font-weight: 600 !important;
  color: color-heading-1 !important;
}

h2,
h2 div,
h2 textarea {
  font-family: Menlo, monospace;
  font-weight: 600 !important;
  color: color-heading-2 !important;
}

h3,
h3 div,
h3 textarea {
  font-family: Menlo, monospace;
  font-weight: 600 !important;
  color: color-heading-3 !important;
}

.mobile > .roam-app > .flex-h-box > .roam-main > .roam-body-main > .rm-article-wrapper {
  font-size: 1.1em;
  line-height: 1.4em;
}

/* ### UI Changes ###*/
/* less space below page heading */
.roam-body .roam-app .roam-main .roam-article .rm-title-display {
  margin-bottom: 10px;
}

/* wide content layout */
.roam-center div:first-child {
  padding-right: calc((100% - 900px) / 2) !important;
}

.roam-block-container {
  max-width: calc(1024px - 80px);
}

.roam-center .roam-article .rm-block-text {
  max-width: 680px;
}

#right-sidebar #roam-right-sidebar-content .rm-block-text {
  max-width: 680px;
}

/* ### RIGHT SIDE BAR ### */
#right-sidebar {
  background-color: rgb(43, 52, 59) !important;
}

/* ### LEFT SIDE BAR ### */
.roam-sidebar-content .log-button:hover {
  background-color: #1e272e !important;
}

.starred-pages-wrapper .starred-pages .page:hover {
  background-color: #1e272e !important;
}

.rm-graph-dropdown .menu-title {
  color: #CED9E0 !important;
}

.rm-graph-dropdown a {
  color: #8A9BA8;
}

.rm-graph-dropdown .setting a {
  color: #182026;
}

/* more subtle logo */
#roam-sidebar-logo img {
  opacity: 0.1;
}

#roam-sidebar-logo span {
  display: none;
}

/* Hide "SHORTCUTS" heading */
.starred-pages-wrapper .flex-h-box {
  display: none;
}
.starred-pages-wrapper .flex-h-box > div:first-child {
  margin: 0 -18px;
}

/* ### All Pages View ### */
.rm-pages-row {
  background-color: #1e272e !important;
  border-bottom: 1px solid #2F3336 !important;
}
.rm-pages-title-col > .bp3-text-overflow-ellipsis > a {
  color: #d5d6d7 !important;
}
.rm-pages-title-col > .bp3-text-overflow-ellipsis > span {
  color: #abaeb0 !important;
}

/* ### EDITOR ### */
/* Tone tweets down a tad */
.twitter-tweet.twitter-tweet-rendered {
  transition: opacity .25s ease-in-out;
  opacity: 0.8;
}

/* Fix vertical line on left of bullets */
.roam-block-container {
  border-radius: 0px;
}

/* tone down color of lines between bullets */
.block-border-left {
  border-left: 1px solid rgba(255, 255, 255, 0.25);
}

.roam-body-main,
body {
  background-color: #1e272e;
}
.roam-topbar {
  background-color: #1e272e;
}
.roam-sidebar-container {
  background-color: #2b343b !important;
  background-color: rgb(43, 52, 59) !important;
}
.roam-body .roam-app {
  color: #d5d6d7;
}
.rm-reference-item {
  background-color: #121212;
  background-color: rgba(43, 52, 59, .9);
}
.rm-title-display {
  color: #FFFFFF;
  color: rgba(255, 255, 255, .87);
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button {
  color: #d5d6d7;
  font-size: 12.5px;
  line-height: 1;
  text-transform: initial;
}
.starred-pages-wrapper > .flex-h-box span {
  color: #d5d6d7;
  font-size: 12.5px !important;
  font-weight: bold;
  margin-bottom: 8px;
}
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page {
  text-decoration: none;
  cursor: pointer;
  font-size: 12.5px;
  padding: 8px 0px 8px 4px;
  color: #abaeb0;
}

/* add some more margin below linked references*/
.roam-article .rm-reference-main .rm-reference-container {
  margin-bottom: 20px;
}

.rm-page-ref-brackets {
  color: #a7b6c2 !important;
}

.rm-page-ref-link-color,
a {
  color: rgba(255, 152, 0, 1.0);

}
a:focus,
a:hover {
  color: rgba(255, 152, 0, 0.7);
}
.rm-page-ref-namespace-color {
  color: rgba(255, 152, 0, 1);
}
.rm-page-ref-tag {
  border-radius: 3px;
  padding: 2px 3px 2px 3px;
  background-color: rgba(255, 152, 0, 0.1);
  color: rgba(255, 152, 0, 1.0);
}

/* Highlights */
.block-highlight-blue {
  background-color: rgba(255, 152, 0, 0.2);
}
.block-highlight-yellow {
  background-color: rgba(121, 85, 72, .60);
}
.roam-highlight {
  background-color: #263139;
  border-radius: 2px;
  padding: 1px 3px 2px 3px;
  background-color: rgba(255, 152, 0, .4);
}

/* Diagrams */
.roam-block-container button {
  background-color: rgba(56, 64, 71, 0.8) !important;
  border: none;
  border-radius: 3px;
  outline: none;
  margin-bottom: 3px;
}


svg[style*="background-color: rgb(86\, 112\, 134);"],
div[style*="border: 1px solid lightgrey;"] {
  background-color: rgba(10, 10, 10, 0.2) !important;
  border-color: #2b343b !important;
}

rect[stroke*="lightgrey"] {
  stroke: #2b343b !important;
  fill: #2b343b !important;
}

/* diagram drag state */
rect[stroke*="red"] {
  stroke: rgba(10, 10, 10, 0.2) !important;
  fill: rgba(10, 10, 10, 0.2) !important;
}

svg .rm-page-ref-link-color {
  color: rgba(255, 152, 0, 1.0);
}
svg .rm-page-ref-brackets {
  color: #a7b6c2;
}

/* Code */
code {
  background: #121212;
  background: rgba(18, 18, 18, 0.60);
  color: #ff5722;
  border: 1px solid #000000;
  border: 1px solid rgba(18, 18, 18, 0.87);
}

/* Blocks */
.roam-block > span > div:not(.slider):not(.roam-table) {
  background: rgba(255, 255, 255, 0.05) !important;
}
.roam-block .rm-block-ref {
  border: none;
  background-color: transparent !important;
}
.rm-block-ref:hover {
  background-color: transparent !important;
  border-bottom: 1px solid rgba(255, 152, 0, 1.0);
}

/* versioning widget */
.version-bullet {
  font-size: 12px;
  background-color: rgb(255, 152, 0) !important;
}

/* slider widget */
.slider {
  max-width: 250px !important;
}
.bp3-slider-progress.bp3-intent-primary {
  background-color: rgb(255, 152, 0) !important;
}

.rm-block-text strong {
  color: rgba(255, 152, 0, 1);
}

/* term select */
.rm-block-text select {
  background-color: rgb(43, 52, 59) !important;
  border: none;
}

/* alias styling */
.rm-block-text span[style*="cursor: alias;"] {
  color: rgb(255, 152, 0) !important;
  background-color: rgb(43, 52, 59) !important;
}

/* sync quick capture styling */
.rm-quick-capture-sync-modal {
  background-color: rgb(43, 52, 59) !important;
}

/* Elements */
.bp3-input {
  background: #FFFFFF;
  background: rgba(255, 255, 255, .05);
  color: #d9d9d9 !important;
}

.bp3-elevation-3 {
  background-color: rgb(43, 52, 59) !important;
  box-shadow: 0 2px 16px 0 rgba(0, 0, 0, .4);
  color: #5C7080 !important;
  /* Style highlighted item in '/' menu */
  div.dont-unfocus-block {
    &:hover,
    &:focus,
    &:active {
      background-color: #1e272e !important;
    }
  }
}
.bp3-datepicker {
  background-color: rgb(43, 52, 59) !important;
  color: #fff !important
}
.bp3-popover {
  box-shadow: 0 2px 16px 0 rgba(0, 0, 0, .4);
}
.bp3-popover-content {
  background-color: #384047 !important;
  color: #5C7080 !important;
}
.bp3-popover-arrow-fill {
  fill: rgb(43, 52, 59) !important;
}
.bp3-popover-arrow-border {
  fill: rgb(255, 255, 255) !important;
}
.bp3-dialog {
  background-color: rgb(43, 52, 59) !important;
  box-shadow: 0 2px 16px 0 rgba(0, 0, 0, .4);
  color: #5C7080 !important;
}
.bp3-dialog textarea {
  color: #d9d9d9 !important;
  background-color: rgba(56, 64, 71, 0.8) !important;
}
.bp3-menu {
  background-color: rgb(56, 64, 71) !important;
  color: #aeacb0;
}
.bp3-menu-item:hover {
  background-color: #1e272e !important;
}
.bp3-html-select > select {
  color: #fff
}
.bp3-button.bp3-minimal:hover {
  background-color: rgba(56, 64, 71, .4) !important;
}
#buffer {
  bottom: 70px !important;
  right: 18px !important;
}

/* Original below here */

h1.rm-title-display > span
{
  color: #328fe0 !important;
}

.red {
  background-color: rgba(202,61,61,0.53);
}

.rm-page-ref-link-color {
  color: #3f87b3 !important;
}

/* hide bullets */
.simple-bullet-outer.cursor-pointer,
.rm-bullet .rm-bullet__inner{
  opacity: 0;
  color: white !important;
}

.simple-bullet-outer.cursor-pointer:hover {
  opacity: 1;
  background-color: #3f87b3;
}

.controls {
  flex: 0 0 23px;
}

.rm-embed-container--block > .rm-hide-bullet{
  padding-left: 20px !important;
}

/* layout stuff */
.roam-article > div:last-child {
  margin-top: 4em !important;
  border-top: 1px solid;
}

.roam-center > div#buffer {
  bottom: 5px !important;
  right: 5px !important;
}

#intercom-container, .intercom-lightweight-app-launcher, .intercom-launcher {
  display: none !important;
}
```
