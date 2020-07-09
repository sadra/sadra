### Hi there 👋

<!DOCTYPE html>
<!-- saved from url=(0031)https://rscard.px-lab.com/html/ -->
<html
  lang="en"
  class="theme-color-07cb79 theme-skin-light cssall cssgradients rgba opacity supports textshadow cssanimations bgrepeatround bgrepeatspace boxshadow csstransforms csstransforms3d csstransitions desktop"
  style=""
>
  <head>

	<style>
		/**
 * Table of Contents:
 *
 * 1.0 - Reset
 * 2.0 - General
 *   2.1 - Typography
 *   2.2 - Elements
 *   2.3 - Helper Classes
 *   2.4 - Icons
 * 3.0 - Form
 * 4.0 - Grid
 * 5.0 - WP Editor
 *   5.1 - Alignments
 *   5.2 - Caption
 *   5.3 - Galleries
 * 6.0 - Components
 *   6.1 - Buttons
 *   6.2 - Ripple
 *   6.3 - Social
 *   6.4 - Pagination
 *   6.5 - Custom Scroll
 *   6.6 - Video & Audio Player
 *   6.7 - Scroll Animations
 * 7.0 - Containers
 * 8.0 - Preloader/Overlay
 * 9.0 - Header
 *    9.1 - Logo
 *    9.2 - Navigation
 *    9.3 - Mobile Navigation
 *    9.4 - Header With BgImage
 *    9.5 - Header Sticky
 * 10.0 - Sidebar
 *    10.1 - Sidebar Fixed
 *    10.2 - Widgets
 *    10.3 - No Sidebar
 * 11.0 - Home
 *    11.1 - Section Text
 *    11.2 - Section About
 *    11.3 - Section Skills
 *    11.4 - Section Interests
 *    11.5 - Section Portfolio
 *    11.6 - Section Timeline
 *    11.7 - Section References
 *    11.8 - Section Calendar
 *    11.9 - Section Contact
 *    11.10 - Section Prices
 *    11.11 - Section Clients
 * 12.0 - Blog
 *    12.1 - Blog General
 *    12.2 - Blog Post Box
 *    12.3 - Post Page
 *    12.4 - Post Comments
 * 13.0 - Error Page
 * 14.0 - Footer
 *
 * 15.0 - Theme dark
 * 16.0 - Old Browsers
 */
/**
 * 1.0 - Reset
 */
html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, font, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td {
  border: 0;
  font-family: inherit;
  font-size: 100%;
  font-style: inherit;
  font-weight: inherit;
  margin: 0;
  outline: 0;
  padding: 0;
  vertical-align: baseline; }

html {
  -webkit-font-smoothing: antialiased;
  -webkit-text-size-adjust: 100%;
  -ms-text-size-adjust: 100%; }

*,
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box; }

*:hover,
*:focus,
*:active {
  outline: 0; }

* {
  -webkit-tap-highlight-color: transparent; }

article,
aside,
details,
figcaption,
figure,
footer,
header,
main,
nav,
section {
  display: block; }

ol,
ul {
  list-style: none; }

table {
  border-collapse: separate;
  border-spacing: 0; }

caption,
th,
td {
  font-weight: normal;
  text-align: left; }

blockquote:before,
blockquote:after,
q:before,
q:after {
  content: ""; }

blockquote,
q {
  -webkit-hyphens: none;
  -moz-hyphens: none;
  -ms-hyphens: none;
  hyphens: none;
  quotes: none; }

a img {
  border: 0; }

a {
  cursor: pointer;
  text-decoration: none;
  -ms-word-break: break-all;
  word-break: break-word;
  word-wrap: break-word; }

a:hover {
  text-decoration: underline; }

/**
 * 2.0 - General
 */
/**
 * 2.1 - Typography
 */
h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: 400;
  font-family: "Open Sans", sans-serif;
  margin: 0 0 25px 0;
  line-height: 1.1; }

h1:first-child,
h2:first-child,
h3:first-child,
h4:first-child,
h5:first-child,
h6:first-child {
  margin-top: 0; }

h1 {
  font-size: 36px; }

h2 {
  font-size: 26px; }

h3 {
  font-size: 24px; }

h4 {
  font-size: 22px; }

h5 {
  font-size: 18px; }

h6 {
  font-size: 16px; }

p {
  margin: 0 0 25px 0; }

b,
strong {
  font-weight: 700; }

dfn,
cite,
em,
i {
  font-style: italic; }

blockquote {
  color: #737881;
  font-size: 18px;
  font-weight: 300;
  line-height: 30px;
  text-align: center;
  position: relative;
  margin: 0 0 20px 0; }

blockquote:before {
  content: '\e61c';
  position: static;
  display: block;
  text-align: center;
  font-size: 20px;
  line-height: 1;
  margin-bottom: 10px; }

blockquote p {
  margin-bottom: 20px; }

blockquote > p:last-child {
  margin-bottom: 0; }

blockquote cite {
  padding-top: 20px;
  margin-top: 25px;
  position: relative;
  display: block; }

blockquote cite:before {
  content: '';
  width: 64px;
  height: 1px;
  background-color: #bfbfbf;
  position: absolute;
  left: 50%;
  top: 0;
  margin-left: -32px; }

blockquote cite,
blockquote small {
  color: #303030;
  font-size: 14px;
  font-weight: 600; }

blockquote em,
blockquote i,
blockquote cite {
  font-style: normal; }

address {
  font-style: italic;
  margin: 0 0 1.6em; }

code,
kbd,
tt,
var,
samp,
pre {
  font-family: Inconsolata, monospace;
  -webkit-hyphens: none;
  -moz-hyphens: none;
  -ms-hyphens: none;
  hyphens: none; }

pre {
  background-color: transparent;
  background-color: rgba(0, 0, 0, 0.01);
  border: 1px solid #eaeaea;
  border: 1px solid rgba(51, 51, 51, 0.1);
  line-height: 1.2;
  margin-bottom: 1.6em;
  max-width: 100%;
  overflow: auto;
  padding: 0.8em;
  white-space: pre-wrap;
  word-wrap: break-word; }

abbr[title] {
  border-bottom: 1px dotted #eaeaea;
  border-bottom: 1px dotted rgba(51, 51, 51, 0.1);
  cursor: help; }

mark,
ins {
  text-decoration: none; }

sup,
sub {
  font-size: 75%;
  height: 0;
  line-height: 0;
  position: relative;
  vertical-align: baseline; }

sup {
  bottom: 1ex; }

sub {
  top: .5ex; }

small {
  font-size: 75%; }

big {
  font-size: 125%; }

/**
 * 2.2 - Elements
 */
hr {
  background-color: #bfbfbf;
  border: 0;
  height: 1px;
  margin-top: 0;
  margin-bottom: 25px; }

ul,
ol {
  margin: 0 0 25px 20px; }

ul {
  list-style: square; }

ol {
  list-style: decimal; }

li > ul,
li > ol {
  margin-bottom: 0; }

dl {
  margin-bottom: 25px; }

dt {
  font-weight: bold; }

dd {
  margin-bottom: 10px; }

table,
th,
td {
  border: 1px solid #e5e5e5; }

table {
  border-collapse: separate;
  border-spacing: 0;
  border-width: 1px 0 0 1px;
  margin: 0 0 25px 0;
  table-layout: fixed;
  width: 100%; }

caption,
th,
td {
  font-weight: normal;
  text-align: left; }

th {
  border-width: 0 1px 1px 0;
  font-weight: 700; }

td {
  border-width: 0 1px 1px 0; }

th, td {
  padding: 5px 10px;
  vertical-align: top; }

img {
  border: 0;
  height: auto;
  max-width: 100%;
  vertical-align: middle; }

figure {
  margin: 0; }

del {
  opacity: 0.5; }

/**
 * 2.3 - Helper Classes
 */
.clearfix:before, .clearfix:after {
  content: " ";
  display: table; }
.clearfix:after {
  clear: both; }
.clearfix {
  *zoom: 1; }

.hidden {
  display: none !important; }

.text-left {
  text-align: left; }

.text-right {
  text-align: right; }

.text-center {
  text-align: center; }

.text-justify {
  text-align: justify; }

.valign-outer {
  width: 100%;
  height: 100%;
  overflow: hidden;
  display: table;
  position: static; }

.valign-middle {
  top: 50%;
  display: table-cell;
  vertical-align: middle;
  width: 100%;
  position: static; }

.valign-inner {
  position: relative;
  top: -50%; }

/**
 * 2.4 - Icons
 */
.rsicon,
blockquote:before,
.ref-box .person-speech:before,
.widget_search .search-form:before {
  display: inline-block;
  vertical-align: middle; }

blockquote:before,
.ref-box .person-speech:before,
.widget_search .search-form:before {
  font-family: 'icomoon';
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; }

/**
 * 3.0 - Form
 */
button,
input[type="submit"] {
  cursor: pointer; }

select,
textarea,
input[type='tel'],
input[type='text'],
input[type='email'],
input[type='search'],
input[type='password'] {
  color: #333;
  font-size: 14px;
  font-weight: 400;
  font-family: "Open Sans", sans-serif;
  line-height: 1.42857143;
  width: 100%;
  display: block;
  padding: 6px 12px;
  background: transparent;
  border: 1px solid #d8d8d8;
  border-radius: 4px; }

select,
input[type='tel'],
input[type='text'],
input[type='email'],
input[type='search'],
input[type='password'] {
  height: 34px; }

textarea {
  resize: none; }

::-webkit-input-placeholder {
  color: #333; }

:-moz-placeholder {
  color: #333; }

::-moz-placeholder {
  color: #333;
  opacity: 1; }

:-ms-input-placeholder {
  color: #333; }

.input-field {
  position: relative;
  margin-bottom: 30px; }

.input-field input,
.input-field textarea {
  font-size: 16px;
  line-height: 16px;
  padding: 10px 0;
  display: block;
  width: 100%;
  border: none;
  border-bottom: 1px solid #d8d8d8;
  border-radius: 0; }

.input-field label {
  top: 10px;
  left: 0;
  color: #333;
  font-size: 14px;
  line-height: 14px;
  font-weight: 400;
  text-transform: uppercase;
  position: absolute;
  pointer-events: none;
  -webkit-transition: 0.15s ease all;
  -moz-transition: 0.15s ease all;
  transition: 0.15s ease all; }

.input-field .line {
  position: relative;
  display: block;
  width: 100%; }

.input-field .line:before,
.input-field .line:after {
  content: '';
  height: 2px;
  width: 0;
  bottom: 0;
  position: absolute;
  -webkit-transition: 0.15s ease all;
  -moz-transition: 0.15s ease all;
  transition: 0.15s ease all; }

.input-field .line:before {
  left: 50%; }

.input-field .line:after {
  right: 50%; }

.input-field input:focus,
.input-field textarea:focus {
  outline: none; }

.input-field.used label {
  top: -15px;
  font-size: 11px; }

.input-field.used .line:before,
.input-field.used .line:after {
  width: 50%; }

.input-field.error label {
  color: #c00 !important; }
.input-field.error input, .input-field.error textarea {
  border-bottom: 1px solid #c00 !important; }
.input-field.error .line:before,
.input-field.error .line:after {
  background-color: #c00 !important; }

/**
 * 4.0 - Grid
 */
.row {
  margin-left: -15px;
  margin-right: -15px; }
  .row:before, .row:after {
    content: " ";
    display: table; }
  .row:after {
    clear: both; }
  .row {
    *zoom: 1; }

.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 15px;
  padding-right: 15px; }

.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left; }

.col-xs-1 {
  width: 8.33333%; }

.col-xs-2 {
  width: 16.66667%; }

.col-xs-3 {
  width: 25%; }

.col-xs-4 {
  width: 33.33333%; }

.col-xs-5 {
  width: 41.66667%; }

.col-xs-6 {
  width: 50%; }

.col-xs-7 {
  width: 58.33333%; }

.col-xs-8 {
  width: 66.66667%; }

.col-xs-9 {
  width: 75%; }

.col-xs-10 {
  width: 83.33333%; }

.col-xs-11 {
  width: 91.66667%; }

.col-xs-12 {
  width: 100%; }

.col-xs-pull-0 {
  right: auto; }

.col-xs-pull-1 {
  right: 8.33333%; }

.col-xs-pull-2 {
  right: 16.66667%; }

.col-xs-pull-3 {
  right: 25%; }

.col-xs-pull-4 {
  right: 33.33333%; }

.col-xs-pull-5 {
  right: 41.66667%; }

.col-xs-pull-6 {
  right: 50%; }

.col-xs-pull-7 {
  right: 58.33333%; }

.col-xs-pull-8 {
  right: 66.66667%; }

.col-xs-pull-9 {
  right: 75%; }

.col-xs-pull-10 {
  right: 83.33333%; }

.col-xs-pull-11 {
  right: 91.66667%; }

.col-xs-pull-12 {
  right: 100%; }

.col-xs-push-0 {
  left: auto; }

.col-xs-push-1 {
  left: 8.33333%; }

.col-xs-push-2 {
  left: 16.66667%; }

.col-xs-push-3 {
  left: 25%; }

.col-xs-push-4 {
  left: 33.33333%; }

.col-xs-push-5 {
  left: 41.66667%; }

.col-xs-push-6 {
  left: 50%; }

.col-xs-push-7 {
  left: 58.33333%; }

.col-xs-push-8 {
  left: 66.66667%; }

.col-xs-push-9 {
  left: 75%; }

.col-xs-push-10 {
  left: 83.33333%; }

.col-xs-push-11 {
  left: 91.66667%; }

.col-xs-push-12 {
  left: 100%; }

.col-xs-offset-0 {
  margin-left: 0%; }

.col-xs-offset-1 {
  margin-left: 8.33333%; }

.col-xs-offset-2 {
  margin-left: 16.66667%; }

.col-xs-offset-3 {
  margin-left: 25%; }

.col-xs-offset-4 {
  margin-left: 33.33333%; }

.col-xs-offset-5 {
  margin-left: 41.66667%; }

.col-xs-offset-6 {
  margin-left: 50%; }

.col-xs-offset-7 {
  margin-left: 58.33333%; }

.col-xs-offset-8 {
  margin-left: 66.66667%; }

.col-xs-offset-9 {
  margin-left: 75%; }

.col-xs-offset-10 {
  margin-left: 83.33333%; }

.col-xs-offset-11 {
  margin-left: 91.66667%; }

.col-xs-offset-12 {
  margin-left: 100%; }

@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left; }

  .col-sm-1 {
    width: 8.33333%; }

  .col-sm-2 {
    width: 16.66667%; }

  .col-sm-3 {
    width: 25%; }

  .col-sm-4 {
    width: 33.33333%; }

  .col-sm-5 {
    width: 41.66667%; }

  .col-sm-6 {
    width: 50%; }

  .col-sm-7 {
    width: 58.33333%; }

  .col-sm-8 {
    width: 66.66667%; }

  .col-sm-9 {
    width: 75%; }

  .col-sm-10 {
    width: 83.33333%; }

  .col-sm-11 {
    width: 91.66667%; }

  .col-sm-12 {
    width: 100%; }

  .col-sm-pull-0 {
    right: auto; }

  .col-sm-pull-1 {
    right: 8.33333%; }

  .col-sm-pull-2 {
    right: 16.66667%; }

  .col-sm-pull-3 {
    right: 25%; }

  .col-sm-pull-4 {
    right: 33.33333%; }

  .col-sm-pull-5 {
    right: 41.66667%; }

  .col-sm-pull-6 {
    right: 50%; }

  .col-sm-pull-7 {
    right: 58.33333%; }

  .col-sm-pull-8 {
    right: 66.66667%; }

  .col-sm-pull-9 {
    right: 75%; }

  .col-sm-pull-10 {
    right: 83.33333%; }

  .col-sm-pull-11 {
    right: 91.66667%; }

  .col-sm-pull-12 {
    right: 100%; }

  .col-sm-push-0 {
    left: auto; }

  .col-sm-push-1 {
    left: 8.33333%; }

  .col-sm-push-2 {
    left: 16.66667%; }

  .col-sm-push-3 {
    left: 25%; }

  .col-sm-push-4 {
    left: 33.33333%; }

  .col-sm-push-5 {
    left: 41.66667%; }

  .col-sm-push-6 {
    left: 50%; }

  .col-sm-push-7 {
    left: 58.33333%; }

  .col-sm-push-8 {
    left: 66.66667%; }

  .col-sm-push-9 {
    left: 75%; }

  .col-sm-push-10 {
    left: 83.33333%; }

  .col-sm-push-11 {
    left: 91.66667%; }

  .col-sm-push-12 {
    left: 100%; }

  .col-sm-offset-0 {
    margin-left: 0%; }

  .col-sm-offset-1 {
    margin-left: 8.33333%; }

  .col-sm-offset-2 {
    margin-left: 16.66667%; }

  .col-sm-offset-3 {
    margin-left: 25%; }

  .col-sm-offset-4 {
    margin-left: 33.33333%; }

  .col-sm-offset-5 {
    margin-left: 41.66667%; }

  .col-sm-offset-6 {
    margin-left: 50%; }

  .col-sm-offset-7 {
    margin-left: 58.33333%; }

  .col-sm-offset-8 {
    margin-left: 66.66667%; }

  .col-sm-offset-9 {
    margin-left: 75%; }

  .col-sm-offset-10 {
    margin-left: 83.33333%; }

  .col-sm-offset-11 {
    margin-left: 91.66667%; }

  .col-sm-offset-12 {
    margin-left: 100%; } }
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left; }

  .col-md-1 {
    width: 8.33333%; }

  .col-md-2 {
    width: 16.66667%; }

  .col-md-3 {
    width: 25%; }

  .col-md-4 {
    width: 33.33333%; }

  .col-md-5 {
    width: 41.66667%; }

  .col-md-6 {
    width: 50%; }

  .col-md-7 {
    width: 58.33333%; }

  .col-md-8 {
    width: 66.66667%; }

  .col-md-9 {
    width: 75%; }

  .col-md-10 {
    width: 83.33333%; }

  .col-md-11 {
    width: 91.66667%; }

  .col-md-12 {
    width: 100%; }

  .col-md-pull-0 {
    right: auto; }

  .col-md-pull-1 {
    right: 8.33333%; }

  .col-md-pull-2 {
    right: 16.66667%; }

  .col-md-pull-3 {
    right: 25%; }

  .col-md-pull-4 {
    right: 33.33333%; }

  .col-md-pull-5 {
    right: 41.66667%; }

  .col-md-pull-6 {
    right: 50%; }

  .col-md-pull-7 {
    right: 58.33333%; }

  .col-md-pull-8 {
    right: 66.66667%; }

  .col-md-pull-9 {
    right: 75%; }

  .col-md-pull-10 {
    right: 83.33333%; }

  .col-md-pull-11 {
    right: 91.66667%; }

  .col-md-pull-12 {
    right: 100%; }

  .col-md-push-0 {
    left: auto; }

  .col-md-push-1 {
    left: 8.33333%; }

  .col-md-push-2 {
    left: 16.66667%; }

  .col-md-push-3 {
    left: 25%; }

  .col-md-push-4 {
    left: 33.33333%; }

  .col-md-push-5 {
    left: 41.66667%; }

  .col-md-push-6 {
    left: 50%; }

  .col-md-push-7 {
    left: 58.33333%; }

  .col-md-push-8 {
    left: 66.66667%; }

  .col-md-push-9 {
    left: 75%; }

  .col-md-push-10 {
    left: 83.33333%; }

  .col-md-push-11 {
    left: 91.66667%; }

  .col-md-push-12 {
    left: 100%; }

  .col-md-offset-0 {
    margin-left: 0%; }

  .col-md-offset-1 {
    margin-left: 8.33333%; }

  .col-md-offset-2 {
    margin-left: 16.66667%; }

  .col-md-offset-3 {
    margin-left: 25%; }

  .col-md-offset-4 {
    margin-left: 33.33333%; }

  .col-md-offset-5 {
    margin-left: 41.66667%; }

  .col-md-offset-6 {
    margin-left: 50%; }

  .col-md-offset-7 {
    margin-left: 58.33333%; }

  .col-md-offset-8 {
    margin-left: 66.66667%; }

  .col-md-offset-9 {
    margin-left: 75%; }

  .col-md-offset-10 {
    margin-left: 83.33333%; }

  .col-md-offset-11 {
    margin-left: 91.66667%; }

  .col-md-offset-12 {
    margin-left: 100%; } }
@media (min-width: 1025px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left; }

  .col-lg-1 {
    width: 8.33333%; }

  .col-lg-2 {
    width: 16.66667%; }

  .col-lg-3 {
    width: 25%; }

  .col-lg-4 {
    width: 33.33333%; }

  .col-lg-5 {
    width: 41.66667%; }

  .col-lg-6 {
    width: 50%; }

  .col-lg-7 {
    width: 58.33333%; }

  .col-lg-8 {
    width: 66.66667%; }

  .col-lg-9 {
    width: 75%; }

  .col-lg-10 {
    width: 83.33333%; }

  .col-lg-11 {
    width: 91.66667%; }

  .col-lg-12 {
    width: 100%; }

  .col-lg-pull-0 {
    right: auto; }

  .col-lg-pull-1 {
    right: 8.33333%; }

  .col-lg-pull-2 {
    right: 16.66667%; }

  .col-lg-pull-3 {
    right: 25%; }

  .col-lg-pull-4 {
    right: 33.33333%; }

  .col-lg-pull-5 {
    right: 41.66667%; }

  .col-lg-pull-6 {
    right: 50%; }

  .col-lg-pull-7 {
    right: 58.33333%; }

  .col-lg-pull-8 {
    right: 66.66667%; }

  .col-lg-pull-9 {
    right: 75%; }

  .col-lg-pull-10 {
    right: 83.33333%; }

  .col-lg-pull-11 {
    right: 91.66667%; }

  .col-lg-pull-12 {
    right: 100%; }

  .col-lg-push-0 {
    left: auto; }

  .col-lg-push-1 {
    left: 8.33333%; }

  .col-lg-push-2 {
    left: 16.66667%; }

  .col-lg-push-3 {
    left: 25%; }

  .col-lg-push-4 {
    left: 33.33333%; }

  .col-lg-push-5 {
    left: 41.66667%; }

  .col-lg-push-6 {
    left: 50%; }

  .col-lg-push-7 {
    left: 58.33333%; }

  .col-lg-push-8 {
    left: 66.66667%; }

  .col-lg-push-9 {
    left: 75%; }

  .col-lg-push-10 {
    left: 83.33333%; }

  .col-lg-push-11 {
    left: 91.66667%; }

  .col-lg-push-12 {
    left: 100%; }

  .col-lg-offset-0 {
    margin-left: 0%; }

  .col-lg-offset-1 {
    margin-left: 8.33333%; }

  .col-lg-offset-2 {
    margin-left: 16.66667%; }

  .col-lg-offset-3 {
    margin-left: 25%; }

  .col-lg-offset-4 {
    margin-left: 33.33333%; }

  .col-lg-offset-5 {
    margin-left: 41.66667%; }

  .col-lg-offset-6 {
    margin-left: 50%; }

  .col-lg-offset-7 {
    margin-left: 58.33333%; }

  .col-lg-offset-8 {
    margin-left: 66.66667%; }

  .col-lg-offset-9 {
    margin-left: 75%; }

  .col-lg-offset-10 {
    margin-left: 83.33333%; }

  .col-lg-offset-11 {
    margin-left: 91.66667%; }

  .col-lg-offset-12 {
    margin-left: 100%; } }
/**
 * 5.0 - WP Editor
 */
/**
 * 5.1 - Alignments
 */
.alignleft {
  display: inline;
  float: left; }

.alignright {
  display: inline;
  float: right; }

.aligncenter {
  display: block;
  margin-right: auto;
  margin-left: auto; }

blockquote.alignleft,
.wp-caption.alignleft,
img.alignleft {
  margin: 0.4em 1.6em 1.6em 0; }

blockquote.alignright,
.wp-caption.alignright,
img.alignright {
  margin: 0.4em 0 1.6em 1.6em; }

blockquote.aligncenter,
.wp-caption.aligncenter,
img.aligncenter {
  clear: both;
  margin-top: 0.4em;
  margin-bottom: 1.6em; }

.wp-caption.alignleft,
.wp-caption.alignright,
.wp-caption.aligncenter {
  margin-bottom: 1.2em; }

/**
 * 5.2 - Caption
 */
.wp-caption {
  background: transparent;
  border: none;
  color: #707070;
  font-family: "Noto Sans", sans-serif;
  margin: 0 0 28px 0;
  max-width: 100%;
  padding: 0;
  text-align: inherit; }

.wp-caption.alignleft {
  margin: 7px 28px 21px 0; }

.wp-caption.alignright {
  margin: 7px 0 21px 28px; }

.wp-caption.aligncenter {
  margin: 7px auto; }

.wp-caption .wp-caption-text,
.wp-caption-dd {
  color: #9a9a9a;
  font-size: 13px;
  line-height: 1.1;
  padding: 10px 0;
  text-align: center; }

/**
 * 5.3 -  Galleries
 */
.gallery {
  margin-bottom: 1.6em; }

.gallery-item {
  display: inline-block;
  padding: 1.79104477%;
  text-align: center;
  vertical-align: top;
  width: 100%; }

.gallery-columns-2 .gallery-item {
  max-width: 50%; }

.gallery-columns-3 .gallery-item {
  max-width: 33.33%; }

.gallery-columns-4 .gallery-item {
  max-width: 25%; }

.gallery-columns-5 .gallery-item {
  max-width: 20%; }

.gallery-columns-6 .gallery-item {
  max-width: 16.66%; }

.gallery-columns-7 .gallery-item {
  max-width: 14.28%; }

.gallery-columns-8 .gallery-item {
  max-width: 12.5%; }

.gallery-columns-9 .gallery-item {
  max-width: 11.11%; }

.gallery-icon img {
  margin: 0 auto; }

.gallery-caption {
  color: #707070;
  color: rgba(51, 51, 51, 0.7);
  display: block;
  font-family: "Noto Sans", sans-serif;
  font-size: 12px;
  line-height: 1.5;
  padding: 0.5em 0; }

.gallery-columns-6 .gallery-caption,
.gallery-columns-7 .gallery-caption,
.gallery-columns-8 .gallery-caption,
.gallery-columns-9 .gallery-caption {
  display: none; }

/**
 * 6.0 - Components
 */
/**
 * 6.1 - Buttons
 */
.btn {
  font-size: 14px;
  font-weight: 400;
  font-family: "Open Sans", sans-serif;
  line-height: 1;
  text-align: center;
  vertical-align: middle;
  display: inline-block;
  border: none;
  cursor: pointer;
  padding: 6px 12px;
  margin-bottom: 0;
  background-image: none; }

.btn,
.btn-outer {
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  -webkit-user-select: none;
  -moz-user-select: none;
  user-select: none;
  -webkit-transition: all 0.3s ease-out;
  -moz-transition: all 0.3s ease-out;
  transition: all 0.3s ease-out;
  box-shadow: 0 0px 5px rgba(0, 0, 0, 0.2), 0 2px 5px rgba(0, 0, 0, 0.17); }

.btn-outer .btn {
  box-shadow: none; }

.btn:hover,
.btn:focus,
.btn-outer:hover,
.btn-outer:focus {
  opacity: 0.95;
  text-decoration: none;
  box-shadow: 0 5px 11px 0 rgba(0, 0, 0, 0.18), 0 4px 15px 0 rgba(0, 0, 0, 0.15); }

.btn-outer {
  display: inline-block; }

.btn-outer .btn {
  background: transparent !important; }

.btn-outer:hover .btn,
.btn-outer:focus .btn {
  opacity: 1;
  box-shadow: none; }

.btn-lg {
  font-size: 14px;
  font-weight: 700;
  text-transform: uppercase;
  padding: 15px 20px;
  min-width: 130px; }

.btn-border {
  font-size: 14px;
  font-weight: 700;
  line-height: 1;
  text-transform: uppercase;
  color: #3d4451 !important;
  border: 1px solid #cbcdcf;
  background: transparent;
  box-shadow: none; }

.btn-primary {
  color: #fff; }

.btn-scroll-top {
  z-index: 10;
  bottom: 35px;
  right: 40px;
  position: fixed;
  width: 40px;
  height: 40px;
  display: none;
  text-align: center;
  text-decoration: none;
  border: 1px solid #d2d2d2;
  border: 1px solid rgba(0, 0, 0, 0.1);
  background-color: rgba(0, 0, 0, 0.02);
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%;
  -webkit-transition: all 0.3s ease-out;
  -moz-transition: all 0.3s ease-out;
  transition: all 0.3s ease-out; }
  .btn-scroll-top:hover {
    background-color: #fff;
    box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }
  .btn-scroll-top .rsicon {
    color: #c8c8c8;
    color: rgba(0, 0, 0, 0.2);
    font-size: 15px;
    font-weight: bold;
    line-height: 38px; }

@media (max-width: 1180px) {
  .btn-scroll-top {
    right: 15px;
    bottom: 15px; } }
/**
 * 6.2 - Ripple
 */
.ripple {
  overflow: hidden;
  position: relative;
  user-select: none;
  display: inline-block;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translate3d(0, 0, 0);
  -moz-transform: translate3d(0, 0, 0);
  transform: translate3d(0, 0, 0); }

.ripple-effect {
  margin: 0;
  padding: 0;
  position: absolute;
  user-select: none;
  pointer-events: none;
  background-color: rgba(0, 0, 0, 0.15);
  -webkit-transform: translate3d(-50%, -50%, 0);
  -moz-transform: translate3d(-50%, -50%, 0);
  transform: translate3d(-50%, -50%, 0);
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%; }

/**
 * 6.3 - Social
 */
.social {
  margin: 0;
  padding: 0;
  list-style: none;
  text-align: center; }
  .social li {
    display: inline-block;
    margin: 5px 15px; }
    .social li a {
      width: 45px;
      height: 45px;
      position: relative;
      display: inline-block;
      background-color: transparent;
      -webkit-transition: -webkit-transition, background-color 0.25s linear 0s;
      -moz-transition: -moz-transition, background-color 0.25s linear 0s;
      transition: transition, background-color 0.25s linear 0s;
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      backface-visibility: hidden;
      -webkit-border-radius: 50%;
      -moz-border-radius: 50%;
      border-radius: 50%; }
      .social li a:hover {
        text-decoration: none;
        background-color: rgba(0, 0, 0, 0.1); }
      .social li a, .social li a .rsicon {
        line-height: 45; }
      .social li a .rsicon {
        color: #fff;
        font-size: 20px;
        line-height: 45px;
        display: block; }

@media (max-width: 767px) {
  .social li {
    margin-left: 5px;
    margin-right: 5px; }
    .social li a {
      width: 35px;
      height: 35px; }
      .social li a, .social li a .rsicon {
        line-height: 35px; }
      .social li a .rsicon {
        font-size: 17px; } }
/**
 * 6.4 - Pagination
 */
.pagination {
  margin-top: 30px;
  text-align: center; }
  .pagination .page-numbers {
    color: #444;
    min-width: 35px;
    height: 35px;
    margin: 0 2px;
    padding: 0 3px;
    font-size: 15px;
    font-weight: 600;
    line-height: 35px;
    text-align: center;
    display: inline-block;
    background-color: transparent;
    box-shadow: none;
    -webkit-transition: -webkit-transition, all 0.2s linear 0s;
    -moz-transition: -moz-transition, all 0.2s linear 0s;
    transition: transition, all 0.2s linear 0s;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px; }
    .pagination .page-numbers.current, .pagination .page-numbers.current:hover {
      color: #fff !important;
      box-shadow: none; }
    .pagination .page-numbers.next, .pagination .page-numbers.prev {
      color: #444;
      background-color: transparent; }
      .pagination .page-numbers.next .rsicon, .pagination .page-numbers.prev .rsicon {
        font-size: 20px;
        line-height: 35px; }
    .pagination .page-numbers:hover, .pagination .page-numbers.next:hover, .pagination .page-numbers.prev:hover {
      text-decoration: none;
      background-color: #fff;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.19), 0 6px 10px rgba(0, 0, 0, 0.23); }
    .pagination .page-numbers:active, .pagination .page-numbers.next:active, .pagination .page-numbers.prev:active {
      color: #fff !important; }

/**
 * 6.5 - Custom Scroll
 */
.mCSB_inside > .mCSB_container {
  margin-right: 15px; }

.mCS-dark.mCSB_scrollTools .mCSB_dragger .mCSB_dragger_bar {
  background-color: #3d4451;
  background-color: rgba(61, 68, 81, 0.75); }

.mCS-dark.mCSB_scrollTools .mCSB_dragger:hover .mCSB_dragger_bar {
  background-color: #3d4451;
  background-color: rgba(61, 68, 81, 0.85); }

.mCS-dark.mCSB_scrollTools .mCSB_dragger:active .mCSB_dragger_bar,
.mCS-dark.mCSB_scrollTools .mCSB_dragger.mCSB_dragger_onDrag .mCSB_dragger_bar {
  background-color: #3d4451;
  background-color: rgba(61, 68, 81, 0.9); }

/**
 * 6.6 - Video & Audio Player
 */
.mejs-overlay-loading {
  background: transparent; }

.mejs-container.mejs-video {
  overflow: hidden; }

.mejs-container .mejs-controls {
  height: 40px;
  background: #efefef; }
  .mejs-container .mejs-controls:before, .mejs-container .mejs-controls:after {
    content: '';
    width: 100%;
    height: 1px;
    position: absolute;
    background-color: #dfdfdf; }
  .mejs-container .mejs-controls:before {
    left: 0;
    top: 0; }
  .mejs-container .mejs-controls:after {
    left: 0;
    bottom: 0; }
  .mejs-container .mejs-controls div,
  .mejs-container .mejs-controls a.mejs-horizontal-volume-slider {
    height: 40px; }
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider .mejs-horizontal-volume-current,
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider .mejs-horizontal-volume-total,
  .mejs-container .mejs-controls .mejs-time-rail span,
  .mejs-container .mejs-controls .mejs-time-rail a {
    -webkit-border-radius: 0;
    -moz-border-radius: 0;
    border-radius: 0; }
  .mejs-container .mejs-controls .mejs-button button {
    margin-top: 11px;
    margin-bottom: 11px; }
    .mejs-container .mejs-controls .mejs-button button:focus {
      outline: none; }
  .mejs-container .mejs-controls .mejs-playpause-button {
    width: 35px;
    border-left: 1px solid #dfdfdf;
    border-right: 1px solid #dfdfdf; }
    .mejs-container .mejs-controls .mejs-playpause-button button {
      margin-left: 8px;
      margin-right: 8px; }
  .mejs-container .mejs-controls .mejs-time {
    color: #909090;
    padding: 14px 7px 0; }
  .mejs-container .mejs-controls .mejs-volume-button {
    border-left: 1px solid #dfdfdf; }
  .mejs-container .mejs-controls .mejs-fullscreen-button,
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider {
    float: right;
    border-right: 1px solid #dfdfdf; }
  .mejs-container .mejs-controls .mejs-time-rail {
    padding-top: 11px; }
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-slider,
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-buffering,
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-loaded,
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-current,
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-handle {
      height: 8px; }
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-total {
      background: #3e4452;
      margin-left: 8px;
      margin-right: 8px; }
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-loaded {
      background: #737780; }
    .mejs-container .mejs-controls .mejs-time-rail .mejs-time-float-corner {
      display: none; }
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider .mejs-horizontal-volume-total,
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider .mejs-horizontal-volume-current {
    top: 16px; }
  .mejs-container .mejs-controls .mejs-horizontal-volume-slider .mejs-horizontal-volume-total {
    background: #3d4550; }

/**
 * 6.7 - Scroll Animations
 */
.desktop .animate-down {
  opacity: 0;
  visibility: hidden;
  -webkit-transform: translate(0, -100px);
  -moz-transform: translate(0, -100px);
  transform: translate(0, -100px); }
.desktop .animate-down.animated {
  opacity: 1;
  visibility: visible;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translate(0, 0);
  -moz-transform: translate(0, 0);
  transform: translate(0, 0);
  -webkit-transition: all 400ms ease-out 100ms;
  -moz-transition: all 400ms ease-out 100ms;
  transition: all 400ms ease-out 100ms; }
.desktop .animate-up {
  opacity: 0;
  visibility: hidden;
  -webkit-transform: translate(0, 100px);
  -moz-transform: translate(0, 100px);
  transform: translate(0, 100px); }
.desktop .animate-up.animated {
  opacity: 1;
  visibility: visible;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translate(0, 0);
  -moz-transform: translate(0, 0);
  transform: translate(0, 0);
  -webkit-transition: -webkit-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  -moz-transition: -moz-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  transition: transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms; }
.desktop .animate-right {
  opacity: 0;
  visibility: hidden;
  transform: translate(-100px, 0); }
.desktop .animate-right.animated {
  opacity: 1;
  visibility: visible;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translate(0, 0);
  -moz-transform: translate(0, 0);
  transform: translate(0, 0);
  -webkit-transition: -webkit-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  -moz-transition: -moz-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  transition: transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms; }
.desktop .animate-left {
  opacity: 0;
  visibility: hidden;
  transform: translate(100px, 0); }
.desktop .animate-left.animated {
  opacity: 1;
  visibility: visible;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transform: translate(0, 0);
  -moz-transform: translate(0, 0);
  transform: translate(0, 0);
  -webkit-transition: -webkit-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  -moz-transition: -moz-transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms;
  transition: transform 400ms ease-out 100ms, opacity 400ms ease-out 100ms; }

/**
 * Icons List
 */
.rs-icons-list {
  list-style: none;
  margin: 0 0 25px 0;
  padding: 0; }
  .rs-icons-list li {
    float: left;
    width: 16.6666%;
    float: left;
    height: 150px;
    background-color: rgba(0, 0, 0, 0.1);
    border: 2px solid #fff;
    border-radius: 5px;
    padding: 10px;
    text-align: center; }

.rs-icon {
  font-size: 42px;
  display: block;
  margin-bottom: 5px; }

.rs-icon-class {
  font-size: 11px;
  display: block; }

@media (max-width: 992px) {
  .rs-icons-list li {
    width: 25%; } }
@media (max-width: 767px) {
  .rs-icons-list li {
    width: 33.33%; } }
@media (max-width: 480px) {
  .rs-icons-list li {
    width: 50%; } }
/**
 * 7.0 - Containers
 */
body {
  color: #3d4451;
  font-family: "Open Sans", sans-serif;
  font-size: 16px;
  line-height: 1.5;
  background-color: #efefef; }

.wrapper {
  opacity: 1;
  visibility: visible;
  position: relative;
  overflow: hidden;
  -webkit-transition: opacity 400ms ease-out;
  -moz-transition: opacity 400ms ease-out;
  transition: opacity 400ms ease-out; }

.mobile.lock-scroll, .mobile.lock-scroll body, .mobile.lock-scroll .wrapper {
  height: 100%;
  position: relative;
  overflow: hidden; }

.content {
  z-index: 2;
  position: relative; }

.container {
  width: 100%;
  max-width: 960px;
  padding-left: 10px;
  padding-right: 10px;
  margin: 0 auto; }

.section {
  padding-top: 70px; }

.section-box {
  padding: 40px 50px; }

.section-title {
  color: #3d4451;
  font-size: 34px;
  line-height: 1.2;
  font-weight: 600;
  text-align: center; }

.grid-box,
.post-box,
.price-box,
.section-box,
.calendar-busy,
.timeline-box-inner,
.sidebar-default .profile-photo img {
  background-color: #fff;
  box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }

@media (max-width: 992px) {
  .section-box {
    padding: 50px 40px; } }
@media (max-width: 767px) {
  .section {
    padding-top: 50px; }

  .section-box {
    padding: 30px 20px; }

  .section-title {
    font-size: 30px; } }
/**
 * 8.0 - Preload/Overlay
 */
#overlay {
  position: fixed;
  z-index: 99;
  top: -1000%;
  left: 0;
  right: 0;
  width: 100%;
  height: 100%;
  background-color: #000;
  opacity: 0;
  -webkit-transition: top 0s ease 0.35s, opacity 0.35s ease;
  -moz-transition: top 0s ease 0.35s, opacity 0.35s ease;
  transition: top 0s ease 0.35s, opacity 0.35s ease; }

.loading #preloader {
  display: block; }
.loading .wrapper {
  opacity: 0;
  visibility: hidden; }

#preloader {
  display: none;
  position: fixed;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 9999;
  background: #fff; }
  #preloader .preload-text {
    display: none; }
  #preloader .preload-icon {
    width: 70px;
    height: 70px;
    display: inline-block;
    padding: 0px;
    text-align: left;
    position: absolute;
    left: 50%;
    top: 50%;
    margin-left: -35px;
    margin-top: -35px; }
    #preloader .preload-icon span {
      position: absolute;
      display: inline-block;
      width: 70px;
      height: 70px;
      border-radius: 100%;
      background: #000000;
      -webkit-animation: preloader 1.6s linear infinite;
      -moz-animation: preloader 1.6s linear infinite;
      animation: preloader 1.6s linear infinite; }
    #preloader .preload-icon span:last-child {
      -webkit-animation-delay: -0.8s;
      -moz-animation-delay: -0.8s;
      animation-delay: -0.8s; }

@-webkit-keyframes preloader {
  0% {
    -webkit-transform: scale(0, 0);
    opacity: 0.5; }
  100% {
    -webkit-transform: scale(1, 1);
    opacity: 0; } }
@-moz-keyframes preloader {
  0% {
    -moz-transform: scale(0, 0);
    opacity: 0.5; }
  100% {
    -moz-transform: scale(1, 1);
    opacity: 0; } }
@keyframes preloader {
  0% {
    transform: scale(0, 0);
    opacity: 0.5; }
  100% {
    transform: scale(1, 1);
    opacity: 0; } }
/**
 * 9.0 - Header
 */
.header {
  position: relative;
  margin-bottom: 75px;
  box-sizing: content-box; }

.head-bar {
  z-index: 3;
  opacity: 0;
  position: relative;
  visibility: hidden;
  background-color: #fff;
  padding-top: 10px;
  padding-bottom: 10px;
  -webkit-transform: translate(0, -100px);
  -moz-transform: translate(0, -100px);
  transform: translate(0, -100px);
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden;
  -webkit-transition: -webkit-transform 400ms ease-out 100ms, padding 250ms ease-out, box-shadow 250ms ease-out;
  -moz-transition: -moz-transform 400ms ease-out 100ms, padding 250ms ease-out, box-shadow 250ms ease-out;
  transition: transform 400ms ease-out 100ms, padding 250ms ease-out, box-shadow 250ms ease-out;
  box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }
  .head-bar.animated {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translate(0, 0);
    -moz-transform: translate(0, 0);
    transform: translate(0, 0); }

.head-bar-inner {
  width: 100%;
  max-width: 1550px;
  padding: 10px 15px;
  margin: 0 auto; }

.head-bg {
  top: 0;
  left: 0;
  right: 0;
  z-index: 1;
  display: none;
  position: absolute;
  background-size: cover;
  background-color: #242832;
  background-repeat: no-repeat;
  background-position: center; }
  .head-bg:before {
    content: '';
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    position: absolute;
    background-color: rgba(44, 51, 64, 0.8); }

@media (max-width: 767px) {
  .head-bar {
    padding-top: 0;
    padding-bottom: 0;
    position: relative; }

  .head-bar-inner .row > div {
    position: static; } }
/**
 * 9.1 - Logo
 */
.logo {
  color: #9a9da2 !important;
  font-size: 30px;
  font-weight: 400;
  font-family: 'Fredoka One', cursive;
  line-height: 40px;
  display: inline-block;
  vertical-align: middle;
  overflow: hidden;
  margin-top: 7px; }
  .logo:hover {
    text-decoration: none; }
  .logo, .logo img {
    max-height: 40px; }
  .logo img {
    max-width: 100%;
    margin-top: -5px;
    display: inline-block; }
  .logo span {
    font-size: 30px;
    text-transform: uppercase;
    margin-right: 3px; }

@media (max-width: 767px) {
  .logo {
    margin-top: 0; } }
/**
 * 9.2 - Navigation
 */
.nav-wrap {
  position: relative;
  padding: 7px 55px 7px 0;
  min-height: 55px; }
  .nav-wrap .nav {
    float: right;
    margin-right: 30px;
    display: block; }
    .nav-wrap .nav ul {
      margin: 0;
      padding: 0;
      list-style: none; }
    .nav-wrap .nav a {
      white-space: nowrap;
      font-family: "Open Sans", sans-serif; }
      .nav-wrap .nav a:hover {
        text-decoration: none; }
    .nav-wrap .nav > ul > li {
      float: left;
      margin: 0 30px 0 0;
      position: relative; }
      .nav-wrap .nav > ul > li:last-child {
        margin-right: 0; }
      .nav-wrap .nav > ul > li > a {
        color: #3c4451;
        font-size: 13px;
        font-weight: 700;
        line-height: 1;
        text-transform: uppercase;
        display: inline-block;
        padding: 15px 0 12px; }
        .nav-wrap .nav > ul > li > a > span {
          position: absolute;
          left: 0;
          top: 100%;
          width: 0;
          height: 3px;
          -webkit-border-radius: 10px;
          -moz-border-radius: 10px;
          border-radius: 10px;
          -webkit-transition: width 0.15s linear 0s;
          -moz-transition: width 0.15s linear 0s;
          transition: width 0.15s linear 0s; }
      .nav-wrap .nav > ul > li.active > a > span, .nav-wrap .nav > ul > li:hover > a > span {
        width: 100%; }
      .nav-wrap .nav > ul > li:hover > ul {
        opacity: 1;
        visibility: visible; }
      .nav-wrap .nav > ul > li ul {
        left: 0;
        top: 100%;
        z-index: 10;
        position: absolute;
        opacity: 0;
        margin-top: -1px;
        visibility: hidden;
        background-color: #fff;
        box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24);
        -webkit-backface-visibility: hidden;
        -moz-backface-visibility: hidden;
        backface-visibility: hidden;
        -webkit-transition: opacity 0.25s ease-out 0s;
        -moz-transition: opacity 0.25s ease-out 0s;
        transition: opacity 0.25s ease-out 0s; }
        .nav-wrap .nav > ul > li ul li:first-child {
          padding-top: 10px; }
        .nav-wrap .nav > ul > li ul li:last-child {
          padding-bottom: 10px; }
        .nav-wrap .nav > ul > li ul a {
          color: #3c4451;
          font-size: 14px;
          line-height: 1;
          display: block;
          padding: 10px 30px;
          background-color: transparent;
          -webkit-backface-visibility: hidden;
          -moz-backface-visibility: hidden;
          backface-visibility: hidden;
          -webkit-transition: background-color 0.25s ease-out 0s;
          -moz-transition: background-color 0.25s ease-out 0s;
          transition: background-color 0.25s ease-out 0s; }
          .nav-wrap .nav > ul > li ul a:hover {
            background-color: #ebecee; }
  .nav-wrap .btn-mobile-nav,
  .nav-wrap .btn-sidebar-open {
    border: 0;
    margin: 0;
    padding: 0;
    position: absolute;
    top: 0;
    height: 55px;
    line-height: 1;
    display: block;
    cursor: pointer;
    text-align: center;
    background: transparent;
    border: 1px solid #d1d1d1;
    -webkit-border-radius: 1px;
    -moz-border-radius: 1px;
    border-radius: 1px;
    -webkit-transition: all 50ms liner;
    -moz-transition: all 50ms liner;
    transition: all 50ms liner; }
  .nav-wrap .btn-sidebar-open {
    right: 0;
    position: absolute;
    width: 55px; }
    .nav-wrap .btn-sidebar-open .rsicon {
      color: #3d4451;
      font-size: 25px; }
  .nav-wrap .btn-mobile-nav {
    right: 65px;
    display: none;
    padding-left: 30px;
    padding-right: 30px;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 700;
    letter-spacing: 1px; }

@media (max-width: 991px) {
  .nav-wrap .nav {
    display: none !important; }
  .nav-wrap .btn-mobile-nav {
    display: block; } }
@media (max-width: 767px) {
  .nav-wrap {
    min-height: 40px;
    padding: 0 40px 0 0; }
    .nav-wrap .btn-mobile-nav,
    .nav-wrap .btn-sidebar-open {
      height: 40px;
      line-height: 40px; }
    .nav-wrap .btn-sidebar-open {
      width: 40px; }
    .nav-wrap .btn-mobile-nav {
      right: 50px;
      padding-left: 13px;
      padding-right: 13px; } }
/**
 * 9.3 - Mobile Navigation
 */
@media (min-width: 992px) {
  .mobile-nav {
    display: none !important; } }
@media (max-width: 991px) {
  .mobile-nav {
    position: fixed;
    right: 0;
    top: 0;
    height: 100%;
    width: 300px;
    z-index: 100;
    padding: 50px 14px 20px 50px;
    -webkit-transform: translateX(300px);
    -moz-transform: translateX(300px);
    transform: translateX(300px);
    -webkit-transition: -webkit-transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94);
    -moz-transition: -moz-transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94);
    transition: transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94); }
    .mobile-nav .mobile-nav-close {
      position: absolute;
      right: 10px;
      top: 10px;
      border: 0;
      margin: 0;
      padding: 0;
      background: transparent;
      display: block; }
      .mobile-nav .mobile-nav-close .rsicon {
        color: #3d4451;
        font-size: 25px;
        line-height: 1;
        display: block; }
    .mobile-nav .mobile-nav-inner {
      overflow: auto;
      position: relative;
      height: 100%; }
    .mobile-nav .nav ul {
      margin: 0;
      padding: 0;
      list-style: none; }
    .mobile-nav .nav li {
      line-height: 1; }
    .mobile-nav .nav a {
      color: #fff;
      font-size: 14px;
      font-family: "Open Sans", sans-serif;
      line-height: 1;
      display: inline-block; }
      .mobile-nav .nav a:hover {
        text-decoration: none; }
    .mobile-nav .nav > ul > li {
      margin-bottom: 20px; }
    .mobile-nav .nav > ul > li > a {
      font-weight: 600;
      text-transform: uppercase; }
    .mobile-nav .nav > ul > li ul {
      margin: 20px 0 0 20px; }
      .mobile-nav .nav > ul > li ul li {
        margin-bottom: 15px; }

  .mobile-nav-opened .mobile-nav {
    -webkit-transform: translateX(0);
    -moz-transform: translateX(0);
    transform: translateX(0); }
  .mobile-nav-opened #overlay {
    top: 0;
    opacity: .7;
    -webkit-transition: top 0s ease 0s, opacity 0.35s ease;
    -moz-transition: top 0s ease 0s, opacity 0.35s ease;
    transition: top 0s ease 0s, opacity 0.35s ease; } }
/**
 * 9.4 - Header With BgImage
 */
.header-has-img .header {
  margin-bottom: 40px; }
.header-has-img .head-bg {
  height: 270px;
  display: block; }
.header-has-img.home .head-bg {
  height: 515px; }
.header-has-img .head-bar {
  background-color: transparent;
  box-shadow: none; }
.header-has-img .nav-wrap .nav > ul > li > a {
  color: #fff;
  color: rgba(255, 255, 255, 0.7); }
.header-has-img .nav-wrap .btn-mobile-nav,
.header-has-img .nav-wrap .btn-sidebar-open {
  border-color: #4f5159; }
  .header-has-img .nav-wrap .btn-mobile-nav .rsicon,
  .header-has-img .nav-wrap .btn-sidebar-open .rsicon {
    color: #fff; }
.header-has-img .head-sticky.head-bar {
  background-color: #fff; }
.header-has-img .head-sticky .nav-wrap .nav > ul > li > a {
  color: #3d4451;
  opacity: 1; }
.header-has-img .head-sticky .nav-wrap .btn-mobile-nav,
.header-has-img .head-sticky .nav-wrap .btn-sidebar-open {
  border-color: #d1d1d1; }
.header-has-img .head-sticky .nav-wrap .btn-sidebar-open .rsicon {
  color: #3d4451; }

/**
 * 9.5 - Header Sticky
 */
.head-sticky.head-bar {
  top: 0;
  left: 0;
  width: 100%;
  position: fixed;
  padding-top: 0;
  padding-bottom: 0;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.19), 0 6px 10px rgba(0, 0, 0, 0.23); }
.head-sticky .logo {
  margin-top: 0; }
.head-sticky .nav-wrap {
  min-height: 40px;
  padding: 0 40px 0 0; }
  .head-sticky .nav-wrap .btn-mobile-nav,
  .head-sticky .nav-wrap .btn-sidebar-open {
    height: 40px; }
  .head-sticky .nav-wrap .btn-sidebar-open {
    width: 40px; }
  .head-sticky .nav-wrap .btn-mobile-nav {
    right: 50px;
    padding-left: 13px;
    padding-right: 13px; }

/**
 * 10.0 - Sidebar
 */
.sidebar-shift {
  margin-top: 165px; }

.sidebar a {
  -webkit-transition: color 0.15s linear 0s;
  -moz-transition: color 0.15s linear 0s;
  transition: color 0.15s linear 0s; }

.btn-sidebar-close {
  top: 25px;
  left: -58px;
  width: 58px;
  height: 58px;
  border: 0;
  margin: 0;
  padding: 0;
  display: block;
  cursor: pointer;
  text-align: center;
  position: absolute;
  -webkit-border-radius: 3px 0 0 3px;
  -moz-border-radius: 3px 0 0 3px;
  border-radius: 3px 0 0 3px; }
  .btn-sidebar-close .rsicon {
    color: #fff;
    font-size: 30px; }

/**
 * 10.1 - Sidebar Fixed
 */
.sidebar-fixed {
  position: fixed;
  z-index: 100;
  top: 0;
  right: 0;
  width: 385px;
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: #fff;
  -webkit-transform: translateX(450px);
  -moz-transform: translateX(450px);
  transform: translateX(450px);
  -webkit-transition: -webkit-transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94);
  -moz-transition: -moz-transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94);
  transition: transform 0.4s cubic-bezier(0.37, 0.15, 0.32, 0.94); }
  .sidebar-fixed .widget-area {
    padding: 25px 0;
    overflow: auto;
    position: relative;
    height: 100%; }
  .sidebar-fixed .widget {
    padding-left: 25px;
    padding-right: 25px; }
  .sidebar-fixed .animate-up {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translate(0, 0);
    -moz-transform: translate(0, 0);
    transform: translate(0, 0); }

.sidebar-opened .sidebar-fixed {
  -webkit-transform: translateX(0);
  -moz-transform: translateX(0);
  transform: translateX(0); }
.sidebar-opened #overlay {
  top: 0;
  opacity: .7;
  -webkit-transition: top 0s ease 0s, opacity 0.35s ease;
  -moz-transition: top 0s ease 0s, opacity 0.35s ease;
  transition: top 0s ease 0s, opacity 0.35s ease; }

@media (max-width: 767px) {
  .sidebar-default {
    margin-top: 50px; }

  .sidebar-fixed {
    width: 265px; }
    .sidebar-fixed .widget {
      padding-left: 15px;
      padding-right: 10px; }

  .btn-sidebar-close {
    left: -35px;
    width: 35px;
    height: 35px; }
    .btn-sidebar-close .rsicon {
      font-size: 25px;
      line-height: 35px; } }
/**
 * 10.2 - Widgets
 */
.widget-title {
  font-size: 20px;
  font-weight: 500;
  line-height: 1.1;
  text-transform: uppercase;
  margin-top: 0;
  margin-bottom: 30px; }

.widget {
  color: #000000;
  font-size: 14px;
  font-weight: 400;
  line-height: 1.4;
  margin-bottom: 55px; }
  .widget:last-child {
    margin-bottom: 0; }

.widget ul {
  list-style: none;
  margin: 0;
  padding: 0; }

.widget ul ul {
  margin-left: 15px; }

.widget_meta ul li,
.widget_archive ul li,
.widget_nav_menu ul li,
.widget_categories ul li,
.widget_recent_entries ul li,
.widget_recent_comments ul li {
  color: #757575;
  padding: 10px 0;
  border-bottom: 1px solid #d8d8d8; }

.widget_meta ul li li,
.widget_archive ul li li,
.widget_nav_menu ul li li,
.widget_categories ul li li,
.widget_recent_entries ul li li,
.widget_recent_comments ul li li {
  border-bottom: none;
  padding-top: 3px;
  padding-bottom: 3px; }

.widget_meta ul li a,
.widget_archive ul li a,
.widget_nav_menu ul li a,
.widget_categories ul li a,
.widget_recent_entries ul li a,
.widget_recent_comments ul li a {
  color: #000; }

.widget_meta ul li a:hover,
.widget_archive ul li a:hover,
.widget_nav_menu ul li a:hover,
.widget_categories ul li a:hover,
.widget_recent_entries ul li a:hover,
.widget_recent_comments ul li a:hover {
  opacity: 0.8;
  text-decoration: none; }

/* Widget: Categories */
.widget_archive ul li,
.widget_categories ul li {
  text-align: right; }
  .widget_archive ul li:before, .widget_archive ul li:after,
  .widget_categories ul li:before,
  .widget_categories ul li:after {
    content: " ";
    display: table; }
  .widget_archive ul li:after,
  .widget_categories ul li:after {
    clear: both; }
  .widget_archive ul li,
  .widget_categories ul li {
    *zoom: 1; }

.widget_archive ul li a,
.widget_categories ul li a {
  float: left;
  text-align: left;
  max-width: 80%; }

.widget_archive .screen-reader-text,
.widget_categories .screen-reader-text {
  display: none; }

/* Widget: Recent Posts */
.widget_recent_entries .post-date {
  display: block; }

/* Widget: Calendar */
.widget_calendar table,
.widget_calendar th,
.widget_calendar td {
  border: none; }

.widget_calendar th,
.widget_calendar td {
  padding: 10px 5px;
  text-align: center;
  vertical-align: middle; }

.widget_calendar th {
  color: #757575;
  font-size: 14px;
  font-weight: 700;
  line-height: 1;
  text-transform: uppercase;
  border-top: 1px solid #e5e5e5;
  border-bottom: 1px solid #e5e5e5; }

.widget_calendar caption {
  color: #333333;
  font-weight: 600;
  text-transform: uppercase;
  padding-bottom: 10px;
  text-align: center; }

.widget_calendar tfoot td {
  border-top: 1px solid #e5e5e5;
  border-bottom: 1px solid #e5e5e5; }

.widget_calendar tfoot #prev {
  text-align: left; }

.widget_calendar tfoot #next {
  text-align: right; }

/* Widget: Tag Cloud */
.widget_tag_cloud a {
  color: #858585 !important;
  font-size: 12px !important;
  font-weight: 400;
  line-height: 1;
  text-transform: uppercase;
  display: inline-block;
  margin-right: 1px;
  margin-bottom: 4px;
  padding: 10px 15px;
  border: 1px solid #dddddd;
  -webkit-border-radius: 2px;
  -moz-border-radius: 2px;
  border-radius: 2px;
  -webkit-transition: all 0.15s linear 0s;
  -moz-transition: all 0.15s linear 0s;
  transition: all 0.15s linear 0s; }

.widget_tag_cloud a:hover {
  color: #fff !important;
  text-decoration: none; }

/* Widget: Search */
.widget_search .widget-title,
.widget_search label .screen-reader-text {
  display: none; }

.widget_search label {
  display: block;
  height: 54px;
  padding: 10px 40px 10px 18px; }

.widget_search .search-form:before {
  position: absolute;
  content: "\e602";
  right: 0;
  top: 0;
  width: 54px;
  height: 54px;
  line-height: 54px;
  font-size: 20px;
  text-align: center;
  display: block; }

.widget_search .search-form {
  position: relative;
  border-width: 1px;
  border-style: solid;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px; }

.widget_search .search-field {
  height: 34px;
  line-height: normal;
  padding: 0;
  margin: 0;
  border: 0;
  -webkit-appearance: none; }

.widget_search .search-submit {
  top: 0;
  right: 0;
  margin: 0;
  border: 0;
  padding: 0;
  z-index: 2;
  width: 54px;
  height: 54px;
  position: absolute;
  text-indent: -9999px;
  background: transparent; }

/* Widget: Profile */
.widget-profile {
  padding: 0 0 25px 0;
  margin-bottom: 30px;
  border-bottom: 1px solid #d8d8d8; }

.widget-profile .profile-info {
  margin: 15px 0 0 0;
  text-align: center; }

.widget-profile .profile-title {
  color: #3d4451;
  font-size: 30px;
  font-weight: 600;
  line-height: 1.1;
  margin-bottom: 10px; }

.widget-profile .profile-position {
  color: #3d4451;
  font-size: 16px;
  line-height: 1.1;
  margin-bottom: 0; }

/* Widget: Popular Posts */
.widget-popuplar-posts li,
.widget-recent-posts li {
  padding-bottom: 15px;
  border-bottom: 1px solid #d8d8d8;
  margin-bottom: 17px; }
  .widget-popuplar-posts li:last-child,
  .widget-recent-posts li:last-child {
    margin-bottom: 0; }
.widget-popuplar-posts .post-media,
.widget-recent-posts .post-media {
  width: 78px;
  float: left;
  margin-right: 20px;
  margin-bottom: 10px; }
  .widget-popuplar-posts .post-media img,
  .widget-recent-posts .post-media img {
    width: 100%;
    display: block;
    margin-top: 2px;
    box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }
.widget-popuplar-posts .post-title,
.widget-recent-posts .post-title {
  color: #000000;
  font-size: 16px;
  font-weight: 400;
  line-height: 1.3;
  margin-bottom: 10px; }
  .widget-popuplar-posts .post-title a,
  .widget-recent-posts .post-title a {
    color: inherit; }
    .widget-popuplar-posts .post-title a:hover,
    .widget-recent-posts .post-title a:hover {
      text-decoration: none; }
.widget-popuplar-posts .post-info,
.widget-recent-posts .post-info {
  clear: both; }
  .widget-popuplar-posts .post-info a,
  .widget-recent-posts .post-info a {
    color: #303030 !important; }
.widget-popuplar-posts .post-tag,
.widget-recent-posts .post-tag {
  font-size: 12px;
  margin-bottom: 10px; }
  .widget-popuplar-posts .post-tag a,
  .widget-recent-posts .post-tag a {
    font-weight: 400; }

/**
 * 10.3 - No Sidebar
 */
.no-sidebar .nav-wrap,
.page-single .nav-wrap {
  padding-right: 0 !important; }
  .no-sidebar .nav-wrap .nav,
  .page-single .nav-wrap .nav {
    margin-right: 0; }
    .no-sidebar .nav-wrap .nav > ul > li:last-child,
    .page-single .nav-wrap .nav > ul > li:last-child {
      margin-right: 0; }
  .no-sidebar .nav-wrap .btn-sidebar-open,
  .page-single .nav-wrap .btn-sidebar-open {
    display: none !important; }
  .no-sidebar .nav-wrap .btn-mobile-nav,
  .page-single .nav-wrap .btn-mobile-nav {
    right: 0 !important; }

/**
 * 11.0 - Home
 */
/**
 * 11.1 - Section Text
 */
.section-txt-btn {
  color: #000;
  font-size: 20px;
  font-weight: 300;
  line-height: 1.8;
  text-align: center;
  margin-top: 30px;
  padding-left: 5%;
  padding-right: 5%; }
  .section-txt-btn .section-txt-btn .btn {
    padding: 21px 55px;
    letter-spacing: 0.05em;
    margin: 5px; }

.section-txt-btn p:last-child,
.section-text .section-box *:last-child {
  margin-bottom: 0; }

/**
 * 11.2 - Section About
 */
.section-about {
  padding-top: 40px;
  position: relative; }
  .section-about .section-box {
    padding: 0; }
  .section-about .profile {
    padding: 57px 50px 15px 50px; }
  .section-about .profile-photo {
    margin-right: 10%;
    margin-bottom: 10px; }
  .section-about .profile-info {
    color: #3d4451;
    padding-bottom: 25px;
    margin-bottom: 25px;
    border-bottom: 1px solid #dedede; }
  .section-about .profile-title {
    font-size: 36px;
    line-height: 1.1;
    font-weight: 700;
    margin-bottom: 5px; }
    .section-about .profile-title span {
      font-weight: 300; }
  .section-about .profile-position {
    font-size: 18px;
    font-weight: 400;
    line-height: 1.1;
    margin-bottom: 0; }

.profile-photo img {
  width: 100%;
  display: block; }

.profile-preword {
  margin-bottom: 28px; }
  .profile-preword span {
    color: #fff;
    font-size: 14px;
    font-weight: 700;
    line-height: 1.1;
    display: inline-block;
    padding: 7px 12px;
    text-transform: uppercase;
    position: relative; }
    .profile-preword span:before {
      content: '';
      width: 0;
      height: 0;
      top: 100%;
      left: 5px;
      display: block;
      position: absolute;
      border-style: solid;
      border-width: 0 0 8px 8px;
      border-color: transparent; }

.profile-list {
  margin: 0;
  padding: 0;
  list-style: none; }
  .profile-list li {
    margin-bottom: 13px; }
  .profile-list .title {
    display: block;
    width: 120px;
    float: left;
    color: #333333;
    font-size: 12px;
    font-weight: 700;
    line-height: 20px;
    text-transform: uppercase; }
  .profile-list .cont {
    display: block;
    margin-left: 125px;
    font-size: 15px;
    font-weight: 400;
    line-height: 20px;
    color: #9da0a7; }
    .profile-list .cont a {
      color: inherit; }
    .profile-list .cont.profile-vacation {
      font-size: 14px; }
  .profile-list .button {
    color: #fff;
    font-size: 12px;
    font-weight: 700;
    line-height: 1;
    text-transform: none;
    padding: 5px 8px;
    display: inline-block;
    position: relative;
    top: -2px;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px; }
  .profile-list .rsicon {
    margin-right: 10px;
    vertical-align: baseline; }

.profile-social {
  padding: 15px 0; }

@media (max-width: 992px) {
  .section-about .profile {
    padding: 50px 40px 15px 40px; }
  .section-about .profile-photo {
    margin-right: 0;
    margin-bottom: 30px; } }
@media (max-width: 767px) {
  .section-about {
    padding-top: 0; }
    .section-about .profile {
      padding: 30px 20px 15px 20px; }

  .profile-list .title, .profile-list .cont {
    width: 100%;
    float: none;
    line-height: 1.2; }
  .profile-list .title {
    margin-bottom: 3px; }
  .profile-list .cont {
    margin-left: 0;
    margin-bottom: 15px; } }
@media (max-width: 480px) {
  .section-about .row > div {
    width: 100%; }
  .section-about .profile-title {
    font-size: 28px; } }
/**
 * 11.3 - Section Skills
 */
.section-skills .section-box {
  padding-bottom: 50px; }

.progress-bar {
  position: relative;
  margin-bottom: 40px; }
  .progress-bar .bar-data {
    font-size: 14px;
    line-height: 1.1;
    padding-right: 40px; }
  .progress-bar .bar-value {
    font-size: 16px;
    position: absolute;
    right: 0;
    top: 0;
    display: block; }
  .progress-bar .bar-title {
    display: block;
    margin-bottom: 5px; }
  .progress-bar .bar-fill {
    width: 0;
    height: 100%;
    display: block;
    position: relative;
    z-index: 1;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px;
    -webkit-transition: width 400ms ease-out 100ms;
    -moz-transition: width 400ms ease-out 100ms;
    transition: width 400ms ease-out 100ms; }
  .progress-bar .bar-line {
    height: 5px;
    position: relative; }
    .progress-bar .bar-line:after {
      content: '';
      opacity: 0.2;
      position: absolute;
      left: 0;
      bottom: 0;
      width: 100%;
      height: 100%;
      z-index: 0;
      -webkit-border-radius: 5px;
      -moz-border-radius: 5px;
      border-radius: 5px; }

@media (min-width: 768px) {
  .section-skills .section-box .row:last-child .progress-bar {
    margin-bottom: 0; } }
@media (max-width: 767px) {
  .section-skills .section-box {
    padding-bottom: 35px; }
    .section-skills .section-box .row:last-child .col-sm-6:last-child .progress-bar {
      margin-bottom: 0; } }
/**
 * 11.4 - Section Interests
 */
.section-interests .section-box {
  text-align: center; }

.interests-list {
  text-align: center;
  margin: 0;
  padding: 0;
  list-style: none; }
  .interests-list li {
    margin: 7px 5px;
    width: 74px;
    height: 74px;
    display: inline-block;
    border: 1px solid #d7dbde;
    position: relative;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px; }
    .interests-list li span {
      color: #fff;
      font-size: 11px;
      font-weight: 400;
      line-height: 1;
      display: inline-block;
      background-color: #717171;
      padding: 5px 8px;
      white-space: nowrap;
      position: absolute;
      top: 100%;
      margin-top: 10px;
      z-index: 1;
      opacity: 0;
      visibility: hidden;
      -webkit-border-radius: 3px;
      -moz-border-radius: 3px;
      border-radius: 3px;
      -webkit-transition: all 0.15s ease-in;
      -moz-transition: all 0.15s ease-in;
      transition: all 0.15s ease-in;
      -webkit-transform: translate3d(0, -15px, 0);
      -moz-transform: translate3d(0, -15px, 0);
      transform: translate3d(0, -15px, 0);
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      backface-visibility: hidden; }
    .interests-list li:hover span {
      opacity: 1;
      visibility: visible;
      -webkit-transition: all 0.35s ease-out;
      -moz-transition: all 0.35s ease-out;
      transition: all 0.35s ease-out;
      -webkit-transform: translate3d(0, 0, 0);
      -moz-transform: translate3d(0, 0, 0);
      transform: translate3d(0, 0, 0);
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      backface-visibility: hidden; }
  .interests-list i {
    display: block;
    width: 100%;
    height: 100%;
    font-size: 30px;
    line-height: 74px;
    cursor: pointer; }

@media (max-width: 767px) {
  .interests-list li {
    margin: 5px 3px;
    width: 65px;
    height: 65px; }
    .interests-list li .rsicon {
      line-height: 65px; } }
/**
 * 11.5 - Section Portfolio
 */
.grid:before, .grid:after {
  content: " ";
  display: table; }
.grid:after {
  clear: both; }
.grid {
  *zoom: 1; }
.grid .grid-item,
.grid .grid-sizer {
  width: 33.33%; }
.grid .grid-sizer {
  height: 0;
  visibility: hidden; }
.grid .grid-item {
  float: left;
  padding: 0 10px;
  margin-bottom: 20px; }
.grid .grid-box {
  width: 100%;
  height: 0;
  padding-top: 95%;
  position: relative;
  overflow: hidden;
  background: rgba(0, 0, 0, 0.15); }
.grid .size11 {
  width: 33.33%; }
  .grid .size11 .portfolio-title {
    font-size: 18px; }
.grid .size22 {
  width: 66.66%; }
  .grid .size22 .portfolio-title {
    font-size: 24px; }

.grid-more {
  margin-top: 20px;
  text-align: center; }
  .grid-more .btn {
    margin: 0;
    padding: 0;
    width: 60px;
    height: 60px;
    display: inline-block;
    line-height: 1; }
    .grid-more .btn .rsicon {
      font-size: 30px;
      -webkit-transition: all 0.2s;
      -moz-transition: all 0.2s;
      transition: all 0.2s; }
    .grid-more .btn:hover .rsicon {
      -webkit-transform: rotate(90deg);
      -moz-transform: rotate(90deg);
      transform: rotate(90deg); }
  .grid-more .ajax-loader {
    display: none;
    width: 72px;
    height: 24px;
    vertical-align: middle;
    background: url("img/ajax-loader.gif"); }

.filter {
  text-align: center;
  margin-bottom: 30px; }
  .filter button {
    border: 0;
    margin: 0 20px 0 0;
    padding: 0 12px;
    background: transparent;
    color: #000;
    font-size: 13px;
    font-weight: 600;
    font-family: "Open Sans", sans-serif;
    text-transform: uppercase; }
    .filter button:first-child {
      padding-left: 0; }
    .filter button:last-child {
      margin-right: 0;
      padding-right: 0; }

.filter-inner {
  display: inline-block;
  position: relative; }

.filter-bar {
  height: 5px;
  margin: 10px auto 0;
  background-color: #fff;
  position: relative; }
  .filter-bar, .filter-bar .filter-bar-line {
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px; }
  .filter-bar .filter-bar-line {
    top: 0;
    left: 0;
    width: 0;
    height: 100%;
    display: block;
    position: relative;
    -webkit-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
    -moz-transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms;
    transition: all 1s cubic-bezier(0.23, 1, 0.32, 1) 0ms; }

.portfolio-figure {
  top: 0;
  left: 0;
  z-index: 1;
  width: 100%;
  height: 100%;
  position: absolute; }
  .portfolio-figure img {
    position: relative;
    display: block;
    width: 100%;
    opacity: 1;
    -webkit-transform: scale3d(1.02, 1.02, 1);
    -moz-transform: scale3d(1.02, 1.02, 1);
    transform: scale3d(1.02, 1.02, 1);
    -webkit-transition: opacity 1s, transform 1s;
    -moz-transition: opacity 1s, transform 1s;
    transition: opacity 1s, transform 1s;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden; }
  .portfolio-figure .portfolio-caption {
    top: -2px;
    left: -2px;
    right: -2px;
    bottom: -2px;
    opacity: 0;
    position: absolute;
    background-color: rgba(32, 39, 52, 0.8);
    -webkit-transition: opacity 0.35s linear 0s;
    -moz-transition: opacity 0.35s linear 0s;
    transition: opacity 0.35s linear 0s;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden; }
  .portfolio-figure .portfolio-caption-inner {
    left: 0;
    bottom: 0;
    width: 100%;
    padding: 5%;
    position: absolute;
    -webkit-transition: -webkit-transform 0.35s;
    -moz-transition: -moz-transform 0.35s;
    transition: transform 0.35s;
    -webkit-transform: translate3d(0, 100%, 0);
    -moz-transform: translate3d(0, 100%, 0);
    transform: translate3d(0, 100%, 0);
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden; }
  .portfolio-figure .portfolio-title,
  .portfolio-figure .portfolio-cat {
    opacity: 0;
    -webkit-transition: opacity 0.35s;
    -moz-transition: opacity 0.35s;
    transition: opacity 0.35s;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden; }
  .portfolio-figure .portfolio-title {
    color: #fff;
    font-weight: 700;
    line-height: 1.3;
    margin-bottom: 13px; }
  .portfolio-figure .portfolio-cat {
    color: #a7a9ab;
    font-size: 13px;
    line-height: 1.1;
    text-transform: uppercase; }
  .portfolio-figure .btn-group a {
    width: 50px;
    height: 50px;
    margin-right: 5px;
    text-align: center;
    display: inline-block;
    background: transparent;
    border: 1px solid #767475;
    border: 1px solid rgba(255, 255, 255, 0.2);
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px;
    -webkit-transition: -webkit-transform 0.35s;
    -moz-transition: -moz-transform 0.35s;
    transition: transform 0.35s;
    -webkit-transform: translate3d(0, 200%, 0);
    -moz-transform: translate3d(0, 200%, 0);
    transform: translate3d(0, 200%, 0);
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden; }
    .portfolio-figure .btn-group a:hover {
      text-decoration: none; }
  .portfolio-figure .btn-group .rsicon {
    display: block;
    line-height: 50px;
    font-size: 25px; }
  .portfolio-figure:hover img {
    opacity: 0.85;
    -webkit-transform: scale3d(1.1, 1.1, 1);
    -moz-transform: scale3d(1.1, 1.1, 1);
    transform: scale3d(1.1, 1.1, 1); }
  .portfolio-figure:hover .portfolio-caption,
  .portfolio-figure:hover .portfolio-title,
  .portfolio-figure:hover .portfolio-cat {
    opacity: 1; }
  .portfolio-figure:hover .portfolio-caption-inner {
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0); }
  .portfolio-figure:hover .btn-group a {
    -webkit-transform: translate3d(0, 0, 0);
    -moz-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0); }
  .portfolio-figure:hover .btn-group .btn-zoom {
    -webkit-transition-delay: 0.3s;
    -moz-transition-delay: 0.3s;
    transition-delay: 0.3s; }
  .portfolio-figure:hover .btn-group .btn-link {
    -webkit-transition-delay: 0.2s;
    -moz-transition-delay: 0.2s;
    transition-delay: 0.2s; }
	
.fancybox-inline-box .inline-cont{
	background-color: #fff;
}

@media (max-width: 767px) {
  .filter-bar {
    display: none; }

  .filter-inner {
    display: block; }

  .filter button {
    width: 100%;
    margin: 0;
    padding: 10px 0;
    display: block;
    border-bottom: 1px solid #d7dbde;
    position: relative; }

  .filter .active:after {
    content: '';
    left: 0;
    bottom: -1px;
    height: 3px;
    width: 100%;
    position: absolute; }

  .grid .grid-item,
  .grid .grid-sizer {
    width: 50%; }
  .grid .size11,
  .grid .size22 {
    width: 50%; }
    .grid .size11 .portfolio-title,
    .grid .size22 .portfolio-title {
      font-size: 18px; } }
@media (max-width: 480px) {
  .grid .grid-item,
  .grid .grid-sizer {
    width: 100%; }
  .grid .size11,
  .grid .size22 {
    width: 100%; }
    .grid .size11 .portfolio-title,
    .grid .size22 .portfolio-title {
      font-size: 22px; } }
.fancybox-portfolio .fancybox-error {
  background: #fff;
  margin-right: 70px;
  min-height: 225px; }
.fancybox-portfolio .fancybox-skin {
  box-shadow: none;
  background-color: transparent;
  -webkit-border-radius: 0px;
  -moz-border-radius: 0px;
  border-radius: 0px; }
.fancybox-portfolio .fancybox-nav,
.fancybox-portfolio .fancybox-close {
  left: auto;
  right: 0px;
  width: 45px;
  height: 45px;
  border: 1px solid #767475;
  border: 1px solid rgba(255, 255, 255, 0.3);
  -webkit-transition: all 0.3s ease-out;
  -moz-transition: all 0.3s ease-out;
  transition: all 0.3s ease-out; }
  .fancybox-portfolio .fancybox-nav:hover,
  .fancybox-portfolio .fancybox-close:hover {
    background-color: rgba(255, 255, 255, 0.1);
    box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }
.fancybox-portfolio .fancybox-close,
.fancybox-portfolio .fancybox-prev span,
.fancybox-portfolio .fancybox-next span {
  background-image: url("img/fancybox_sprite.png"); }
.fancybox-portfolio .fancybox-close {
  top: 0;
  background-position: -91px 0px; }
.fancybox-portfolio .fancybox-nav span {
  top: 0;
  left: 0;
  margin: 0;
  right: auto;
  width: 100%;
  height: 100%;
  visibility: visible; }
.fancybox-portfolio .fancybox-prev {
  top: 127px; }
  .fancybox-portfolio .fancybox-prev span {
    background-position: -1px 0px; }
.fancybox-portfolio .fancybox-next {
  top: 180px; }
  .fancybox-portfolio .fancybox-next span {
    background-position: -46px 0px; }

.fancybox-inline-box {
  width: 730px;
  z-index: 0;
  opacity: 0;
  visibility: hidden;
  position: relative;
  background: #fff;
  overflow-y: auto;
  overflow-x: hidden;
  margin-right: 65px;
  -webkit-box-sizing: content-box;
  -moz-box-sizing: content-box;
  box-sizing: content-box; }
  .fancybox-inline-box.opened {
    height: 100%;
    min-height: 225px;
    opacity: 1;
    visibility: visible; }
  .fancybox-inline-box .inline-cont {
    padding: 25px 40px; }
  .fancybox-inline-box .inline-title {
    color: #000;
    font-size: 20px;
    line-height: 1.25;
    margin-bottom: 20px; }
  .fancybox-inline-box .inline-text {
    color: #757575;
    font-size: 16px;
    line-height: 1.3; }
    .fancybox-inline-box .inline-text p {
      margin-bottom: 15px; }
      .fancybox-inline-box .inline-text p:last-child {
        margin-bottom: 0; }
  .fancybox-inline-box .inline-embed-image {
    width: 100%; }
    .fancybox-inline-box .inline-embed-image img {
      width: 100%;
      height: auto;
      display: block; }
  .fancybox-inline-box .inline-embed-iframe,
  .fancybox-inline-box .inline-embed-video {
    width: 100%;
    height: 410px; }
  .fancybox-inline-box .inline-embed-iframe iframe {
    width: 100%;
    height: 100%;
    border: 0; }
  .fancybox-inline-box .mejs-poster,
  .fancybox-inline-box .mejs-container,
  .fancybox-inline-box .mejs-overlay-play,
  .fancybox-inline-box .inline-embed video {
    width: 100% !important;
    height: 100% !important; }

@media only screen and (min--moz-device-pixel-ratio: 2), only screen and (-o-min-device-pixel-ratio: 2 / 1), only screen and (-webkit-min-device-pixel-ratio: 2), only screen and (min-device-pixel-ratio: 2) {
  .fancybox-portfolio .fancybox-nav span,
  .fancybox-portfolio .fancybox-close {
    background-image: url("img/fancybox_sprite@2x.png");
    background-size: 135px 45px; } }
@media (max-width: 992px) {
  .fancybox-inline-box {
    width: 650px; }
    .fancybox-inline-box .inline-embed-iframe,
    .fancybox-inline-box .inline-embed-video {
      height: 360px; } }
@media (max-width: 767px) {
  .fancybox-portfolio .fancybox-error {
    background: #fff;
    margin-right: 0;
    min-height: 0px; }
  .fancybox-portfolio .fancybox-nav,
  .fancybox-portfolio .fancybox-close {
    width: 30px;
    height: 30px; }
  .fancybox-portfolio .fancybox-close {
    top: -40px;
    right: 0;
    background-position: -99px -8px; }
  .fancybox-portfolio .fancybox-prev {
    top: -40px;
    left: 0;
    right: auto; }
    .fancybox-portfolio .fancybox-prev span {
      background-position: -9px -8px; }
  .fancybox-portfolio .fancybox-next {
    top: -40px;
    left: 40px;
    right: auto; }
    .fancybox-portfolio .fancybox-next span {
      background-position: -53px -8px; }

  .fancybox-inline-box {
    margin-right: 0;
    width: 420px; }
    .fancybox-inline-box .inline-embed-iframe,
    .fancybox-inline-box .inline-embed-video {
      height: 230px; }
    .fancybox-inline-box .inline-cont {
      padding: 20px; } }
@media (max-width: 480px) {
  .fancybox-inline-box {
    width: 350px; }
    .fancybox-inline-box .inline-embed-iframe,
    .fancybox-inline-box .inline-embed-video {
      height: 187px; } }
@media (max-width: 360px) {
  .fancybox-inline-box {
    width: 250px; }
    .fancybox-inline-box .inline-embed-iframe,
    .fancybox-inline-box .inline-embed-video {
      height: 150px; } }
/**
 * 11.6- Section Timeline
 */
.timeline {
  position: relative; }
  .timeline .timeline-bar {
    content: '';
    width: 4px;
    opacity: 0.2;
    margin-left: -2px;
    position: absolute;
    left: 50%;
    top: 0;
    height: 100%; }
  .timeline .timeline-inner {
    position: relative; }

.timeline-box {
  width: 50%;
  color: #757575;
  font-size: 16px;
  line-height: 1.5;
  margin-bottom: 25px;
  position: relative; }
  .timeline-box:last-child {
    margin-bottom: 0; }
  .timeline-box h3 {
    color: #414141;
    font-size: 22px;
    font-weight: 400;
    line-height: 1.1;
    text-align: center;
    margin-bottom: 20px; }
  .timeline-box h4 {
    color: #878787;
    font-size: 13px;
    font-weight: 400;
    line-height: 1.1;
    text-transform: uppercase;
    text-align: center;
    margin-bottom: 30px; }
  .timeline-box .date {
    font-size: 16px;
    font-weight: 700;
    line-height: 1;
    text-align: center;
    margin-bottom: 15px; }

.timeline-box-compact .date, .timeline-box-compact h3, .timeline-box-compact h4 {
  text-align: left; }
.timeline-box-compact .date span {
  color: #fff;
  font-size: 14px;
  font-weight: 700;
  line-height: 1;
  display: inline-block;
  position: relative;
  padding: 5px 8px;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px; }
  .timeline-box-compact .date span:before {
    content: '';
    width: 0;
    height: 0;
    top: 100%;
    left: 5px;
    display: block;
    position: absolute;
    border-style: solid;
    border-width: 0 0 8px 8px;
    border-color: transparent; }

.timeline-box-inner {
  padding: 20px 5%;
  position: relative;
  border-width: 5px 0 0 0;
  border-style: solid; }

.timeline-box-left .dot,
.timeline-box-right .dot {
  top: 80px;
  width: 8px;
  height: 8px;
  display: block;
  position: absolute;
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%; }
.timeline-box-left .arrow,
.timeline-box-right .arrow {
  top: 60px;
  width: 12px;
  height: 41px;
  display: block;
  position: absolute;
  background-image: url(img/arrows.png);
  background-repeat: no-repeat; }
  .timeline-box-left .arrow:before,
  .timeline-box-right .arrow:before {
    width: 0;
    height: 0;
    content: '';
    display: block; }

.timeline-box-left {
  float: left;
  clear: left; }
  .timeline-box-left .timeline-box-inner {
    margin-right: 35px; }
    .timeline-box-left .timeline-box-inner .arrow {
      right: -12px;
      background-position: -18px 0; }
      .timeline-box-left .timeline-box-inner .arrow:before {
        margin-right: 2px;
        border-top: 20px solid transparent;
        border-bottom: 20px solid transparent;
        border-left: 10px solid #fff; }
  .timeline-box-left .dot {
    right: 0px;
    margin-right: -4px; }

.timeline-box-right {
  float: right;
  clear: right; }
  .timeline-box-right .timeline-box-inner {
    margin-left: 35px; }
    .timeline-box-right .timeline-box-inner .arrow {
      left: -12px;
      background-position: 0 0; }
      .timeline-box-right .timeline-box-inner .arrow:before {
        margin-left: 2px;
        border-top: 20px solid transparent;
        border-bottom: 20px solid transparent;
        border-right: 10px solid #fff; }
  .timeline-box-right .dot {
    left: 0px;
    margin-left: -4px; }

@media (max-width: 600px) {
  .timeline-box {
    width: 100%;
    float: none;
    margin-left: 0;
    margin-right: 0; }
    .timeline-box .timeline-box-inner {
      margin-left: 0;
      margin-right: 0; }
      .timeline-box .timeline-box-inner .arrow {
        display: none; }
    .timeline-box .dot {
      display: none; } }
/**
 * 11.7 - Section References
 */
.section-references .section-box {
  padding: 0 105px 0 25px;
  position: relative; }

.ref-slider {
  margin: 0;
  padding: 0;
  list-style: none; }
  .ref-slider li {
    margin: 0;
    padding: 0; }

.ref-slider-nav {
  position: absolute;
  right: 25px;
  top: 25px; }
  .ref-slider-nav .slider-prev,
  .ref-slider-nav .slider-next {
    display: block;
    width: 58px;
    height: 58px;
    margin-bottom: 8px; }
    .ref-slider-nav .slider-prev .rsicon,
    .ref-slider-nav .slider-next .rsicon {
      color: #3e4452;
      font-size: 30px;
      line-height: 58px; }
    .ref-slider-nav .slider-prev a,
    .ref-slider-nav .slider-next a {
      width: 100%;
      height: 100%;
      display: block;
      text-align: center;
      border: 1px solid #d7dbde;
      -webkit-transition: box-shadow 0.3s ease-out;
      -moz-transition: box-shadow 0.3s ease-out;
      transition: box-shadow 0.3s ease-out; }
      .ref-slider-nav .slider-prev a:hover,
      .ref-slider-nav .slider-next a:hover {
        box-shadow: 0 1px 6px rgba(0, 0, 0, 0.12), 0 1px 4px rgba(0, 0, 0, 0.24); }

.ref-box {
  padding: 55px 75px 40px 80px; }
  .ref-box .person-speech {
    font-size: 18px;
    font-weight: 400;
    line-height: 1.4;
    position: relative;
    padding-bottom: 27px;
    border-bottom: 1px solid #dddad9; }
    .ref-box .person-speech p:last-child {
      margin-bottom: 0; }
    .ref-box .person-speech:before {
      content: "\e61c";
      top: 2px;
      left: -55px;
      position: absolute;
      font-size: 23px;
      line-height: 1; }
  .ref-box .person-info {
    padding-top: 25px; }
  .ref-box .person-img {
    width: 53px;
    float: left;
    display: block;
    margin-right: 22px;
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px; }
  .ref-box .person-name-title {
    padding-top: 10px; }
  .ref-box .person-name {
    color: #757575;
    font-size: 20px;
    font-weight: 700;
    line-height: 1.1;
    display: block;
    margin-bottom: 3px; }
  .ref-box .person-title {
    color: #d0d0d0;
    font-size: 13px;
    font-weight: 400;
    line-height: 1.1;
    text-transform: uppercase; }

@media (max-width: 767px) {
  .ref-box {
    padding: 30px 0 30px 45px; }
    .ref-box .person-speech:before {
      left: -43px; } }
@media (max-width: 480px) {
  .section-references .section-box {
    padding-right: 25px; }

  .ref-slider-nav .slider-prev,
  .ref-slider-nav .slider-next {
    display: none; }

  .ref-box {
    padding-top: 35px;
    padding-left: 0; }
    .ref-box .person-img {
      margin-right: 10px; }
    .ref-box .person-name {
      font-size: 15px; }
    .ref-box .ref-box .person-title {
      font-size: 11px; }
    .ref-box .person-speech {
      text-align: center; }
      .ref-box .person-speech:before {
        font-size: 15px;
        left: 50%;
        top: -20px; } }
/**
 * 11.8 - Section Calendar
 */
.calendar-busy {
  position: relative; }
  .calendar-busy .calendar-cont {
    padding: 35px 35px 0 35px;
    margin-left: 35%; }
  .calendar-busy .calendar-header {
    margin-bottom: 15px; }
    .calendar-busy .calendar-header:before, .calendar-busy .calendar-header:after {
      content: " ";
      display: table; }
    .calendar-busy .calendar-header:after {
      clear: both; }
    .calendar-busy .calendar-header {
      *zoom: 1; }
  .calendar-busy .calendar-today {
    color: #fff;
    line-height: 1;
    font-weight: 300;
    position: absolute;
    left: 0;
    top: 0;
    width: 35%;
    height: 100%;
    text-align: center;
    background-size: cover;
    background-color: #242832;
    background-repeat: no-repeat;
    background-position: center center; }
    .calendar-busy .calendar-today:after {
      z-index: 1;
      content: '';
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      position: absolute;
      background: rgba(44, 51, 64, 0.8); }
    .calendar-busy .calendar-today .valign-outer {
      z-index: 2;
      position: relative; }
    .calendar-busy .calendar-today .date {
      position: relative;
      margin: 0 auto 13%;
      width: 53%;
      padding: 11% 5%;
      -webkit-border-radius: 7px;
      -moz-border-radius: 7px;
      border-radius: 7px; }
      .calendar-busy .calendar-today .date:before, .calendar-busy .calendar-today .date:after {
        content: '';
        position: absolute;
        top: -6px;
        width: 3px;
        height: 12px;
        background-color: #fff;
        -webkit-border-radius: 38%;
        -moz-border-radius: 38%;
        border-radius: 38%; }
      .calendar-busy .calendar-today .date:before {
        left: 30%; }
      .calendar-busy .calendar-today .date:after {
        right: 30%; }
    .calendar-busy .calendar-today .day {
      font-size: 74px;
      display: block;
      margin-bottom: 8px; }
    .calendar-busy .calendar-today .month {
      display: block;
      font-size: 33px;
      letter-spacing: 0.2em; }
    .calendar-busy .calendar-today .week-day {
      font-size: 36px;
      letter-spacing: 0.08em; }
  .calendar-busy .calendar-nav {
    float: left;
    padding: 0 25px;
    position: relative;
    font-size: 16px;
    line-height: 1.1; }
    .calendar-busy .calendar-nav .active-date {
      color: #333333;
      font-weight: 600;
      text-transform: uppercase;
      display: inline-block;
      overflow: hidden;
      width: 145px;
      text-align: center; }
    .calendar-busy .calendar-nav .active-month,
    .calendar-busy .calendar-nav .active-year {
      opacity: 1;
      display: inline-block;
      -webkit-transform: translate3d(0px, 0px, 0px);
      -moz-transform: translate3d(0px, 0px, 0px);
      transform: translate3d(0px, 0px, 0px);
      -webkit-transition: -webkit-transform 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      -moz-transition: -moz-transform 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;
      transition: transform 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 300ms cubic-bezier(0.23, 1, 0.32, 1) 0ms; }
      .calendar-busy .calendar-nav .active-month.moveup,
      .calendar-busy .calendar-nav .active-year.moveup {
        opacity: 0;
        -webkit-transform: translate3d(0px, -20px, 0px);
        -moz-transform: translate3d(0px, -20px, 0px);
        transform: translate3d(0px, -20px, 0px); }
      .calendar-busy .calendar-nav .active-month.movedown,
      .calendar-busy .calendar-nav .active-year.movedown {
        opacity: 0;
        -webkit-transform: translate3d(0px, 20px, 0px);
        -moz-transform: translate3d(0px, 20px, 0px);
        transform: translate3d(0px, 20px, 0px);
        -webkit-transition: -webkit-transform 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;
        -moz-transition: -moz-transform 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms;
        transition: transform 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms; }
    .calendar-busy .calendar-nav .active-month {
      margin-right: 7px; }
    .calendar-busy .calendar-nav .calendar-next,
    .calendar-busy .calendar-nav .calendar-prev {
      top: -5px;
      position: absolute;
      display: block;
      cursor: pointer; }
    .calendar-busy .calendar-nav .calendar-next {
      right: -3px; }
    .calendar-busy .calendar-nav .calendar-prev {
      left: -3px; }
    .calendar-busy .calendar-nav .rsicon {
      color: #cccccc;
      font-size: 26px; }
  .calendar-busy .calendar-body {
    border: none; }
    .calendar-busy .calendar-body th,
    .calendar-busy .calendar-body td {
      width: 14.2857%;
      border: none;
      text-align: center;
      vertical-align: middle; }
    .calendar-busy .calendar-body th {
      color: #757575;
      font-size: 14px;
      font-weight: 700;
      line-height: 1;
      text-transform: uppercase;
      padding: 13px 5px; }
    .calendar-busy .calendar-body td {
      color: #000;
      font-size: 16px;
      font-weight: 400;
      padding: 5px 0; }
      .calendar-busy .calendar-body td span {
        width: 36px;
        height: 36px;
        line-height: 36px;
        display: block;
        margin: 0 auto; }
      .calendar-busy .calendar-body td .busy-day,
      .calendar-busy .calendar-body td .current-day {
        color: #fff;
        -webkit-border-radius: 3px;
        -moz-border-radius: 3px;
        border-radius: 3px; }
      .calendar-busy .calendar-body td .busy-day {
        background-color: #cacaca !important; }
  .calendar-busy .calendar-busy-note {
    color: #373b42;
    font-size: 12px;
    line-height: 1.25;
    border-top: 1px solid #e1e1e1;
    padding: 18px 0 18px 35px;
    margin: 0 12px;
    position: relative; }
    .calendar-busy .calendar-busy-note:before {
      content: '';
      position: absolute;
      left: 3px;
      top: 0;
      width: 14px;
      height: 14px;
      margin: 18px 0;
      background-color: #cacaca;
      -webkit-border-radius: 3px;
      -moz-border-radius: 3px;
      border-radius: 3px; }
  .calendar-busy .calendar-body {
    overflow: hidden; }
  .calendar-busy .calendar-tbody {
    opacity: 1;
    transform: translate3d(0px, 0px, 0px);
    transition: transform 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 450ms cubic-bezier(0.23, 1, 0.32, 1) 0ms; }
    .calendar-busy .calendar-tbody.moveright {
      opacity: 0;
      transform: translate3d(-50px, 0px, 0px); }
    .calendar-busy .calendar-tbody.moveleft {
      opacity: 0;
      transform: translate3d(50px, 0px, 0px);
      transition: transform 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms, opacity 0ms cubic-bezier(0.23, 1, 0.32, 1) 0ms; }

@media (max-width: 767px) {
  .calendar-busy .calendar-body th {
    font-size: 11px; }
  .calendar-busy .calendar-body td {
    font-size: 14px; }
  .calendar-busy .calendar-today {
    width: 40%; }
    .calendar-busy .calendar-today .date {
      width: 63%; }
    .calendar-busy .calendar-today .week-day {
      font-size: 29px; }
  .calendar-busy .calendar-cont {
    margin-left: 40%;
    padding-left: 17px;
    padding-right: 17px; } }
@media (max-width: 480px) {
  .calendar-busy .calendar-nav {
    float: none;
    text-align: center; }
  .calendar-busy .calendar-today {
    position: relative;
    left: auto;
    top: auto;
    width: 100%;
    height: auto;
    padding: 20px 15px; }
    .calendar-busy .calendar-today .date {
      padding: 0;
      background: none !important;
      margin-bottom: 15px; }
      .calendar-busy .calendar-today .date:before, .calendar-busy .calendar-today .date:after {
        display: none; }
    .calendar-busy .calendar-today .day,
    .calendar-busy .calendar-today .month {
      display: inline-block;
      font-size: 45px;
      letter-spacing: 0;
      margin: 0 5px; }
    .calendar-busy .calendar-today .week-day {
      font-size: 25px; }
  .calendar-busy .calendar-cont {
    margin-left: 0; } }
/**
 * 11.9 - Section Contact
 */
.contact-info.section-box {
  padding: 0; }
.contact-info.has-map {
  position: relative;
  padding-bottom: 266px; }
.contact-info iframe {
  display: block; }
.contact-info .contact-list {
  list-style: none;
  padding: 45px 35px 30px;
  margin: 0; }
  .contact-info .contact-list li {
    margin-bottom: 10px; }
  .contact-info .contact-list strong, .contact-info .contact-list span {
    display: block; }
  .contact-info .contact-list strong {
    font-size: 13px;
    font-weight: 400;
    text-transform: uppercase;
    width: 85px;
    float: left; }
  .contact-info .contact-list span {
    font-size: 16px;
    font-weight: 400;
    margin-left: 90px; }
  .contact-info .contact-list a {
    color: inherit;
    -webkit-transition: opacity 0.15s linear 0s;
    -moz-transition: opacity 0.15s linear 0s;
    transition: opacity 0.15s linear 0s; }
    .contact-info .contact-list a:hover {
      opacity: 0.6;
      text-decoration: none; }

.contactForm h3 {
  font-size: 20px;
  line-height: 1.1;
  font-weight: 700;
  text-transform: uppercase;
  margin-bottom: 42px; }
.contactForm.section-box {
  padding: 45px 35px 25px 35px; }

#map {
  width: 100%;
  height: 266px;
  position: absolute;
  left: 0;
  bottom: 0; }
  #map .map-icon {
    font-size: 55px;
    line-height: 55px;
    text-align: center;
    white-space: nowrap; }

@media (max-width: 767px) {
  .contact-form {
    margin-bottom: 35px; }

  .contactForm.section-box,
  .contact-info .contact-list {
    padding: 30px 25px; } }
@media (max-width: 480px) {
  .contact-info .contact-list dt, .contact-info .contact-list dd {
    width: 100%;
    float: none; }
  .contact-info .contact-list dt {
    margin-bottom: 0; }
  .contact-info .contact-list dd {
    margin-left: 0; } }
/**
 * 11.10 - Section Prices
 */
.section-prices .section-box {
  padding: 0; }
.section-prices .row {
  margin-left: 0;
  margin-right: 0; }
.section-prices div[class^="col-"] {
  padding-left: 0;
  padding-right: 0; }

.price-list {
  margin-bottom: 25px; }

.price-box {
  text-align: center;
  position: relative;
  z-index: 0; }
  .price-box .btn-wrap {
    position: absolute;
    left: 0;
    bottom: 35px;
    width: 100%;
    text-align: center; }

.price-box-top {
  color: #fff;
  font-weight: 300;
  padding: 23px 20px;
  background-color: #373b42;
  position: relative; }
  .price-box-top:before {
    content: '';
    width: 0;
    height: 0;
    border-left: 11px solid transparent;
    border-right: 11px solid transparent;
    border-top: 7px solid #373b42;
    position: absolute;
    left: 50%;
    margin-left: -11px;
    bottom: -7px; }
  .price-box-top span,
  .price-box-top small {
    margin: 0 5px;
    display: inline-block; }
  .price-box-top span {
    font-size: 45px; }
  .price-box-top small {
    font-size: 18px; }

.price-box-content {
  color: #818181;
  font-size: 16px;
  line-height: 1.2;
  padding: 50px 20px 100px 20px; }
  .price-box-content h3 {
    color: #373b42;
    font-size: 20px;
    font-weight: 700;
    text-transform: uppercase;
    margin-bottom: 30px; }
  .price-box-content ul {
    margin: 0;
    padding: 0;
    list-style: none; }
  .price-box-content li {
    margin-bottom: 20px; }
  .price-box-content .new {
    color: #fff;
    font-size: 10px;
    line-height: 12px;
    text-transform: uppercase;
    padding: 0 6px;
    margin-left: 5px;
    background-color: #f44459;
    -webkit-border-radius: 2px;
    -moz-border-radius: 2px;
    border-radius: 2px; }

.box-primary {
  z-index: 1; }
  .box-primary .price-box-content .btn {
    color: #fff !important; }

@media (max-width: 767px) {
  .price-list {
    margin-bottom: 0; }
    .price-list .col-sm-4 .price-box {
      margin-bottom: 25px; }
    .price-list .col-sm-4:last-child .price-box {
      margin-bottom: 0; } }
/**
 * 11.11 - Section Clients
 */
.section-clients .client-logo {
  text-align: center;
  line-height: 60px; }
  .section-clients .client-logo img {
    max-width: 100%;
    max-height: 60px;
    filter: gray;
    filter: grayscale(1);
    -webkit-filter: grayscale(1);
    -webkit-transition: all 0.15s linear 0s;
    -moz-transition: all 0.15s linear 0s;
    transition: all 0.15s linear 0s; }
  .section-clients .client-logo a,
  .section-clients .client-logo img {
    display: inline-block; }
  .section-clients .client-logo > a, .section-clients .client-logo > img {
    max-width: 75%; }
  .section-clients .client-logo > a:hover img, .section-clients .client-logo > img:hover {
    filter: none;
    -webkit-filter: grayscale(0); }

/**
 * 12.0 - Blog
 */
.section-blog .section-title {
  margin-bottom: 0; }
.section-blog .grid-item {
  margin-bottom: 0 !important;
  margin-top: 25px; }

/**
 * 12.1 - Blog General
 */
.post-title {
  color: #373b42;
  font-size: 20px;
  line-height: 1.3;
  font-weight: 700;
  text-transform: uppercase; }

.post-info {
  font-size: 13px;
  line-height: 1.3; }
  .post-info a {
    color: #757575 !important;
    margin-right: 20px; }
    .post-info a:last-child {
      margin-right: 0; }
  .post-info .rsicon {
    color: #ccc;
    margin-right: 10px; }

.post-datetime {
  width: 58px;
  height: 58px;
  color: #fff;
  line-height: 1;
  font-weight: 700;
  text-align: center;
  position: absolute;
  top: 20px;
  right: 20px;
  padding-top: 11px;
  display: block; }
  .post-datetime .day {
    font-size: 20px;
    margin-bottom: 2px; }
  .post-datetime .month {
    font-size: 13px; }
  .post-datetime span {
    display: block; }

.post-tag {
  font-size: 11px;
  font-weight: 400;
  line-height: 1.2;
  margin-bottom: 26px; }
  .post-tag a {
    color: #757575 !important;
    font-weight: 700;
    text-transform: uppercase;
    margin-right: 3px; }

.post-data {
  text-align: center; }

.post-embed {
  width: 100%;
  height: 0;
  padding: 57% 0 0 0;
  display: block;
  overflow: hidden;
  position: relative; }

.post-embed-item {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: 0; }

.post-slider {
  margin: 0;
  padding: 0;
  list-style: none; }
  .post-slider img {
    -webkit-transition: opacity 1s;
    -moz-transition: opacity 1s;
    transition: opacity 1s; }

.post-slider-arrows {
  top: 100px;
  right: 30px;
  position: absolute; }
  .post-slider-arrows a, .post-slider-arrows .rsicon {
    width: 100%;
    height: 100%;
    line-height: 37px; }
  .post-slider-arrows a {
    display: block;
    text-align: center;
    width: 37px;
    height: 37px;
    margin-bottom: 8px;
    background-color: #000;
    background-color: rgba(0, 0, 0, 0.5);
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-transition: background-color 0.15s linear 0s;
    -moz-transition: background-color 0.15s linear 0s;
    transition: background-color 0.15s linear 0s;
    -webkit-border-radius: 3px;
    -moz-border-radius: 3px;
    border-radius: 3px; }
    .post-slider-arrows a:hover {
      text-decoration: none;
      background-color: #000;
      background-color: rgba(0, 0, 0, 0.8); }
  .post-slider-arrows .rsicon {
    color: #fff;
    font-size: 25px;
    display: block; }

/**
 * 12.2 - Blog Post Box
 */
.blog-grid {
  margin-left: -12px;
  margin-right: -12px; }
  .blog-grid:before, .blog-grid:after {
    content: " ";
    display: table; }
  .blog-grid:after {
    clear: both; }
  .blog-grid {
    *zoom: 1; }
  .blog-grid .grid-item,
  .blog-grid .grid-sizer {
    width: 50%; }
  .blog-grid .grid-sizer {
    height: 0;
    visibility: hidden; }
  .blog-grid .grid-item {
    float: left;
    padding: 0 12px;
    margin-bottom: 25px; }

.post-box .post-title a,
.post-single .post-title a {
  color: inherit;
  -webkit-transition: color 0.15s linear 0s;
  -moz-transition: color 0.15s linear 0s;
  transition: color 0.15s linear 0s; }
  .post-box .post-title a:hover,
  .post-single .post-title a:hover {
    text-decoration: none; }

.post-box {
  position: relative;
  background-color: #fff;
  -webkit-transition: box-shadow 0.15s linear 0s;
  -moz-transition: box-shadow 0.15s linear 0s;
  transition: box-shadow 0.15s linear 0s;
  -webkit-backface-visibility: hidden;
  -moz-backface-visibility: hidden;
  backface-visibility: hidden; }
  .post-box .post-type-icon {
    left: 20px;
    bottom: 20px;
    width: 70px;
    height: 44px;
    display: block;
    position: absolute;
    text-align: center;
    background-color: #202734;
    background-color: rgba(32, 39, 52, 0.8);
    -webkit-border-radius: 5px;
    -moz-border-radius: 5px;
    border-radius: 5px; }
    .post-box .post-type-icon .rsicon {
      color: #fff;
      line-height: 44px;
      font-size: 20px;
      display: block; }
  .post-box .post-media {
    overflow: hidden;
    position: relative;
    background-color: #2c3340; }
    .post-box .post-media.no-media {
      padding-top: 58px;
      background-color: #f7f7f7; }
    .post-box .post-media img {
      width: 100%;
      height: auto;
      opacity: 0.8;
      display: block;
      position: relative;
      -webkit-backface-visibility: hidden;
      -moz-backface-visibility: hidden;
      backface-visibility: hidden; }
  .post-box .post-data {
    padding: 25px 25px 35px 25px; }
  .post-box .post-image img {
    -webkit-transition: opacity 1s, transform 1s;
    -moz-transition: opacity 1s, transform 1s;
    transition: opacity 1s, transform 1s; }
  .post-box:hover {
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.19), 0 6px 10px rgba(0, 0, 0, 0.23); }
    .post-box:hover .post-slider img {
      opacity: 1; }
    .post-box:hover .post-image img {
      opacity: 1;
      -webkit-transform: scale3d(1.1, 1.1, 1);
      -moz-transform: scale3d(1.1, 1.1, 1);
      transform: scale3d(1.1, 1.1, 1); }

@media (max-width: 668px) {
  .blog-grid {
    margin-left: 0;
    margin-right: 0; }
    .blog-grid .grid-item,
    .blog-grid .grid-sizer {
      width: 100%; }
    .blog-grid .grid-item {
      padding-left: 0;
      padding-right: 0; } }
/**
 * 12.3 - Post Page
 */
.post-single .post-title-wrap {
  position: relative; }
.post-single .post-datetime {
  top: 0;
  left: -60px; }
.post-single .post-media {
  position: relative; }
  .post-single .post-media img {
    width: 100%;
    display: block; }
.post-single .post-slider-arrows {
  top: auto;
  bottom: 40px; }
.post-single .post-content {
  padding: 0;
  margin-bottom: 30px; }
.post-single .post-inner {
  padding: 0 50px 40px; }
.post-single .post-header {
  position: relative;
  padding-top: 30px;
  margin-bottom: 40px; }
.post-single .post-footer {
  margin-top: 10px; }
.post-single .post-audio-wrap {
  padding: 25px 20px;
  background-color: #f7f7f7; }
.post-single .post-comments {
  padding-top: 0; }

.post-pagination {
  margin-bottom: 50px;
  padding: 0; }
  .post-pagination .post-next,
  .post-pagination .post-prev {
    padding: 30px 50px; }
  .post-pagination .post-next {
    border-bottom: 1px solid #ccc; }
  .post-pagination .post-tag {
    font-size: 12px; }
  .post-pagination .post-title {
    margin-bottom: 15px; }

/**
 * 12.4 - Post Comments
 */
.post-comments {
  padding-top: 70px; }
  .post-comments .section-title {
    font-size: 26px;
    text-align: left; }
  .post-comments .section-box {
    padding-top: 30px;
    padding-bottom: 20px; }
  .post-comments .section-title,
  .post-comments .section-box {
    padding-left: 30px;
    padding-right: 30px; }

.comment-list, .comment-list ol {
  margin: 0;
  padding: 0;
  list-style: none; }
.comment-list .comment-avatar {
  width: 64px;
  height: 64px;
  float: left;
  display: block;
  box-shadow: 0 0px 5px rgba(0, 0, 0, 0.2), 0 2px 5px rgba(0, 0, 0, 0.17);
  -webkit-border-radius: 50%;
  -moz-border-radius: 50%;
  border-radius: 50%; }
  .comment-list .comment-avatar img {
    width: 100%;
    display: block;
    -webkit-border-radius: 50%;
    -moz-border-radius: 50%;
    border-radius: 50%; }
.comment-list .comment-meta {
  padding-bottom: 15px;
  margin-bottom: 10px;
  position: relative; }
  .comment-list .comment-meta:after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 65px;
    height: 1px;
    background-color: #ccc; }
  .comment-list .comment-meta .name {
    color: #000;
    font-size: 18px;
    font-weight: 400;
    line-height: 1.1;
    margin-bottom: 5px;
    display: block; }
  .comment-list .comment-meta .date {
    color: #757575;
    font-size: 13px;
    font-weight: 400;
    line-height: 1.1;
    display: inline-block;
    margin-right: 5px; }
  .comment-list .comment-meta .reply-link {
    font-size: 13px;
    font-weight: 400;
    display: inline-block; }
.comment-list .comment-content {
  margin-left: 90px; }
.comment-list .comment {
  margin-bottom: 40px; }
  .comment-list .comment:last-child {
    margin-bottom: 0; }
  .comment-list .comment .comment {
    margin-top: 20px;
    margin-left: 55px; }

.comment-reply {
  margin-top: 45px; }
  .comment-reply .input-field label {
    text-transform: none;
    color: #9a9a9a; }

@media (max-width: 767px) {
  .comment .comment {
    margin-left: 35px; }
  .comment .comment-avatar {
    width: 40px;
    height: 40px; }
  .comment .comment-content {
    margin-left: 60px; } }
@media (max-width: 480px) {
  .comment-list .comment .comment {
    margin-left: 0; } }
/**
 * 13.0 - Error Page
 */
.header-has-img .page-404 {
  margin-top: 170px; }

.page-404 {
  color: #000000;
  font-size: 30px;
  font-weight: 300;
  text-align: center;
  padding: 50px 0; }
  .page-404 p {
    margin-bottom: 60px; }
  .page-404 h2 {
    color: #d1d1d1;
    font-size: 170px;
    line-height: 1;
    font-weight: 700;
    margin-bottom: 40px; }
    .page-404 h2 span {
      margin: 0 10px;
      position: relative;
      display: inline-block; }
      .page-404 h2 span:before {
        content: '';
        width: 0;
        height: 0;
        left: 50%;
        bottom: 5px;
        display: block;
        margin-left: -10px;
        position: absolute;
        border-style: solid;
        border-width: 0px 0px 15px 17px;
        border-color: transparent;
        -webkit-transform: rotate(15deg);
        -moz-transform: rotate(15deg);
        transform: rotate(15deg); }
  .page-404 .btn {
    color: #a7a7a7 !important;
    width: 100%;
    max-width: 256px;
    display: block;
    margin: 0 auto; }

@media (max-width: 480px) {
  .page-404 {
    font-size: 25px; }
    .page-404 h2 {
      font-size: 120px; } }
/**
 * 14.0 - Footer
 */
.footer-social {
  padding: 30px 0; }
  .footer-social .social li a .rsicon {
    color: #d7d7d7;
    -webkit-transition: -webkit-transition, color 0.25s linear 0s;
    -moz-transition: -moz-transition, color 0.25s linear 0s;
    transition: transition, color 0.25s linear 0s; }
  .footer-social .social li a:hover .rsicon {
    color: #6e6e6e; }

@media (max-width: 767px) {
  .footer {
    padding-bottom: 30px; } }
/**
 * 15.0 - Theme dark
 */
.theme-skin-dark body {
  color: #9c9c9c;
  background-color: #27292e; }
.theme-skin-dark hr {
  background-color: #302f32; }
.theme-skin-dark table, .theme-skin-dark th, .theme-skin-dark td {
  border-color: #515056; }
.theme-skin-dark .section-title {
  color: #7C7D82; }
.theme-skin-dark .grid-box,
.theme-skin-dark .post-box,
.theme-skin-dark .price-box,
.theme-skin-dark .section-box,
.theme-skin-dark .calendar-busy,
.theme-skin-dark .timeline-box-inner {
  background-color: #35363b; }
.theme-skin-dark #preloader {
  background-color: #35363b; }
.theme-skin-dark ::-webkit-input-placeholder {
  color: #8f9094; }
.theme-skin-dark :-moz-placeholder {
  color: #8f9094; }
.theme-skin-dark ::-moz-placeholder {
  color: #8f9094;
  opacity: 1; }
.theme-skin-dark :-ms-input-placeholder {
  color: #8f9094; }
.theme-skin-dark select,
.theme-skin-dark textarea,
.theme-skin-dark input[type='tel'],
.theme-skin-dark input[type='text'],
.theme-skin-dark input[type='email'],
.theme-skin-dark input[type='search'],
.theme-skin-dark input[type='password'] {
  color: #9c9c9c;
  border-color: #56565e; }
.theme-skin-dark .input-field input,
.theme-skin-dark .input-field textarea {
  border-bottom-color: #1f2125; }
.theme-skin-dark .input-field label {
  color: #9c9c9c; }
.theme-skin-dark .section-box .input-field input,
.theme-skin-dark .section-box .input-field textarea {
  border-bottom-color: #474d56; }
.theme-skin-dark .section-box .input-field label {
  color: #9c9c9c; }
.theme-skin-dark blockquote cite:before {
  background-color: #4d4c51; }
.theme-skin-dark blockquote cite, .theme-skin-dark blockquote small {
  color: #99999b; }
.theme-skin-dark .btn-border {
  color: #9d9ea2  !important;
  border-color: #474d56; }
.theme-skin-dark .btn-primary {
  color: #35363b; }
.theme-skin-dark .ripple-effect {
  background-color: rgba(255, 255, 255, 0.15); }
.theme-skin-dark .btn-scroll-top {
  border: 1px solid #2b2e35;
  border: 1px solid rgba(0, 0, 0, 0.2);
  background-color: rgba(0, 0, 0, 0.02); }
  .theme-skin-dark .btn-scroll-top:hover {
    background-color: #2e3035; }
  .theme-skin-dark .btn-scroll-top .rsicon {
    color: #2b2e35;
    color: rgba(0, 0, 0, 0.2); }
.theme-skin-dark .rs-icons-list li {
  border-color: #35363b; }
.theme-skin-dark .social li a .rsicon {
  color: #27292e; }
.theme-skin-dark .mejs-container .mejs-controls {
  background-color: #1B1B1D; }
  .theme-skin-dark .mejs-container .mejs-controls:before, .theme-skin-dark .mejs-container .mejs-controls:after {
    background-color: #27292e; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-playpause-button {
    border-left: 1px solid #27292e;
    border-right: 1px solid #27292e; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-volume-button {
    border-left: 1px solid #27292e; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-fullscreen-button,
  .theme-skin-dark .mejs-container .mejs-controls .mejs-horizontal-volume-slider {
    border-right: 1px solid #27292e; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-time {
    color: #4e4e50; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-time-rail .mejs-time-total {
    background-color: #3B3C40; }
  .theme-skin-dark .mejs-container .mejs-controls .mejs-time-rail .mejs-time-loaded {
    background-color: #737780; }
.theme-skin-dark .btn-sidebar-close .rsicon {
  color: #35363b; }
.theme-skin-dark .sidebar-fixed {
  background-color: #2d2d35; }
.theme-skin-dark .widget-profile,
.theme-skin-dark .widget-recent-posts li,
.theme-skin-dark .widget-popuplar-posts li,
.theme-skin-dark .widget_meta ul li,
.theme-skin-dark .widget_archive ul li,
.theme-skin-dark .widget_nav_menu ul li,
.theme-skin-dark .widget_categories ul li,
.theme-skin-dark .widget_recent_entries ul li,
.theme-skin-dark .widget_recent_comments ul li,
.theme-skin-dark .widget_calendar thead th,
.theme-skin-dark .widget_calendar tfoot td {
  border-color: #1f2125; }
.theme-skin-dark .widget_meta ul li,
.theme-skin-dark .widget_archive ul li,
.theme-skin-dark .widget_nav_menu ul li,
.theme-skin-dark .widget_categories ul li,
.theme-skin-dark .widget_recent_entries ul li,
.theme-skin-dark .widget_recent_comments ul li {
  color: #57575f; }
.theme-skin-dark .widget_meta ul li a,
.theme-skin-dark .widget_archive ul li a,
.theme-skin-dark .widget_nav_menu ul li a,
.theme-skin-dark .widget_categories ul li a,
.theme-skin-dark .widget_recent_entries ul li a,
.theme-skin-dark .widget_recent_comments ul li a {
  color: #9d9ea2; }
.theme-skin-dark .widget_calendar caption {
  color: #97989c; }
.theme-skin-dark .widget_calendar td {
  color: #57585d; }
.theme-skin-dark .widget_tag_cloud a {
  color: #56565e;
  border-color: #56565e; }
  .theme-skin-dark .widget_tag_cloud a:hover {
    color: #201f27 !important; }
.theme-skin-dark .widget-profile .profile-title,
.theme-skin-dark .widget-profile .profile-position {
  color: #d4d4d5; }
.theme-skin-dark .head-bar,
.theme-skin-dark .header-has-img .head-sticky.head-bar {
  background-color: #27292e; }
.theme-skin-dark .nav-wrap .nav > ul > li > a,
.theme-skin-dark .header-has-img .head-sticky .nav-wrap .nav > ul > li > a {
  color: #9a9da2; }
.theme-skin-dark .nav-wrap .btn-mobile-nav,
.theme-skin-dark .nav-wrap .btn-sidebar-open,
.theme-skin-dark .header-has-img .head-sticky .nav-wrap .btn-mobile-nav,
.theme-skin-dark .header-has-img .head-sticky .nav-wrap .btn-sidebar-open {
  border-color: #4d4c51; }
  .theme-skin-dark .nav-wrap .btn-mobile-nav .rsicon,
  .theme-skin-dark .nav-wrap .btn-sidebar-open .rsicon,
  .theme-skin-dark .header-has-img .head-sticky .nav-wrap .btn-mobile-nav .rsicon,
  .theme-skin-dark .header-has-img .head-sticky .nav-wrap .btn-sidebar-open .rsicon {
    color: #9a9da2; }
.theme-skin-dark .nav-wrap .nav > ul > li ul {
  background-color: #212026; }
  .theme-skin-dark .nav-wrap .nav > ul > li ul a {
    color: #fff; }
    .theme-skin-dark .nav-wrap .nav > ul > li ul a:hover {
      background-color: #27292e; }
.theme-skin-dark .header-has-img .head-bar {
  background-color: transparent; }
.theme-skin-dark .header-has-img .nav-wrap .nav > ul > li > a {
  color: #fff;
  color: rgba(255, 255, 255, 0.7); }
.theme-skin-dark .header-has-img .nav-wrap .btn-mobile-nav,
.theme-skin-dark .header-has-img .nav-wrap .btn-sidebar-open {
  border-color: #4f5159; }
  .theme-skin-dark .header-has-img .nav-wrap .btn-mobile-nav .rsicon,
  .theme-skin-dark .header-has-img .nav-wrap .btn-sidebar-open .rsicon {
    color: #fff; }
.theme-skin-dark .profile-preword span,
.theme-skin-dark .timeline-box-compact .date span,
.theme-skin-dark .profile-list .button {
  color: #27292e; }
.theme-skin-dark .section-about .profile-info {
  color: #d4d4d5;
  border-color: #47494c; }
.theme-skin-dark .profile-list .title {
  color: #d4d4d5; }
.theme-skin-dark .profile-list .cont {
  color: #84898e; }
.theme-skin-dark .section-txt-btn {
  color: #ffffff; }
.theme-skin-dark .profile-line {
  background-color: #222227; }
.theme-skin-dark .interests-list li {
  border-color: #47494C; }
.theme-skin-dark .interests-list li span {
  background-color: #222227; }
.theme-skin-dark .filter-bar {
  background-color: #1f1f23; }
.theme-skin-dark .filter button {
  color: #9a9b9d; }
.theme-skin-dark .grid-more .ajax-loader {
  background: url("img/ajax-loader-dark.gif"); }
.theme-skin-dark .timeline-box-left .timeline-box-inner .arrow:before {
  border-left-color: #35363b; }
.theme-skin-dark .timeline-box-right .timeline-box-inner .arrow:before {
  border-right-color: #35363b; }
.theme-skin-dark .timeline-box,
.theme-skin-dark .timeline-box h4 {
  color: #7f8082; }
.theme-skin-dark .timeline-box h3 {
  color: #bbbbbb; }
.theme-skin-dark .ref-box .person-speech {
  border-bottom-color: #474d56; }
.theme-skin-dark .ref-slider-nav .slider-prev a,
.theme-skin-dark .ref-slider-nav .slider-next a {
  border-color: #474d56; }
  .theme-skin-dark .ref-slider-nav .slider-prev a .rsicon,
  .theme-skin-dark .ref-slider-nav .slider-next a .rsicon {
    color: #919296; }
.theme-skin-dark .ref-box .person-name {
  color: #c7c8cA; }
.theme-skin-dark .ref-box .person-title {
  color: #525458; }
.theme-skin-dark .calendar-busy .calendar-nav .rsicon {
  color: #525458; }
.theme-skin-dark .calendar-busy .calendar-nav .active-date {
  color: #d4d4d5; }
.theme-skin-dark .calendar-busy .calendar-body th {
  color: #525458; }
.theme-skin-dark .calendar-busy .calendar-body td {
  color: #9c9c9c; }
  .theme-skin-dark .calendar-busy .calendar-body td .busy-day {
    color: #d4d4d5;
    background-color: #474d56 !important; }
.theme-skin-dark .calendar-busy .calendar-busy-note {
  color: #9c9c9c;
  border-top-color: #474d56; }
  .theme-skin-dark .calendar-busy .calendar-busy-note:before {
    background-color: #474d56; }
.theme-skin-dark .contact-form h3 {
  color: #d4d4d5; }
.theme-skin-dark .contact-map .contact-info dt {
  color: #d4d4d5; }
.theme-skin-dark .contact-map .contact-info dd {
  color: #757677; }
.theme-skin-dark .price-box-top {
  background-color: #474d56; }
  .theme-skin-dark .price-box-top:before {
    border-top-color: #474d56; }
.theme-skin-dark .price-box-content h3 {
  color: #c7c8cA; }
.theme-skin-dark .post-tag a,
.theme-skin-dark .post-info a,
.theme-skin-dark .post-info .rsicon {
  color: #9c9c9c !important; }
.theme-skin-dark .post-title {
  color: #d4d4d5; }
.theme-skin-dark .post-box .post-media.no-media,
.theme-skin-dark .post-single .post-audio-wrap {
  background-color: #2e3035; }
.theme-skin-dark .post-pagination .post-next {
  border-color: #302f32; }
.theme-skin-dark .comment-list .comment-meta:after {
  background-color: #4d4c51; }
.theme-skin-dark .comment-list .comment-meta .name {
  color: #99989d; }
.theme-skin-dark .comment-list .comment-meta .date {
  color: #605E65; }
.theme-skin-dark .pagination .page-numbers {
  color: #9c9c9c; }
.theme-skin-dark .pagination .page-numbers:hover,
.theme-skin-dark .pagination .page-numbers.next:hover,
.theme-skin-dark .pagination .page-numbers.prev:hover {
  background-color: #35363b; }
.theme-skin-dark .page-404 {
  color: #fff; }
  .theme-skin-dark .page-404 h2 {
    color: #5d5e62; }
.theme-skin-dark .footer-social .social li a .rsicon {
  color: #1c1c1f; }

/**
 * 16.0 - Old Browsers
 */
.no-csstransforms #preloader .preload-icon,
.no-cssanimations #preloader .preload-icon {
  display: none; }
.no-csstransforms #preloader .preload-text,
.no-cssanimations #preloader .preload-text {
  top: 50%;
  left: 0;
  width: 100%;
  height: 20px;
  position: absolute;
  text-align: center;
  display: block;
  font-size: 14px;
  line-height: 20px;
  font-weight: 600; }

.no-csstransforms .sidebar-fixed {
  right: -450px; }
.no-csstransforms .sidebar-opened .sidebar-fixed {
  right: 0; }
.no-csstransforms .mobile-nav {
  right: -300px; }
.no-csstransforms .mobile-nav-opened .mobile-nav {
  right: 0; }

.no-rgba .head-bg:before,
.no-rgba .portfolio-figure .portfolio-caption {
  background-image: url("img/overlay.png"); }

.no-opacity .overlay {
  background: url("img/overlay.png"); }
.no-opacity .bar-line:after {
  background-color: #dedede !important;
  opacity: 1; }
.no-opacity.theme-skin-dark .bar-line:after {
  background-color: #525458 !important;
  opacity: 1; }
.no-opacity .portfolio-figure .portfolio-caption {
  display: none; }
.no-opacity .portfolio-figure:hover .portfolio-caption {
  display: block; }

.no-boxshadow .nav-wrap .nav > ul > li ul,
.no-boxshadow .grid-box,
.no-boxshadow .post-box,
.no-boxshadow .section-box,
.no-boxshadow .calendar-busy,
.no-boxshadow .sidebar-default .profile-photo img {
  border: 1px solid #dedede; }
.no-boxshadow .timeline-box-inner {
  border: 1px solid #dedede !important; }
.no-boxshadow.theme-skin-dark .nav-wrap .nav > ul > li ul,
.no-boxshadow.theme-skin-dark .grid-box,
.no-boxshadow.theme-skin-dark .post-box,
.no-boxshadow.theme-skin-dark .section-box,
.no-boxshadow.theme-skin-dark .calendar-busy,
.no-boxshadow.theme-skin-dark .sidebar-default .profile-photo img {
  border: 1px solid #525458; }
.no-boxshadow.theme-skin-dark .timeline-box-inner {
  border: 1px solid #525458 !important; }

/*# sourceMappingURL=style.css.map */

	</style>
	
    <style>
		.theme-color-07cb79 a,
		.theme-color-07cb79 blockquote:before,
		.theme-color-07cb79 .contact-map .contact-info a:hover,
		.theme-color-07cb79 .interests-list i,
		.theme-color-07cb79 .input-field.used label,
		.theme-color-07cb79 .logo span,
		.theme-color-07cb79 #map .map-icon,
		.theme-color-07cb79 .nav-wrap .btn-mobile-nav,
		.theme-color-07cb79 .page-404 h2 span,
		.theme-color-07cb79 .post-box .post-title a:hover,
		.theme-color-07cb79 .post-single .post-title a:hover,
		.theme-color-07cb79 .post-comments .section-title,
		.theme-color-07cb79 .ref-box .person-speech:before,
		.theme-color-07cb79 .timeline-box .date,
		.theme-color-07cb79 .widget-title,
		.theme-color-07cb79 .widget_meta ul li a:hover,
		.theme-color-07cb79 .widget_archive ul li a:hover,
		.theme-color-07cb79 .widget_nav_menu ul li a:hover,
		.theme-color-07cb79 .widget_categories ul li a:hover,
		.theme-color-07cb79 .widget_recent_entries ul li a:hover,
		.theme-color-07cb79 .widget_recent_comments ul li a:hover,
		.theme-color-07cb79 .widget_search .search-form:before,
		.theme-color-07cb79 .widget-popuplar-posts .post-title a:hover,
		.theme-color-07cb79 .widget-recent-posts .post-title a:hover {
		color: #07cb79;
		}
		.theme-color-07cb79 ins,
		.theme-color-07cb79 mark,
		.theme-color-07cb79 .btn-primary,
		.theme-color-07cb79 .btn-primary-outer,
		.theme-color-07cb79 .btn-sidebar-close,
		.theme-color-07cb79 .calendar-busy .calendar-body td .current-day,
		.theme-color-07cb79 .calendar-busy .calendar-today .date,
		.theme-color-07cb79 .filter .active:after,
		.theme-color-07cb79 .filter-bar .filter-bar-line,
		.theme-color-07cb79 .input-field .line:before,
		.theme-color-07cb79 .input-field .line:after,
		.theme-color-07cb79 .mobile-nav,
		.theme-color-07cb79 .nav > ul > li > a > span,
		.theme-color-07cb79 .post-datetime,
		.theme-color-07cb79 .profile-social,
		.theme-color-07cb79 .profile-preword span,
		.theme-color-07cb79 .progress-bar .bar-fill,
		.theme-color-07cb79 .progress-bar .bar-line:after,
		.theme-color-07cb79 .price-box.box-primary .btn,
		.theme-color-07cb79 .price-box.box-primary .price-box-top,
		.theme-color-07cb79 .profile-list .button,
		.theme-color-07cb79 .pagination .page-numbers.current,
		.theme-color-07cb79 .pagination .page-numbers.current:hover,
		.theme-color-07cb79 .pagination .page-numbers:active,
		.theme-color-07cb79 .pagination .page-numbers.next:active,
		.theme-color-07cb79 .pagination .page-numbers.prev:active,
		.theme-color-07cb79 .timeline-bar,
		.theme-color-07cb79 .timeline-box .dot,
		.theme-color-07cb79 .timeline-box-compact .date span,
		.theme-color-07cb79 .widget_tag_cloud a:hover {
		background-color: #07cb79;
		}
		.theme-color-07cb79
		.mejs-container
		.mejs-controls
		.mejs-time-rail
		.mejs-time-current,
		.theme-color-07cb79
		.mejs-container
		.mejs-controls
		.mejs-horizontal-volume-slider
		.mejs-horizontal-volume-current {
		background: #07cb79;
		}
		.theme-color-07cb79 .timeline-box-inner,
		.theme-color-07cb79 .price-box.box-primary .btn,
		.theme-color-07cb79 .widget_search .search-form,
		.theme-color-07cb79 .widget_tag_cloud a:hover {
		border-color: #07cb79;
		}
		.theme-color-07cb79 .page-404 h2 span:before,
		.theme-color-07cb79 .profile-preword span:before,
		.theme-color-07cb79 .timeline-box-compact .date span:before {
		border-left-color: #07cb79;
		}
		.theme-color-07cb79 .price-box.box-primary .price-box-top:before {
		border-top-color: #07cb79;
		}
	</style>

  </head>

  <body class="home header-has-img" data-gr-c-s-loaded="true" style="">
    <div class="wrapper">
      <header class="header" style="min-height: 95px;">

      <div class="content">
        <div class="container">
          <!-- START: PAGE CONTENT -->
          <section id="about" class="section section-about">
            <div class="animate-up animated">
              <div class="section-box">
                <div class="profile">
                  <div class="row">
                    <div class="col-xs-5">
                      <div class="profile-photo">
                        <img
                          src="./RScard_files/rs-photo-v1.jpg"
                          alt="Robert Smith"
                        />
                      </div>
                    </div>
                    <div class="col-xs-7">
                      <div class="profile-info">
                        <div class="profile-preword"><span>Hello</span></div>
                        <h1 class="profile-title">
                          <span>I'm</span> Robert Smith
                        </h1>
                        <h2 class="profile-position">
                          Developer and businessman
                        </h2>
                      </div>
                      <ul class="profile-list">
                        <li class="clearfix">
                          <strong class="title">Age</strong>
                          <span class="cont">29</span>
                        </li>
                        <li class="clearfix">
                          <strong class="title">Address</strong>
                          <span class="cont"
                            >24058, Belgium, Brussels, Liutte 27, BE</span
                          >
                        </li>
                        <li class="clearfix">
                          <strong class="title">E-mail</strong>
                          <span class="cont"
                            ><a href="mailto:robertsmith@company.com"
                              >robertsmith@company.com</a
                            ></span
                          >
                        </li>
                        <li class="clearfix">
                          <strong class="title">Phone</strong>
                          <span class="cont"
                            ><a href="tel:+12562548456"
                              >+1 256 254 84 56</a
                            ></span
                          >
                        </li>
                        <li class="clearfix">
                          <strong class="title">Freelance</strong>
                          <span class="cont">till April 15, 2016</span>
                        </li>
                        <li class="clearfix">
                          <strong class="title"
                            ><span class="button">On Vacation</span></strong
                          >
                          <span class="cont"
                            ><i class="rsicon rsicon-calendar"></i>till March
                            25, 2016</span
                          >
                        </li>
                      </ul>
                    </div>
                  </div>
                </div>
                <div class="profile-social">
				  <ul class="social">
                    <li>
                      <a
                        class="ripple-centered"
                        href="https://www.facebook.com/"
                        target="_blank"
                        ><i class='rsicon fab fa-facebook' style='font-size:24px;color:white'></i></a>
                    </li>
                    <li>
                      <a
                        class="ripple-centered"
                        href="https://twitter.com/"
                        target="_blank"
                        ><i class='rsicon fab fa-twitter' style='font-size:24px;color:white'></i></a>
                    </li>
                    <li>
                      <a
                        class="ripple-centered"
                        href="https://www.linkedin.com/"
                        target="_blank"
                        ><i class='rsicon fab fa-linkedin' style='font-size:24px;color:white'></i></a>
                    </li>
                    <li>
                      <a
                        class="ripple-centered"
                        href="https://dribbble.com/"
                        target="_blank"
                        ><i class='rsicon fab fa-dribbble' style='font-size:24px;color:white'></i></a>
                    </li>
                    <li>
					  <a
                        class="ripple-centered"
                        href="https://www.instagram.com/"
                        target="_blank"
                        ><i class='rsicon fab fa-instagram' style='font-size:24px;color:white'></i></a>
                    </li>
                  </ul>
                </div>
              </div>
			</div>

			

          </section>
          <!-- #about -->

          <!-- END: PAGE CONTENT -->
        </div>
        <!-- .container -->
      </div>
      <!-- .content -->
    </div>
    <!-- .wrapper -->
  </body>
</html>




<!--
**sadra/sadra** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
