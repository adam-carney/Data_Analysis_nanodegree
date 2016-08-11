# Data_Analysis_nanodegree_Project2
Data Analyis Nanodegree projects and other misc. items from the program
<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />
<title>Data_Analysis_Nanodegree-Project_2</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>

<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.6 (http://getbootstrap.com)
 * Copyright 2011-2015 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    color: #000 !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: thin dotted;
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.2.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.2.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.2.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.2.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.2.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.2.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
@media (max-width: 991px) {
  #ipython_notebook {
    margin-left: 10px;
  }
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#login_widget {
  float: right;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  text-align: center;
  vertical-align: middle;
  display: inline;
  opacity: 0;
  z-index: 2;
  width: 12ex;
  margin-right: -12ex;
}
.alternate_upload .btn-upload {
  height: 22px;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: baseline;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI colors. */
.ansibold {
  font-weight: bold;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  border-left-width: 1px;
  padding-left: 5px;
  background: linear-gradient(to right, transparent -40px, transparent 1px, transparent 1px, transparent 100%);
}
div.cell.jupyter-soft-selected {
  border-left-color: #90CAF9;
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected {
  border-color: #ababab;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 5px, transparent 5px, transparent 100%);
}
@media print {
  div.cell.selected {
    border-color: transparent;
  }
}
div.cell.selected.jupyter-soft-selected {
  border-left-width: 0;
  padding-left: 6px;
  background: linear-gradient(to right, #42A5F5 -40px, #42A5F5 7px, #E3F2FD 7px, #E3F2FD 100%);
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
  border-left-width: 0px;
  padding-left: 6px;
  background: linear-gradient(to right, #66BB6A -40px, #66BB6A 5px, transparent 5px, transparent 100%);
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
@-moz-document url-prefix() {
  div.inner_cell {
    overflow-x: hidden;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  padding: 0.4em;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. We need the 0 value because of how we size */
  /* .CodeMirror-lines */
  padding: 0;
  border: 0;
  border-radius: 0;
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul {
  list-style: disc;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ul ul {
  list-style: square;
  margin: 0em 2em;
}
.rendered_html ul ul ul {
  list-style: circle;
  margin: 0em 2em;
}
.rendered_html ol {
  list-style: decimal;
  margin: 0em 2em;
  padding-left: 0px;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
  margin: 0em 2em;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
  margin: 0em 2em;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  background-color: #fff;
  color: #000;
  font-size: 100%;
  padding: 0px;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: 1px solid black;
  border-collapse: collapse;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  border: 1px solid black;
  border-collapse: collapse;
  margin: 1em 2em;
}
.rendered_html td,
.rendered_html th {
  text-align: left;
  vertical-align: middle;
  padding: 4px;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget {
  float: right !important;
  float: right;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 20ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  margin-top: 6px;
}
span.save_widget span.filename {
  height: 1em;
  line-height: 1em;
  padding: 3px;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  display: none;
}
.command-shortcut:before {
  content: "(command)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    .highlight .hll { background-color: #ffffcc }
.highlight  { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>
<style type="text/css">
    
/* Temporary definitions which will become obsolete with Notebook release 5.0 */
.ansi-black-fg { color: #3E424D; }
.ansi-black-bg { background-color: #3E424D; }
.ansi-black-intense-fg { color: #282C36; }
.ansi-black-intense-bg { background-color: #282C36; }
.ansi-red-fg { color: #E75C58; }
.ansi-red-bg { background-color: #E75C58; }
.ansi-red-intense-fg { color: #B22B31; }
.ansi-red-intense-bg { background-color: #B22B31; }
.ansi-green-fg { color: #00A250; }
.ansi-green-bg { background-color: #00A250; }
.ansi-green-intense-fg { color: #007427; }
.ansi-green-intense-bg { background-color: #007427; }
.ansi-yellow-fg { color: #DDB62B; }
.ansi-yellow-bg { background-color: #DDB62B; }
.ansi-yellow-intense-fg { color: #B27D12; }
.ansi-yellow-intense-bg { background-color: #B27D12; }
.ansi-blue-fg { color: #208FFB; }
.ansi-blue-bg { background-color: #208FFB; }
.ansi-blue-intense-fg { color: #0065CA; }
.ansi-blue-intense-bg { background-color: #0065CA; }
.ansi-magenta-fg { color: #D160C4; }
.ansi-magenta-bg { background-color: #D160C4; }
.ansi-magenta-intense-fg { color: #A03196; }
.ansi-magenta-intense-bg { background-color: #A03196; }
.ansi-cyan-fg { color: #60C6C8; }
.ansi-cyan-bg { background-color: #60C6C8; }
.ansi-cyan-intense-fg { color: #258F8F; }
.ansi-cyan-intense-bg { background-color: #258F8F; }
.ansi-white-fg { color: #C5C1B4; }
.ansi-white-bg { background-color: #C5C1B4; }
.ansi-white-intense-fg { color: #A1A6B2; }
.ansi-white-intense-bg { background-color: #A1A6B2; }

.ansi-bold { font-weight: bold; }

    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}

@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Introduction</p>
<p>For the final project, you will conduct your own data analysis and create a file to share that documents your findings. You should start by taking a look at your dataset and brainstorming what questions you could answer using it. Then you should use Pandas and NumPy to answer the questions you are most interested in, and create a report sharing the answers. You will not be required to use statistics or machine learning to complete this project, but you should make it clear in your communications that your findings are tentative. This project is open-ended in that we are not looking for one right answer.
Step One - Choose Your Data Set</p>
<p>Choose one of the following datasets to analyze for your project:</p>

<pre><code>Titanic Data - Contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. You can view a description of this dataset on the Kaggle website, where the data was obtained.

Baseball Data - A data set containing complete batting and pitching statistics from 1871 to 2014, plus fielding statistics, standings, team stats, managerial records, post-season data, and more. This dataset contains many files, but you can choose to analyze only the one(s) you are most interested in.

Choose the comma-delimited version, which contains CSV files.

</code></pre>
<p>Step Two - Get Organized</p>
<p>Eventually you’ll want to submit your project (and share it with friends, family, and employers). Get organized before you begin. We recommend creating a single folder that will eventually contain:</p>

<pre><code>The report communicating your findings
Any Python code you wrote as part of your analysis
The data set you used (which you will not need to submit)

</code></pre>
<p>You may wish to use IPython notebook, in which case you can submit both the code you wrote and the report of your findings in the same document. Otherwise, you will need to submit your report and code separately.
Step Three - Analyze Your Data</p>
<p>Brainstorm some questions you could answer using the data set you chose, then start answering those questions. Here are some ideas to get you started:</p>

<pre><code>Titanic Data
    What factors made people more likely to survive?
Baseball Data
    What is the relationship between different performance metrics? Do any have a strong negative or positive relationship?
    What are the characteristics of baseball players with the highest salaries?

</code></pre>
<p>Try and suggest questions that promote looking at relationships between multiple variables. You should aim to analyze at least one dependent variable and three independent variables in your investigation. Make sure you use NumPy and Pandas where they are appropriate!
Step Four - Share Your Findings</p>
<p>Once you have finished analyzing the data, create a report that shares the findings you found most interesting. You might wish to use IPython notebook to share your findings alongside the code you used to perform the analysis, but you can also use another tool if you wish.
Step Five - Review</p>
<p>Use the Project Rubric to review your project. If you are happy with your submission, then you're ready to submit your project. If you see room for improvement, keep working to improve your project.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>I will be using the Batting.csv and the BattingPost.csv fle from the Baseball Data.</p>
<ul>
<li>What was the batting average of each player during the regular playing season?</li>
<li>Over time, has batter's averages gone up, down, or stayed the same during the regular playing season?</li>
<li>Is there a correlation between the number of singles (H), doubles (2B), triples (3B), or home runs (HR) to batting averages?</li>
<li>Do players who make it to the post season perform the same, better, worse in the post season?</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Imports</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="kn">as</span> <span class="nn">pd</span> 
<span class="kn">import</span> <span class="nn">numpy</span> <span class="kn">as</span> <span class="nn">np</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="kn">as</span> <span class="nn">plt</span>
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="kn">as</span> <span class="nn">sns</span>

<span class="c1"># Let&#39;s begin by reading in the files</span>

<span class="n">batting_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;Batting.csv&quot;</span><span class="p">)</span>
<span class="n">batting_post_df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;BattingPost.csv&quot;</span><span class="p">)</span>

<span class="c1"># Doing a little display to make sure reading the file worked</span>
<span class="k">print</span> <span class="s2">&quot;Batting DataFrame&quot;</span>
<span class="n">batting_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt"></div>
<div class="output_subarea output_stream output_stdout output_text">
<pre>Batting DataFrame
</pre>
</div>
</div>

<div class="output_area"><div class="prompt output_prompt">Out[1]:</div>

<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>playerID</th>
      <th>yearID</th>
      <th>stint</th>
      <th>teamID</th>
      <th>lgID</th>
      <th>G</th>
      <th>AB</th>
      <th>R</th>
      <th>H</th>
      <th>2B</th>
      <th>...</th>
      <th>RBI</th>
      <th>SB</th>
      <th>CS</th>
      <th>BB</th>
      <th>SO</th>
      <th>IBB</th>
      <th>HBP</th>
      <th>SH</th>
      <th>SF</th>
      <th>GIDP</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>abercda01</td>
      <td>1871</td>
      <td>1</td>
      <td>TRO</td>
      <td>NaN</td>
      <td>1</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>addybo01</td>
      <td>1871</td>
      <td>1</td>
      <td>RC1</td>
      <td>NaN</td>
      <td>25</td>
      <td>118.0</td>
      <td>30.0</td>
      <td>32.0</td>
      <td>6.0</td>
      <td>...</td>
      <td>13.0</td>
      <td>8.0</td>
      <td>1.0</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>allisar01</td>
      <td>1871</td>
      <td>1</td>
      <td>CL1</td>
      <td>NaN</td>
      <td>29</td>
      <td>137.0</td>
      <td>28.0</td>
      <td>40.0</td>
      <td>4.0</td>
      <td>...</td>
      <td>19.0</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>5.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>allisdo01</td>
      <td>1871</td>
      <td>1</td>
      <td>WS3</td>
      <td>NaN</td>
      <td>27</td>
      <td>133.0</td>
      <td>28.0</td>
      <td>44.0</td>
      <td>10.0</td>
      <td>...</td>
      <td>27.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>ansonca01</td>
      <td>1871</td>
      <td>1</td>
      <td>RC1</td>
      <td>NaN</td>
      <td>25</td>
      <td>120.0</td>
      <td>29.0</td>
      <td>39.0</td>
      <td>11.0</td>
      <td>...</td>
      <td>16.0</td>
      <td>6.0</td>
      <td>2.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 22 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[2]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#More display - this time on Batting Post Season</span>
<span class="k">print</span> <span class="s2">&quot;Batting Post Season DataFrame&quot;</span>
<span class="n">batting_post_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt"></div>
<div class="output_subarea output_stream output_stdout output_text">
<pre>Batting Post Season DataFrame
</pre>
</div>
</div>

<div class="output_area"><div class="prompt output_prompt">Out[2]:</div>

<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>yearID</th>
      <th>round</th>
      <th>playerID</th>
      <th>teamID</th>
      <th>lgID</th>
      <th>G</th>
      <th>AB</th>
      <th>R</th>
      <th>H</th>
      <th>2B</th>
      <th>...</th>
      <th>RBI</th>
      <th>SB</th>
      <th>CS</th>
      <th>BB</th>
      <th>SO</th>
      <th>IBB</th>
      <th>HBP</th>
      <th>SH</th>
      <th>SF</th>
      <th>GIDP</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1884</td>
      <td>WS</td>
      <td>becanbu01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>1</td>
      <td>2</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1884</td>
      <td>WS</td>
      <td>bradyst01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>3</td>
      <td>10</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0</td>
      <td>1</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1884</td>
      <td>WS</td>
      <td>esterdu01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>3</td>
      <td>10</td>
      <td>0</td>
      <td>3</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>1</td>
      <td>NaN</td>
      <td>0</td>
      <td>3</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1884</td>
      <td>WS</td>
      <td>forstto01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>1</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0</td>
      <td>1</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1884</td>
      <td>WS</td>
      <td>keefeti01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>2</td>
      <td>5</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>NaN</td>
      <td>0</td>
      <td>4</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 22 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="sd">&#39;&#39;&#39;</span>
<span class="sd">Defining the batting average function.  This will add the total hits and the batting average into the DataFrame...</span>
<span class="sd">though from my old playing days of baseball I generally knew this to be the case, I did confirm via the following source:</span>
<span class="sd">Wikipedia Batting Average: https://en.wikipedia.org/wiki/Batting_average</span>
<span class="sd">&#39;&#39;&#39;</span>
<span class="k">def</span> <span class="nf">batting_average</span><span class="p">(</span><span class="n">batting_dataframe</span><span class="p">):</span>
    <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;TOTAL_HITS&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;H&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;2B&#39;</span><span class="p">]</span> <span class="o">+</span> \
    <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;3B&#39;</span><span class="p">]</span> <span class="o">+</span> <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;HR&#39;</span><span class="p">]</span>
    <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;TOTAL_HITS&#39;</span><span class="p">]</span> <span class="o">/</span> <span class="n">batting_dataframe</span><span class="p">[</span><span class="s1">&#39;AB&#39;</span><span class="p">]</span>
    <span class="k">return</span> <span class="n">batting_dataframe</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Calling the batting average function on both the season batting and the post season.</span>

<span class="n">season_batting_df</span> <span class="o">=</span> <span class="n">batting_average</span><span class="p">(</span><span class="n">batting_df</span><span class="p">)</span>
<span class="n">post_season_batting_df</span> <span class="o">=</span> <span class="n">batting_average</span><span class="p">(</span><span class="n">batting_post_df</span><span class="p">)</span>

<span class="c1">#Showing the first few records of season DF to ensure data is being returned appropriately.</span>
<span class="n">season_batting_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[4]:</div>

<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>playerID</th>
      <th>yearID</th>
      <th>stint</th>
      <th>teamID</th>
      <th>lgID</th>
      <th>G</th>
      <th>AB</th>
      <th>R</th>
      <th>H</th>
      <th>2B</th>
      <th>...</th>
      <th>CS</th>
      <th>BB</th>
      <th>SO</th>
      <th>IBB</th>
      <th>HBP</th>
      <th>SH</th>
      <th>SF</th>
      <th>GIDP</th>
      <th>TOTAL_HITS</th>
      <th>BATTING_AVERAGE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>abercda01</td>
      <td>1871</td>
      <td>1</td>
      <td>TRO</td>
      <td>NaN</td>
      <td>1</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>addybo01</td>
      <td>1871</td>
      <td>1</td>
      <td>RC1</td>
      <td>NaN</td>
      <td>25</td>
      <td>118.0</td>
      <td>30.0</td>
      <td>32.0</td>
      <td>6.0</td>
      <td>...</td>
      <td>1.0</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>38.0</td>
      <td>0.322034</td>
    </tr>
    <tr>
      <th>2</th>
      <td>allisar01</td>
      <td>1871</td>
      <td>1</td>
      <td>CL1</td>
      <td>NaN</td>
      <td>29</td>
      <td>137.0</td>
      <td>28.0</td>
      <td>40.0</td>
      <td>4.0</td>
      <td>...</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>5.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>49.0</td>
      <td>0.357664</td>
    </tr>
    <tr>
      <th>3</th>
      <td>allisdo01</td>
      <td>1871</td>
      <td>1</td>
      <td>WS3</td>
      <td>NaN</td>
      <td>27</td>
      <td>133.0</td>
      <td>28.0</td>
      <td>44.0</td>
      <td>10.0</td>
      <td>...</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>58.0</td>
      <td>0.436090</td>
    </tr>
    <tr>
      <th>4</th>
      <td>ansonca01</td>
      <td>1871</td>
      <td>1</td>
      <td>RC1</td>
      <td>NaN</td>
      <td>25</td>
      <td>120.0</td>
      <td>29.0</td>
      <td>39.0</td>
      <td>11.0</td>
      <td>...</td>
      <td>2.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>53.0</td>
      <td>0.441667</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 24 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Showing the first few records of post season DF to ensure data is being returned appropriately.</span>
<span class="n">post_season_batting_df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[5]:</div>

<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>yearID</th>
      <th>round</th>
      <th>playerID</th>
      <th>teamID</th>
      <th>lgID</th>
      <th>G</th>
      <th>AB</th>
      <th>R</th>
      <th>H</th>
      <th>2B</th>
      <th>...</th>
      <th>CS</th>
      <th>BB</th>
      <th>SO</th>
      <th>IBB</th>
      <th>HBP</th>
      <th>SH</th>
      <th>SF</th>
      <th>GIDP</th>
      <th>TOTAL_HITS</th>
      <th>BATTING_AVERAGE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1884</td>
      <td>WS</td>
      <td>becanbu01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>1</td>
      <td>2</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0</td>
      <td>0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1</td>
      <td>0.5</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1884</td>
      <td>WS</td>
      <td>bradyst01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>3</td>
      <td>10</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0</td>
      <td>1</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1884</td>
      <td>WS</td>
      <td>esterdu01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>3</td>
      <td>10</td>
      <td>0</td>
      <td>3</td>
      <td>1</td>
      <td>...</td>
      <td>NaN</td>
      <td>0</td>
      <td>3</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>4</td>
      <td>0.4</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1884</td>
      <td>WS</td>
      <td>forstto01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>1</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0</td>
      <td>1</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0</td>
      <td>0.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1884</td>
      <td>WS</td>
      <td>keefeti01</td>
      <td>NY4</td>
      <td>AA</td>
      <td>2</td>
      <td>5</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0</td>
      <td>4</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1</td>
      <td>0.2</td>
    </tr>
  </tbody>
</table>
<p>5 rows × 24 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[6]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Now, to answer my first few questions I will plot some information on batting average</span>

<span class="o">%</span><span class="k">pylab</span> inline
<span class="n">plt</span><span class="o">.</span><span class="n">scatter</span><span class="p">(</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;yearID&#39;</span><span class="p">],</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt"></div>
<div class="output_subarea output_stream output_stdout output_text">
<pre>Populating the interactive namespace from numpy and matplotlib
</pre>
</div>
</div>

<div class="output_area"><div class="prompt output_prompt">Out[6]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.collections.PathCollection at 0x7f4820f83a90&gt;</pre>
</div>

</div>

<div class="output_area"><div class="prompt"></div>


<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYMAAAEDCAYAAADX1GjKAAAABHNCSVQICAgIfAhkiAAAAAlwSFlz
AAALEgAACxIB0t1+/AAAIABJREFUeJzsvXt8XUd19/09uli+W7IsXxTbkuxEJ0kTGggUwuWBhIdw
azGBtk8c2gChbh8SaKGl+BKSkJBEiZ9eoVzeuhDyBmJDKYkNTShvKU24pA9pEocYkp3YluTLkW3J
kizZlmRJZ79/zPw0c7aOZF1tR5rf56PP0dln75k1a2bWWrPWmtmpOI4JCAgICJjeKDjbBAQEBAQE
nH0EZRAQEBAQEJRBQEBAQEBQBgEBAQEBBGUQEBAQEEBQBgEBAQEBQNF4Hk6n05uBNwKFwD1RFD3k
/VYP7AOyQAx8IIqipvHUFxAQEBAwORizMkin028BLo6i6PXpdHoh8AzwkHdLDLwjiqKu8ZEYEBAQ
EDDZGI+b6DHg9+z/7cDsdDqd8n5P2b+AgICAgHMcY14ZRFEUA7L6/wh4xF7z8ZV0Ol0D/CSKok1j
rSsgICAgYHIx7gByOp1eA3wY+Fjip1uAPwfeDFyaTqffN966AgICAgImB6nxnE2UTqffDtwOvD2K
omPD3PdRYHEURbcPdU8cx3EqFbxKAQEBAaPEhAjO8QSQ5wObgbcmFYH97dvA70RR1ItZHfzzcOWl
UimamzvHSs6koKJiXqBphDgX6Qo0jQyBppHjXKSromLehJQzntTS/wWUA9+2geMY+A/guSiKtqfT
6X8F/iudTp8Enomi6F/GT25AQEBAwGRgPAHkLcCWYX7/AvCFsZYfEBAQEHDmEHYgBwQEBAQEZRAQ
EBAQEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABB
GQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBA
QABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEEJRB
QEBAQABBGQQEBAQEEJRBQEBAQABBGQQEBAQEAEXjeTidTm8G3ggUAvdEUfSQ99v/BO4C+oBHoyi6
czx1BQQEBARMHsa8Mkin028BLo6i6PXAO4G/S9zy98A1GGVxdTqdvnCsdQUEBAQETC7G4yZ6DPg9
+387MDudTqcA0ul0DXA0iqJMFEUx8Ajw1nFRGhAQEBAwaRizm8gK+S779Y+AR+w1gKVAs3f7EWDV
WOuaamhtbWf9+h/T2DifqqpjbN58FWVlpSO6v7b2JJ/73JuGvX+kdSTv+ehHL+CGG/6Tw4dT9Pcf
I5WqpaRkLzt2vIvLLrt02HoymTJmznyOX/ziJKdOraKkZC8PPPAmvvGNw+zZU0hrayPl5bWsWnVi
gJbhaEz+tnHj5dTVPZ333j17Gnn/+3dw9OhCUqkDrFixmhMnmliy5CJWruwYUduT9zz11HNcc82j
9PTUnJYH+aDnu7sXAC2UlFxIeflBHn/8D5g/f+HAfUnaa2oupba2m82bryKOGZYHH/3oBfzBH2yn
pWUGsISSkkOsWmWe171J3vtlLFvWBBTT0rKEysrWQTwYTf8M16dqRxT10NCwj1RqNWVlB7nvviv5
0pd2D1yP42X0979AHJeSzS5hxoymgfZobDY3z6K/v5miouUUFGRYtqyS/fsj+vrmAUtHxAOf1ptu
+g6PP95Gf381ixcfZPv2a6ipqRpxP08pxHE8rr/a2to1tbW1T9TW1s7zrl1RW1v7L973j9TW1t55
mrLiI0c6zqm/yaJpzZr7Y8jGEMeQjdesuX9C7x/pM8l7Zs78jP1+y6DrI6vnMznPFRRstN8fzEvL
cDQmf6usvGvIe91vDw5b32j443hxeh7k+3PP1+WUs3x5Xc59g2l39JyOB6aOu/M+P1S5uWV8c1ge
jKZ/hutTd60uD/3+9QeHbE/+e/V9dDzIpfXuQc+cDZkwTjk1bjkex/G4A8hvBzYCb4+iqNP7KQMs
876fZ68Ni4qKeeMhZ1IwGTRlMmVAyn5LkcmUDVvPaO8f6TPJe3p6auz36kHXh6ovt4yanOey2fPt
97l5aRmOxuRv7e3Lh7zX/TaX4eobDX8cL07Pg3xwz1fmlNPaWplTzmDaHT36fygemDqK8j4/VLm5
Zcwblgej6Z/h+tS1I5cXg3k0FyMqBtOd/159J+8zw/HW0TqYx6fr53NRTk0ExqwM0un0fGAz8NYo
io75v0VR1JhOp+el0+mVGCXw28B1pyuzubnzdLecUVRUzJsUmiorW4EYMwhjKivbhq1ntPeP9Jnk
PSUle+nujoG9iev1Q9aXW0bucwUFL5HNxkBnXlqGozH5W2npfk6ezH+v+0315K9vNPxxvDg9D/LB
PX8wp56FCzM55Qym3dFjvg/NA1PHnLxtHqrc3DI6huXBaPpnuD517cjlxWAedSb+P929+s6oeJBL
aybxzIFh+3myZMJ4MFHKKRXH8ZgeTKfT64DbgBcRJ+E/gOeiKNqeTqffiFEWMfCdKIr+9jRFxuci
kyeDpra2dj79aflVO9i8+cphYwD+/bW1XXzuc288bcxgJHUk77nppvP50If+k8OHs/T3H7cxg3p2
7HjnkP5ylWFiBs/yi19025hBPd/4xht54IFkzODkAC3D0Zj8bdOmV3H33U/nvbe+vpFrrtnB0aNl
pFIZVqyo4cSJQzZm0Dmitifv2bnzOd7zHsUMhudBPuj57u55QKuNGWR4/PEP5MQMkrTX1FxCbW0P
mzdfCTAsD2666Xyuu+5hWlpKgMWUlBy2/vKegXuTvPfLyI0ZtA3iwWj6Z7g+VTuiqJuGhv02ZpDh
619/C1/84u6B6yZmEBHHC8hmFzNjxqGB9mhsNjeX0N9/1MYMmli2bAn7979kYwZLRsQDn9Ybb/w2
jz9+zMYMMmzf/t5hYwbnqDJInf6u02PMymASMG2UwXhwLtIE5yZdgaaRIdA0cpyLdE2UMgg7kAMC
AgICgjIICAgICAjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjK
ICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgIC
AgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwC
AgICAgjKICAgICCAoAwCAgICAgjKICAgICCAoAwCAgICAgjKICAgICAAKBrPw+l0+hLgYeBvoij6
UuK3emAfkAVi4ANRFDWNp76AgICAgMnBmJVBOp2eDXwe+PchbomBd0RR1DXWOgICAgICzgzGszLo
Bt4JbBji95T9C0igtbWd9et/TGPjfKqqjrF581WUlZWe8TLGA9W/Z08hra2NLFlyEStXdpxxOkaK
yeTX2e6L0SAfrRUV8yaknMlo80jqeTnx/1zGmJVBFEVZoCedTg9321fS6XQN8JMoijaNta6phvXr
f8z27X8IpNi5MwYeYMuWa854GeOBq38bsJFMJsUzz5x5OkaKyeTX2e6L0SAfrQ8/fP2ElDMZbR5J
PS8n/p/LGFfM4DS4BfgB0ApsT6fT74ui6LvDPTAWC2WyMRk0ZTJluEVTikymbFT1VFTMG3cZ44Wr
f+5ZpeN0EC2Tya/Rln02+ZOP1rHQdCbG30jH+ZmeC+fS+J5ITJoyiKLoG/o/nU4/AlwKDKsMmps7
J4ucMaGiYt6k0FRZ2YoJqaSAmMrKthHXI5rGU8ZEwNXfeVbpGA5+/00mv0ZT9mSNqZEiH60w+rk3
2eNvNOP8TM6Fs91/+TBRymmilEFObCCdTs8Hvg38ThRFvcCbgX+eoLpe9ti8+SrgAevj7GDz5ivP
Shnjgeo3MYM6GzPoPON0jBSTya+z3RejwUTReqbaPJJ6Xk78P5eRiuN4TA+m0+lXAX8NVAG9wEFg
B1AfRdH2dDr9ceBDwEngmSiK/vQ0RcbnosYNNI0M5yJdgaaRIdA0cpyLdFVUzJuQRJ3xBJCfBoZU
wVEUfQH4wljLDwgICAg4c5jMAHJAQEDAqKA00UymjMrK1pAmegYRlEFAQMA5Az9N1ASFQ5romUI4
myggIOCcQWPjfPw0UfM94EwgKIOAgIBzBlVVxzArAoCYqqqOs0nOtEJwEwUEBJwzUJqoiRm0hTTR
M4igDALC2S6jxNnm19muf6QYC51lZaVs2XLNqFI49+xp5P3v30Fb23LKyvbz0ENrqKmpmogmTCsE
ZRAQznYZJc42v852/SPFmaLz/e/fQSazEUjR1RVzzTV17Nz58QmvZ6ojxAwCQtBulDjb/Drb9Y8U
Z4rOtrblOfWY7wGjRVAGASFoN0qcbX6d7fpHijNFZ1nZ/px6ysoOTEo9Ux3BTRQQznYZJc42v852
/SPFmaLzoYfWcM01dTZmcICHHnrPpNQz1THms4kmAeFsohHgXKQJzk26Ak0jQ6Bp5DgX6Zqos4mC
myggICAgICiDyUZrazvr1j3E1Vf/iHXrvktbW/vZJmnKYc+eRi677AtUVT3EZZd9nvr6xrNN0lnD
RIy3MGanJ0LMYJLxckkDfDkjpBY6TIVXqgacHYSVwSTj5ZIG+HJGSC10mIjxFsbs9ERQBpOMcyEN
cKov+0NqocNEjLezOWY1Vn/rt743JcfquYzgJppknAtpgFN92R9SCx1e7q9UDUdYnz0EZTDJ0Fkr
ZxNTfdlfU1M1bWMESUzEeDubY3aqj9VzGcFNNA1wLriqAqYXxuqaDGP17CGsDKYBzgVXVcD0wlhd
k+EI67OHoAymAc4FV1XA9MJY3T1jOcI6YGIQ3EQBAQETjuDuefkhrAwCAgImHME1+fJDUAYBAQET
juCafPkhuIkCAgICAoIyCAgICAgIyiAgICAggKAMAgICAgIYZwA5nU5fAjwM/E0URV9K/PY/gbuA
PuDRKIruHE9dAQEBAQGThzGvDNLp9Gzg88C/D3HL3wPXAG8Erk6n0xeOta6AgICAgMnFeFYG3cA7
gQ3JH9LpdA1wNIqijP3+CPBW4IVx1DcutLa2s379j23e8zE2b76KsrLSYZ85erSddet2DHpmJGWN
5p49ewppbW1kwYLzOHbsIHPmlLF/f4be3pn093cCK4C9zJ27CJhBb28bfX2zBn4rKDjI8uXLOHLk
CHG8jFQqw4oVq2lre4H29hL6+uaTSrWSSs0hm3XPlJdDc3MWmAscBxYBLUAXcBA4f+BacXEtFRVN
fPjDs7nrrsOWpv0sXbqI9vZjdHefAo4Ci4FWoNQrV59FmIViP1BoP18CLgRqgYg///MFbNsGhw+n
6O8/Nqh93d0dQC+wEDDtiuMsxq4xtBYULAJaKS5eTiqVYcaMo3R09FraCiwNfltnAUfs76JtLtBg
rx0HZg+0uaJiLkePniSbXWjLKLY0LQKeAqq8tqrtKvekLSsfL9psfb0eDfn45/fXL4FK77dk+Ybm
5cuX0tJylFRqNYWFP+H48QqPB+Jf7jNVVTX09h6lsBD272+29x+x/KoFXuSDH4T77ycPjScx0/1V
QLsdD88Bl3o06vsBYLn93gJcCdQDNR5/ngIu9+qJgLS9rwP4TeBFS5fKV7n6FG1+u38NXILG32c+
s5g//dM/ZloijuNx/dXW1t5WW1t7Y+LaFbW1tf/ifb+htrb2ztOUFR850jFpf2vW3B9DNoY4hmy8
Zs39p33m93//wbzPjKSs0d3zYOKzzn7e4l3/5jC/+df9su4+zTPrE9frvOvrE9fixDPJetfH8Jkh
ytXnxsTvfj3J8odq3/o87UrSmuSFT9vGIZ5Nft6Spz0Pxrm01eUpc33i2i1DlJ+PFyPln1//xiHK
0/ck/+I8/BrqmQe9699M3DtUf/l0DMXb4T5Pd08+fo60/Hx9P7g9w8mEyZZTY/kbrwzX35nadJY6
/S1QUTFv0gjIZMrwz0rJZMpOW199/dy8z4ykrNHdMzfxWWk/q73rDPObf90v67zTPFObuF7pXU/W
R+KZZL21ee6pTnyen/jdf2aoZ/PVU5Tnmv89yQu/nvOHeDb5WT1Mm5P88stcnLhWPUT5w/HidPzz
60/Wlyw/yT/y8GuoZ+Z61+cl7h2KVp+O5D0j+TzdM/n4OdJ68vW9nnVlnE4uTKacOpuYLGWQAZZ5
38+z14bFZB5MVVnZijkrJQXEVFa2nba+mppOnnxy8DMjKWt093QmPg/az72J68P9djBPWQdP88yL
ieu6L7IU+tdS3m/56n0RM5z8e/YmPl9K1KvPfOUP1b4I43JI1u1/T/IiwrhyfBoOJuqLEmXt9XiQ
bHOSX36ZxxLX9ibKjRiaF0UMpiEf//z6OxK/JctP8i+Vh18vDvFMp3e9JHHvUP3l05Hk30g+k88k
+bZ3BM8M9Zns+3zj78Vh5cK5eIDeRCmnVBzH4yognU7fBrREUfTFxPXngHdjlMDPgeuiKNo9TFHx
ZDK5ra2dT3/6xzlnpZwuZlBY2M8NN+wY9MxIyhrNPYNjBqXs399Eb+8M+vtPYPyd9TZmUExvbzt9
fSUDvxUUZFi+fAlHjrTYmEETK1bU2JjBTPr65pJKtZNKzSKbdc+Ul/fT3JzC+IC7MH74VoxP9hDG
kjLXTMzgEDfcUMKddzYjX+zSpQtpb++ku/skRhAuxviVF3nl6lPowQiXHszkvgj5oP/iL+aydWsB
hw9n6e8/Pqh93d1tGF/vQsC0K457McLe0FpQsBBotzGDJmbMaKKjA0tb1tKgtnZirN4MxmIUbbOA
/faZdmD+QJsrKmZx9GgP2WypLaPAo+kZTMxAUNtVboctKx8vOm19XR4N+fjn99cuS7eQLN/QvHz5
Ylpa2hIxA/HgFDBj0DNVVdX09rZSWNjP/v2tmD5twqwYTH/dcEMfX/taUR4aOzBC+DUY//wiy5tX
ejTqe6Pl2TPAYeAdwG7M+BN/ngCu8Op5HjNudlu+vdK7pvJVrj4Fv90RJm5h2vOZz1QMGzM4R5VB
6vR3nR5jVgbpdPpVwF9juNyLUbc7gPooiran0+k3Apsx6vY7URT97WmKnFRlMBacox1/ztEE5yZd
gaaRIdA0cpyLdE2UMhizmyiKoqcxYf+hfv8p8Pqxlh8QEBAQcOYQdiAHBAQEBIQjrANefhjLnpGA
iUXog6mHoAwCXnYY6/t1AyYOoQ+mHoIyCHjZYazv1w2YOLyc+iCsYkaGoAwCXnaoqjpmrVGTGx7e
r+swkceuDIeJ7AOf5mXLmoBiWlqWUFnZOiGCO6xiRoagDAJedgjv1x0aYxF8N9746Kifmcg+yKX5
QWAtbhPY+AX3y2kVczYRlMHLHNNxCTwZ79c903yc6PpU3g9/CKcTfMm69+07vbDMR+9Y+yBZ1osv
zvTq17EX7cCj/PCHsG7dd4fkz3B81G8NDYfwdxmHlWR+BGXwMsdUWQKfbaV2pvk40fW58rYynOBr
bW3nqqseIJPZOFD38uX3DPvMRNObLGvmzFuA37f163iNR4Fr6epKsX370PUNR5f77RiwldLSbt78
5qKwkhwC004ZnG2hMxyGos2/vnJlC7290NS0iKqqY+zdO4eRLoGTR2aXl9eyatWJYY/mbm09xvvf
v4O2tuWUle3noYfWUFNTNWQdY8UnP/mvPProfKCQnTuLOHXq+9x//x+cluaJQtKVsGdPIevWPZTD
izhmwsbORLgu/P5qaOiz5b0BuJdUajHLlh3ixhvfktOOU6d6yWQuzKm7tHQFl1/uXD4bN75qUNsd
vSO32D/5yX/liSc6gXKuuKKf2267grq6pwetXuL4PGCb/f4ccAuwakT1GbqOYZTHXB577BBtbe2U
lZV6NJcC11Fd/TBbtrx11HyeLph2yuBctqSHom0on+rOnTGVlXcz0iWwK2cbsJFMJsVzzw1Vj7n+
5JMHBqzIrq6Ya66pY+fOj094243Q+JOBdjzxxF+NiOaJQjIg2trayK5dznqGBwAmbOxMRADW7y/4
JmYc/BxYTxynyGRiPvzhupxVQGnpfbiD20zd7e0H2LLlpoFy1617aFA7q6pi+//ILXaj3E2fPvpo
zLPPipbc1Ut5eSuZzP/G9PErMONb9wxf39KlzcAjaE60t/82n/60uSckGowO004ZnMvBpKFoy70+
L+eehQurec1rRhbIc+XkHs2dvx5zva1tec418310GNlqrDynHvP99DRPFJIB0b17a8lk8tU3MTRM
RAA2t7/eTWnpX9HTs4SurmR/+XxtwRwntg29KGbRotyVXr5x8K1vXQ48wA9/SE75Q/HAXO/y6umk
rW2ZLfddwDZmzerl6qth06Y13H23yp6Xc08q1UUcD11fKtWHOXBu8D0h0WB0mHbK4Fy2FoaiLfe6
fKrmntWr+0dsnbpydDTxcPWY60eO7Kery10rKzsw6naNZDV2xRX9PPqoq+eKK7IjonmikAxKr1v3
XbsC8euLJ2zsTEQQPLe/FvDmNy8BYmtBq79y+++KK+bx7LP1ZDKbBq7V1m4bplzTTtG7bt13c8of
igemjAzmRYjm3ji+BdOHpcC1XH21GwdbtlTZsl/Iuaek5Ba6u4eur6lpGebNZoPvmYxEg6mMcR9h
PYGYlFNLk1bpBz6wlOuv/yk9PTWUlOxlx453cdlll+Z9NnlCocqKoh4aGvaRSq2mrOzgsH70PXsa
T+tzH6rc++67ki99aXfO9XnzXgDmcOxYBanUQWpqLqG2tntE/uu9ext53/t20NTUTRyfAmopKHiJ
f/qnV7N9+wmiqJuGhv0Dx2DX1FxCZeV+fvWrbo4dW0lZ2QHuu+8tfOlLuwf58L/2tTX09xfmrffq
q3/Ezp3vHfh+2WUP88MfvpU9exp573u/TXPzTLLZFCUlJ4DKgbpra7vZtOly7r776YH69ErQfLxP
9vXNN7+S9773+xw9upBU6gA1NZdSXd0KFLN//6y85Ynne/YU0twc0dU1l2y2gN7edktbhpqaS6mt
7Rk4ljxfXGP58uacenQ8+fz5i2ho2D/s2BlpbCffOCwtXZBzdPoHPrAkZ7x/8YuvZNOmnTQ3z6Kg
oJy3vCXmy19+J5/61GODjlI39Z7MOX59pEfBP/30c7zjHc8ANyG/f0lJG+Xl7QM891/ReuJEEyUl
M6mv7wVWYgR8I+Zo8hMkX3+qNq9ePYuf/KQI88rVeUALM2aspKDAlSv+bdx4OXV1T+ftJ8XgTjeP
pvKppRPyurQJ+jsjr7ucOfMzOd8rK+8a8SvuXFl1Iy6jsvKu0947+PWX7t7B17+Z996RvMbT1XNL
zrMFBUO97nBw2UPR+vu//+Aw9X49b3mmfcn2DN+uJUtusc/siOEb8ZIln8lDW1sM34xTqZtHwL/c
vswdH8lXjZpyi4q+Eq9Z8/U4ivYNw5Oh2nX6sTMUjwe/dvX0YyA5/lxfu/rd6131adpZWvrVgXa+
8MK+eM2a++PLLnsop+1DXTf1fiNvufAp+/l/8vDm5jiXT8lXmObyr6TEfyVnvle/5ptP/+SNobvj
0/EwvPZyiiDp/+zpqcn5PhofuCtLvk+VUTnkMyPxuQ/lF3fP+tf9mIHzx+7Zk98qz19PdU492exQ
rzs0v/t+2qFoNa8IzY+NGy/nySfrBlZHmzatAcSbZHt6h6wboLl5Jv6mpObmujy0PQqsJY4fyEPr
vMQ1vQLRWK/d3TV57q3MKbevLzeYmZ8ns4bgae5rREczHgbHdgb/nlwdmbGZr69d/e71rvo07Wxv
d+2E/MHzoVyApl3vJrdP/8XypdT24ffz8OaEfWYxg/nlXzf0nzrlv5Iz36tf882nNuAGNIYmMxb1
csKUP8K6qkqvIQSIKSnZm/N9ND5wV5Zen2fKiOM9Qz5TVrb/tPW5cjsT9+7Pc10xgwbgWuB3gLW0
tjaOgv5cHhQUDPW6Q/O776cditaamuND1ltX9zSZzEa6uq4nk9nE3Xc/DYg3yfbo1Y+D6wYoKMgN
NJvvSdokBJKvv8SrL/k6yEdt/QV57j2YKNfULcGRnycvkJ+nB8nt45GPBz+2M9TvEs47d76X7duv
J45359zj+trVX1Ojcg4DD5JPIY8sucFdN327ACP0C235bfb7IvtMPt60Y/rhcIJfDYnrhn4zn5P9
lH8cu/mk+sG81W/o8TadUPjZz372bNMgfPbkyVMTXuib3rSM/fu3M2tWPa997ZP87d++lh/96Bv0
9dWzePEjPPTQe4b0Ec6ZU4JPk8rauzdLNvs4Rqj+gPPPX8qHP5w/7vD2ty/lkUe+OlDfffe9hVtv
/Tn/8A8ZHn98J2960zLe9rYa9u/fTnFxiqKi71NdfZgrrniKL37xSpqb/y1x/TirVj3DwYPz6et7
pa0lRXX1YT74wfNHxIv+/hTt7d8DGpk58yG2bv0f9PT8fKCe5cvnMGPGIwN0bN58JbNmzcwpI0nr
li2/TRznty3+4R8yHDp00QCts2bV84d/uIq3v30p3/veY3R1/RdxXA68GlgBPMzMmU/x7nc/l1M3
wH//97PU158PPAzUs2jRHtauvYhZs2YO0Hb4cAPd3a/H+J6/DGSZOfP7XHBBM695TTsXXPAsRUWn
OH78YVKp2cC/Yl6T+CrgvzGplw1AG0uXPsLy5RUcP76dbPYocfwmZFG+9rVP8p73XMQll8zmkUe+
yqlTKYqLd3DBBc2cOtVHT89ee++/UlKSZcmSf2fJklk5vP/Wt97G0qVLcviVr7w3vOHpAV4M1Qeb
N1/JP/1Tq+V1O/AwqVQfM2Y8SnHxPhYvfpSvfe31/PSn384Z/9dffzlR9M80NR2ip+ejwK+BS3La
WVraTRT95qC2P/74zrzX/XFfXv4iV1zxIg0NJcTxqzGvt3yV7Z+HmDOnhYqK/2Dp0lLa218ijn8O
zAa+TypVhFHUK4DL7TNfIZV6kcrKH/Ctb72NlpZ9tLT8J0VFKVKpH1BUVExx8feoqZnHzJk/GDSf
mpoy9PT2XoF8AAAgAElEQVS80dK8nKVL/5rzz2/lta99ctB4SyIpE84FzJlTcvtElDPlA8jjwVDB
IpP1cD2aAGvWjDzf3M/hHu2zPk3joWEyMFxgbSS0XnbZ53MyXCor8+9naGtr58or3Q7afOUpyJnJ
lFFZ2ZY3yJnsh8rKu23938estkSXCXb75SaDp/n61GT1DG7zxz72fb797WuH5cV4xojj9TaMJT10
GXIpGT61snfvHJ577neRy0ypn0rJzNf20bxb/IMf3Majj/4RZpPYI8yf382VVxblPDO4X/y9Cc49
OJ7xPpb3oQtTOYA87ZTBaHYgJztemUGZzBFgJsZa2c2sWYsoLCzJk3HSPSiDoa2tkq6uD9kS2ykt
3UJ19QVUVR0buFe05ct+qKlpp7cXnn12N5kMmCVvC6nUIlKpVmbMqGXhwoP83d+9mo9//Gd5MnVc
lkUyq2PhwllkMp0YV80JWzYUF5+goGA5qVSGiooyDh48Sja7EGihuHglhYUZVqw4j/r6F+jrmwcs
paTkEIsX694y4Cip1DziWOX3Wf7tZ/Xq36C5+RgdHeUoiySVqmbZsib+7u9ezSc+8RSZjJbvK+yn
2yR16aXf4Uc/evug/iso6OcjH9nBnj2FHDr0S9rbS+jrW0JJSROwip6eG5DgKy7OUFjYTnc3mJeq
twIZzEvZf0oqtcSuXlooKlpJUZHr4yef3EMmc8rS9gzGr23aXFhYQRwfpahoOQUFGWAV3d03DNB4
0UX3U1tr3Cvl5Xv51a9OcugQmNz5rOWT6eOCggrgKNlsIcaV4/h3ySVZm1dvhPYjjzTT29uL8c8f
pLh4MRUVnTmZQocP7+LIkduA7wBPYQTt3UjgvvrVdZx33nL27Cnk4MEnaW+fTRybfle7CgrKyWaP
AnPIZjtR1k919SpOnNhHV9dc+vpO0dV10mawFaH9DdCPcSFpPJy07Vpg+6XU9sNCzL6To5gVw0nv
mX47Vhdi9jUUDxpfixeXcORIz8D38nI4ehTL16cw+y5qgYj77vst3v3uqweNJWEqK4OznUE06dlE
p8suGi57IEmTy0ZY72UrDJXJYDIniovvTFz/plf/N+P82Q4jySZan6g3N8vCZI2cLssieX2j9znU
s7cMcb0udpkZX0/cm3w2mb0Uxy7z5M7Yb0cqpXt9nudmgAyVzZWbJXN3os7kd30maY89epNtjvPQ
9pl4MF/y1Zsve0m/bUx8Jvs4H/9yx/LQGWL+M1+xn6L/z2OXZfPNGP4yT7uStOgz2df+3Ej2u76v
T1xf711Lfg41htZ7fEuWlxzXDybuq/P+d30ZsommCcazA9llI9TishUgfyaDycjo7U1mTLizYwoL
e+nry5ftkPyeLxtGNFQmPs2zJmskmWUBudkdSZrP9z6HytCoHuK6Mqr8DI2VQzybzF4C7aBtb/eD
eyniWPf6PK/G30G7cGEV+ZCbJXNeHlp8XujkzBn2umjFozfZZrXXp60mUV4+/jnaU6lVXlmi8fzE
Z7KPff7tw7hQKnnkkZeor2+kpqbK41sys2Yu7iyfZkxfif7fAK7zONjtPbOU/Fk+pQl++fWIP/rt
/MR31auziWrz8LSWwfzzy6rFrAT8e5NtT373505udpKjYfphymcTJZHMLhpN9oDLRngel60wVCaD
Bl4ys+HnwJ8Qx7Po62vNoWXBgsac766+o9511fdiot7cLBWTNZKkrYHcjJ0kzS95n3p2DybDZKf9
fClxXVkz9V55zd49Pv3P22ee855tAO4BdtDdfYzCwiM57XD1qb2dGPeJMqmuZfXq/jy9hZcl05mn
rbEt45Sl5ekEj/yMK9GQLKPdPht51/XcC4lnlKmj7J4jwK/p6vL7Tf+rjGS9BxNld9oy1wPvobf3
It7whp+xbt13mTFjD7m06vMo5iwftX2rR7/qU7v8bLaD5M/yOZDg11HvmY5EufrUverT/baMyKNF
bfR5m483kUfL84nfOhP1JL8f9P7H+216YkrGDIaLC4wmeJT0D9bXN3LNNTvIZFowmS8p4HkKC4uZ
NauE3t4OtIO2uHgOnZ3rccGyVubO7bAxgxRwPfAPGN/pecBB3vSmfhYuXDlA26ZNr+Luu5/mxz9u
oKND1vohli49RHFxL/v3n8L5UBcCrZSUXEh5eYbPf/5ybrrppzQ3zyKbhZKSk5w6VU0c/xHOT36Q
wsJjaMfxwoVFZDJdGCERY3yqXcDngP/X0vwc8M+27bcPtM/4XldifLx9GCuzFePr3Q2sxkzSW4Ev
AB+3z24G7vLK+SXmsLJ5QCeve13Evn0lZDKtGCW2HNjD7NkVzJixlCuuyHLbba/LibWovwsL+7nh
BsUMnqW9fSZ9fYspKTlEZeUymz1TjDkm4YuW1h7gQ5aO72As0Z+RSi0mjmdZXhv/tYmBbAJ+ADxm
aduJsTYr7X0nMNZ7oW27+HgvRoibdhcVdfLmNx/nV7/qorkZ+vv9VF3TtyaNto1sthd4pe2Dk8BH
MELdBYxf97pb+MUvsmSzlcABli9fQktLqz3aYRUmz77RPrcPk00lzAM25YzdEyegv/9jHl/m2v5d
CdzoXc8CF6O5UVQ0g74+OSCOWj7MsuOqByjB+PJvAr6OCeCfjxHUKzDC+XzL2wOkUpBKFZDNZr0y
iy2PTgCvse1p955ZgDnfaAHQhFEKJfaZZ3Axgxe5777XTNuYwZR0E+VuhGnjySe/zOLFF4/7pRw1
NVXs3PnxxPEK7cybt4Xlyytpbe2jvHwxq1bNsccoPJDY4t9BcfFhurqUK38C/+yWZ5+9h927c2nb
sqWKq676N3bt+t2B+k6e/EdWrbqUV73KHEn86KMfGSjjHe94gC1bPk5razuve93hHAH5Z3/2A37w
gxgzyRvo7Z1PYWE7K1fO4sSJWSxYYJRSR0cfx49XYiaUNtgtxLl+LsYosZQtax+QBv7Y0tgIbCGV
mkEc34Q7nriKwS4GuZKMW80cUPYI8+fvY+7cY5w4cSmvec0JNm/+w0EvLWlsnM+MGce4/fb/sjw4
xs6dj/DjH+9g7txjOUc/zJ9fwlveUsmBA4U0NKRobGwnm70Dt/HpCEYg3Y9RhAswSnEvcCEmR74X
o6gyQB1xrGevANqZNauXt7zlcqCYJ55opb39JiRQCwpOks36fBQPDP/6+hbz7LOHKSiYx4wZVcMe
F+7GXyPwFXJXokbR/+IXs8lmNw7U39T0PP39SjnV6mQBsJKCghKWLu0aCC47g8Uc/VxZuYW9e3fT
3x9jhOftA+OtqOgu+vpiy5dLKSj4R7LZ62w9u+jrO25puxmX4WRomj17L93dJ8lmmyw9JRiF+R3g
UoxiudLybC6wkHT6BOl0ycC8MkkU6zEKuQfj5jI8KCzcSxwXkM2esuUamt/5zq9y//3/a9BYqqq6
iNe//rcG8Xu6YEoqg9y4wA/IZMzRx+M9djj/m5Meob39U7S35z9ied26h9i1ayOZjPndTIT/Y58v
w5/AHR2L857Z3toa5dTX0fGX7NzpH0nsfJ6KgeTbGWpOeJRb4LPANrq7b+Sll0S7aPxrzIpDFqe/
xNbmrFvt962Yybjeo/H/Ay4mjn+FcQE1YZTKCXvPTuD99t4D9lo/Tmk0cvx4lo6OTYP4me/lLI4H
RqF0dGyjo+NGMpl7gTuAY3R1fZnDh/8EY5H7SkDtkk98v8ejBRhlfS9xfJfly9o8z+qY5WM8+uiX
7TPmhSrFxfX09m4im9ULZJKbz8S/FC0td2KEpjkufM2aO/nlLz8xzPjbijki+l7Lv98GtgPXk82K
RsOT/n7RfivGMt+KUWp/QTa7jUzmWq//1edGaEdRI3FcYq/35Iy3OO6y181KbvHiwxw6JJ70A3WY
1eStuHiKoenkydswq8JtuPjNt4A7LR11dvzciDE4HuSFF7K88MImzAprI/CPGEVwrb3X9Ud/v8r/
ag6Nph6Dc/lI+zONKakMzImJbZhBMvzxBqNB8s1J8+e3cfJkkQ0CK2Col3FkWbfuu97LZ2S5lWLc
L9swxwn7Ajb/me0LF1aTyXwNY52W4IRmAx0d/TghHLNs2SHWrXtoiNcfzgfei5lI+s0PoorGRbgA
8iXAbcBiCgpupri4lp4eWbZ+QLEEM+naMQJjE8aCrMKtgDTpF+CCqAvt/7/GCYYNnjDz6YdPfOLf
yGS0IUpKVJZlMlg635Z3ELiAXItcQvldwFaKiprp6/sobp/B1zEB1G2YaXIvTnnnPuus/kdxx0MD
NNLXp5VVhS1jAXArhYVzKS6+NXH8RUVOuw4dqmTduu8OpBg/9thh2ts/hRGM99j2PYFxydVjXgqz
IkGjxqUC86sxriX/WnGCb2/AKZhNxPFXMFZ6ChcPMuNtzpwSrryyjz17OuwKuIqCgjqOHi2lp0eB
2u9jFLBWXVgeLbGfDXZ8/APGtaZgcgr3kptvYMbUw7hV9TbgEGasbsOMwXtxY7Lafi7B3zvS1PTw
wP/n8pH2ZxpTMoC8cePlzJhRhwvcuQDReLabJwfO8ePH6OubS27AS1bih9i+/XqOHk0GwMAok2sx
g/gejP906AG5YkUHxo3xF/bzWvvLBrLZj2Fe6fc1u9mpiO3b/5CurmxOu5cta/GC5wpU/wIjhPfl
oVHBv0cwQv1jZLN3WWv/QYxVeS3G6o8x/tlujGKRkCnEWKOa0AratuICwAvt/xLWycC7CWY2NLSy
bt13+fnPC3BHCHwDaLB7Hm6lsHBnoh0KJC4Cnk20XUpgG2vW9PGzn72fNWseoLRUQcgXccHKFoz1
XpLz7Pz532XNmj4WLxYPZtryr8UI3CriWAHVZlvGR4E7KCtrZeHCWeQebaLguYyDj7B9+/W87307
2L79D2lv1xvKfo4Rngrq/o5t4+csb2OMQL8HE8vxA6T7Pf6LbvHGT3JYj1kt3WvbpLoWY6zsrbb8
SiBmxYouMpmNPP/8GjKZak6dOoibE0st3VqZ/sqWtc9+VtjrzZgYwLU4V9ZzXh+mbHsexAWuO4An
cQHkE5ix6Qebhz5exbwcJ3eeTFdMyZVBXd3TnDq1GCOIZEUtprLyMJs2vQcY3eazwctzc+BWNusf
xqUUu9yViF4+Y44bvpVUajWnTrXQ338PZnJ8BmMR1WEsz4Ps2bMix1106lQKY/3JskuuNNwr/a6+
+kc4YfpZjAAr56mnDvK97/0+8AA/+lEvx49vxbgLjBtFboPKyjoWLDiP5uZnaW+P6OurzmlPb+/8
BF8PY1wAYGyLz2ICxA8CcyxPNCnfZeuZjxEypfa3Oy0N/sSVMMsCmwYOTSsuvgv4A/v8cYwANO6M
/v6mAfqPHasjk1loaZXQ2oYTSPMAePObT7FlywcAE58xx3zX2RfbqK1KsXyvLaOLNWuK2Lz5bZSV
lXLVVTs4dGgbRhittvccxrkFt5J7Hk7KboDbiDkuQ/ScsP934B9CePSoxlYDxhWUTJkEt5KT20bv
EtBqTFbzSVycZrG9Jgs9Zb9rJdSOGZf3DdANv4dRVnuBTXR0mH6ZP/+r9nfjporjr1oaVE5sxwO4
1ctyW28nRuFWe7w+bvtNKwXfqFsL/D+4GFaHvbYLM55/hnG3dds+KAc2UlS0gqKiJl588dKB+eVc
p4NdSNMNY1YG6XT6b4DXYWbrJ6Io+m/vt3qMtJB5+oEoiprGSeuIsWfPbNzkkxVlXgN4990PsGVL
1ah8hUn3kFmabsIse3UY1zcxlor8rcbHuWvXfHbvbqK4eB7d3XdYmlowVv6/4IKINwNfAy6is3Me
27d3DLwH+MknZ+CsYVlzDZiJaoK+5eUzgLd6LybpwQR1zRb+I0fU9mu8AOQ/kptjXcZrXlPExo2X
s2bNHvr6LsSl6xmBG8dysyzATN6TmB27J3FL90ZMttBG4JM4n/FSCgoO2myYzRi30h9gAoY9lncn
7b3dmFWDBCGYoPdxe98G+3wKdxpmJZlMA8eP93LlleexfbvcIdWY1NFXYvzWLpc+k7k/zzuCN9q+
FV9kvZsXrqRSN7Nly8aBMlas6GDXrgWYuMjztl/ux1fWhYWfob//QYywbqCvT+6hMhxmiCr8V4Ce
OrURs6KQ77sRoxQOY1yHP8BYyr9t23gN8L2B5/1jHEpL76O9XYJV4/geTPBc98tfL/42YlxG/gpD
1r7hUVeXVlxyIR22v623Zfuxo+MYY+Ew8DFMf98BfBp3qF0a0/+7MMpKSk5804rrIG7lKeX4Q4zL
URlb24BP0de3jb6+G3n++X08//yDbN++g1SqAH88+C6k6YYxuYnS6fT/AM6Pouj1wB8Bn0/cEgPv
iKLoyiiKrjqTigDgyJFfe2SM/BWPQyF5r1M0siq+B5xk6dI7ueQSc55KUdFXMQJrId3dn6Oz82Kv
DD0vt4YErE51/B3gOp54wqQXdnVlgNdjBvcMzGRtsuW/B6jiP/9zNuvWfZdNmy5nzZoHKCiYR/IV
mYNP2ZTFbtwtUMz27Rne855/5vBhWcV/hJnIX7TfZ9lntmOUn3L8D1uarsWtXtL281eYyb6QbPYu
7/dejNC8ECMUX8AIwjswAewNlifOLWaUn+ImciUctbQZ14yxVndj/OgSUFKMUqbG/fTCC/tyTvl8
4okCj2fgAv33YmIt9zJrVu4K8tSpPvvfcZyfWs8qZ7/Y1t9s2yeB3GDb9yZgBanUHgoKVuL3WypV
hfN9X4dzq8y1ZclNdw9FRbtw7qAHkXItKPgalZV1vOIVx3GCVZlN19n2mXtKSuSOarBlrcCMg3uB
L9l25Lohi4sVB1NgvB9jsW+1dG/ArLQ22N/W4jLVtDIpts/cjHO3pey9C+w1jVkZZn3k7luJcSuf
fJsEt2GMLjM343h+Tjum86mlY9pnkE6nbwcaoyj6mv3+a+C3oig6br/XA78RRdHJURQ7YfsMFi/+
AmZQFWM6WoK4ASMgFmIWRe763LlzmT+/M+etUuXl8/jIR3bw2GOHaG//S+CvbLm/xvi4V2EWR9/B
DHR3Vk939wqMdfcljDB5BrgMMxF/hclM+XOMYDuBSU9sxFlVJbgzVgowwvFmXJ7/PMyEVAAttvea
t5ddfHERu3aBERbKg6/HWFZ9uF2bKcyy+grbrosxK5dLgE/Yup7CCLn/bduzD+Mfn4mx6G/FKIxu
S0cxxv31IYzwbsVYyJXAn2KU2aW2LSWYAPWfY3LEG2x72+3nEuDPMBbkXNveQlvWTPu/3AX/jhGU
amen5U2b7QOtsGbYa9W2P2Zj/OZVGMWyyvbBAYy1eRIjuLpte49gXCz67MNkiN2NGR/34PZNPIIR
1Nj2lGCE4Qu2nvn2+iHMCuRSW9/fY1xI+2xZi2w//RbGKv+E5dkh2/bn7LNq+wmMjbYZI8x/Zett
sH1RikmdfbX32wFLq3jwM8w48PPx1Y5G+/2Q5UELcBXwfy19T9ryL7HtmY0ZC4swexKKbXtfgRHw
/4iZE/UYt+nvWd6XYAyQJzEK/TGM4qzArK7/wvJnNeb02TdiNjuu9njSBLwdE3xOY4wQ8fwJYA06
m6iy8t/ZufM/GQpTeZ/BWAPISzEmjtBir/n4Sjqd/kk6nb57jHWMAycxA+8ijABZa68ba8AsgS/A
tyaPH+8hk9nIc8/9Ltu3X8+nP/1jbrzxURu4+2OMFdKGEa4X2DL2YyyN2zFC5hX09nbQ3f05nAWj
IBk4y1CpfSW2HL2w5QRmWVtsr/fZz37cC+O/iTtIbT1mkt2BUQx1wPvIZi9l165enOvlMftbjf1U
+TFmOf0qzKS82F5fhLOgn7LXFGTeZ78r2KnMjXqMYL0dY93fY3l9CUbwiF+xbScYK1IZNIssD47b
dmUtbQoGzrVlLMUI+Iswwn49bvVQYe+pxG1cUywGS9sMe60CMx5O4YKlr7A0b7D3nW/vnWWv9Xr8
qfPqk5ui0+P5T2ydy+092PaIR6vs9Q6vHy+11wpxm8HqMFbxHRhFUOf1zUyMIqjznlUfX2Rp6rF8
VZpntdcf8xK/iVbx4BL7vR2jUPx2VNnPxd4zazFjegNGuOr52fZTQejY8mCFvVcb6NpwsTHxvsfy
Z7Wt7w3kjr/Vtu82YFbPdfaaz5MluESGO7w2LMYogjrMJrx7yGTexnTFRAWQk5rpFow52gpsT6fT
74ui6LunK6SiYt4EkbPMVv0xXACtjdyUNS2R9daj3FTGTKaM3t4+nE9/H7nnoaRsPbJMlTkjX/EK
W5+W+Fp6V2IU0HW4YJncKdXkBol9v7Kye+S+UQaSaNL5Lgcx1lKf/bsOF8gT3crc0XcJ4pPe9eO2
PP98HJ9/pZgJ+FlLVzlmcm3DCdq7bbnPYFYDWZySWIuxEOVWKPV4us2rT+3yz+vZn6BXv4nnao/f
510J+sXrJA/UJ6st/7Z5/SOhL9rER2XwrMClYB7HWM/JM3aG+lyFsc1SGCHmj4/kvWqn3l+R7x7R
tDjPsyW4AHK+Z9OJeqry1JOcCxcmPufi3DS6R+6b5PiTS0s2ZpynntWJT9HW6vXlavK350Ly0+yf
heTadzo5NHFy6tzCWJVBhtyVQCXGXAEgiqJv6P90Ov0IZnSfVhlM1PKruHg/vb0Swg0YwXQrJgin
zVEKQCXfupQCYior23jqKQmq+zCujI24FDb5ewsxA1nKRYN5HyZwtgGXqqiAV6t9Rtfk+37KPt9h
f1f2UpF9bitOaOrZZ3HnyNyIU2qNXjktGOsnSYvSXlXmr73rYILAeqbBtlH3KCOkxdK1GrM6+ATG
lZTC+fYLbf03YwRLG25y7rLPayV1AKPEP4URVocsHZ/0eFZtn1dgVz7jfZYHf43LvrkR0+cF9v8b
cYHXGOdnFg/0/RBGgdxo2+Sfy3QI47rSeGjGWfIpS782n21I1KPPZB/sxvnhdc8vyT37SNf3Y8bW
J3CuUI0D3SOadEaR+k0rPP//Z+yzyfo0pjZgrHuf7hcS5WpO6Ayr4ww+X6ghcY/6/BRGEd+My6iK
EvUdSnxqfn0SZyjpN9Urnqis5LlRv8YFrFMD9Q0nh85RN9GElDNWN9EPgd8FSKfTrwIORlF0wn6f
n06nf5BOp4vtvW/GzPgzht7ectxSWlaIrOyZGMG+GzPodN+7MGmKG4D72LHj1xj23Ibb1JLFDNhW
jHLptX9rcdbNUZzPWFbwvfb7Rtz57WsxOnUjZuJsxaTebcAsy8FNjCMY4bsPN7kb7bMltiwpvwin
ALL2N1l6e+0zLZa2Qts+5ZkX2Prk9duGWZVss7/JGhdNMc4CfhFnCdbjMp+uxVlip+y9GZzgugRj
BffacnVyp1ZA+y3Ns+33coxiVK75zRg3zlqMmyOF24uhPu/EBSvLcO6hjbasezyaxaMj3vN+3ffi
Ng3Ott8PYATpYpyS1ErkuC1vn6VVKZMZzBhqsddnYgT4rV67+my9orXeforGfsxY2ur1zxH7bNbS
1Gbvbbf1LsOM53txqy65KbW6PYpLyUxZvrbaenbb3zTOO+11tUt0XODR2+HVvc3rL80jWexlts59
mHG8Ebcp0Ve4qm8jZj7MwIzjRlteJy4tea3HrzZcVtPNtqwS/OQAl9E1/TAmZRBF0RPAU+l0+mfA
3wE3pdPpD6bT6TVRFHVgIjn/lU6nfwIciaLoXyaO5JGgy/7djNuQIgujC7NsrMUIIWVS/BNG0Bm/
exy/ggMH2jG+TVkcJzATSb7H38C5DJQhoVfiSSg04Py7r7DXJbTmYPzBEjpa5mqPhAKPNbgYwUzM
ZFhsy5OgbcIIyCP22RmYBVkKd+SDfKiXYybHfozAmYmZRBdafsz0ntE7aUWbXBjKSFlgaVyIE6jK
spJbRZZZjFFa3ZbGXq9f5mOUg9ohBVyJiwOkMEpVltl5GN9vcke3+KlV2mtx7ij/yOhXYPzMG70y
qm2bFuAsWP3WhDuM71pL/3pMYkAdZsWhuIjiGFlb1ipL60W2DsW05mCE8BHLmzss/Xfh+rbc0rrS
flbb+pbZcq7D7Xx+HcY9V27rXYrzm1fZehSbijDjM7nbt5xcv/x+cl2XdbbN1ThjS8+Kjgjnu6+y
98o4kPDXPhfVswfTv+txcZ/j9hmNM2X9Fdjfa2x7LrRtvQM395bh9rOAGbPaZ3GXpbnQ1ne9/Sxk
umLMO5CjKNoURdEboij6H1EUPRdF0f1RFG23v30hiqLLoyh6UxRFfzpx5I4Uyvq4BOO/3oaz0BU0
O4YZqF/CDMTDOGv4K/aelTgLcC3OTy73RwNuZaHJoGBjG2ZwKRgnVr+Is4xVnpRNI853KoF1HWay
aPPNQq8eMIsuKbm15Ppse+1vspR0nMIBW88yzKRQiqLcBYvtM42WxnttW7Xi0LIajOLYYPnZilHA
svYV/JWlWWZplLCuxUzkWzFK9HZccLkBpzykVLWRrZTc1ZAE7wGcZS3Xxc3AT3ErM+2g7rH1SEm0
e2Ucwyg09Xuz/a3Ea/O9tl7fdXfc1rkRp8zmWDpFq4KohRjll8UohRO4YLrGoWgTrVnbJ1rpdeJc
jBK0P8fsHajHCD4ZHkptnY9TbhLeUtZSntoMpkB2J25FqjmhHcBSfgftb+JVm+XfbTjlKb6pLI0D
rZo6vWuap932txJ732L7qbhTIWZuKEAs1+VK26dyCxfbdt2BkwmzMePqVky66a32+/TElDyOwgyg
CswA6cCdw74SFzRrxEyEGCPMlLZ4LW4HpiaJntEk3YMZNHtxg1b+SN2TDAJj66zADNZGcl/+Ikt5
LS4HfTfOFy6rWy6QObgsqa1ePfLhVlg69ZtWAhIua8kNuG7DrCaUEVJu+aJ2ibYIMzmVNaw2dFo+
3YXLQNISfxbGipMyEh37cdZcMpCrCf4sLsMGjNBRfyjuIyFabsuSG6za0qNUyjqM0FXeOh6Ncp0o
o6YGZ8HqHikHHd3ciXHFSPmU4rKEdKxCH6avfWGawgiqC3GrwGU4RSuFIbeKdsUqU0dj4Xzbnntw
yrfr5SsAACAASURBVEYZXIstL6QstLHxoK3nWq/uGZhx8gJmnOy2v6/AKPV5ONdmg/1N5z5Jwavf
5HY5D6McbydXocu/fzPunRjltp+WeLyUdV9kf1OW2X9Z3qn+IpyBpJiONoLKkFH2mRIcGnHxwoX2
twrbHwuZrpiiyiCD83dKMMj/ugszAOWTljVRgbNkdBaN8qk1SSUYdZrlCq+eHluPJrKs71/ZZ8BM
ir04QbuP3OCzltz7MVaKBEkF7s1RvuXkZ7TICpdfdB9uMkugltj2SSBp8hy2NIsXR717tHqRO0yr
iTaMINTKqJzc7KcNGCu5AWfFKdCrSdmDUxB7vHLUHyncEJXym+/VqbiMAqG+L1zpjRKQ1fb/y3DB
QnAKRS/0UbubcCs2WehzccdEYOt7BU7o4PWHYh9aOWlj1VOYZDuNLa0qJNi34pSPhL7iQgtsPToC
5HmPFo1NCWcZI50YwSuhOsPrJ22mnGV5uMS2R0pQY7iZwVleWo1p7C6wn3JBlXn8F/8qLQ3YTyl4
3x2muJWekcGie2osjaq/CDfH1A9KCvHTdsEpMo3H3bZ/fJQwXTFFlcFynJtB56FoMCl4pQEjgdyC
sXZvxwnNGTihfSvOPaGJXYmxxOXj3oCzWqV8pCSkfLShRwJpLU64yU1UgbHqZuJevCHIvyq3gN4S
JUGyDLfLU+WKNuW4a+UhwSEBJqtsJUY41uEmmKxJBR3lx55jf1+KE14SqHKRiSdaAWm1Ng+nxBSM
ldVWj1OUG3BKogonLFP2N2zbJYh0r7JGmjDHUSjX/UGclX/E1jkXY1GLB4dwbicJDyl6raBkDe+x
dffgXC3ivcZKI2ZMavUyF3fYXIxRlE0440PW91qPf3J7LMHly6ucHkurxnVk21tg+SxhvgSneEWj
rG6Nh4PedTBzRjTpU9a+VnnqN7ljD+CMDfWXxo5oEV//L0ZBagWn+bMVY7w14N6SJ54rhjQD4wm4
FRdXk/EmpSZlOgszr6XAUhiD4nnbb8/b79MTU1QZaCPKNsygqsINVvlblXXTiRkoh3BCsQcjNKtx
VvhFuInmv4ZQFquyVRpsuf6yvcrScRtGwGvpLt+lBOpJW5YGsdxZL+AGdCNm4OuwN9W7BKO09D2N
mey3MvjsFmVJKTahIK4m8kHLR8UCFNATPbLg5U9fiVEwshplpYoHEviq/6ClqwLnR1Zwth1jyUJu
XOAFXIC8gVyBtAqzApLCVx/UY9weFbgVjoLXsvLVP2qPVhczMApjNm6VUo1b+aQwPvzbcAK+xPLy
ZtwRFhncsQpS7H5ZsnwXYMbfBty4kMtFylsrA/VFOU7ZzLE0SJkV27K0SpPbqgljFGzErYQ17tVO
rdwkeIu8OjW+1KcluIPebsMYRx32+nFMPx+0fSJlqriC+Cj+7fZ+09gU/VhakivJpbZvFXdR/EmZ
TxrXKYyBdLvtozrbbsXLbsBkE07NPQQjwRRVBgdwvnVZH90YC11uIvkVFXCdhYsRaHJoEspCk+Wu
OEENbjJrEvba+2R1yYrsxQzEBThrW+4ZWWZSVBrECkYfxQkvrRr0TAPO1bMS5/Z4DmdBSnn56aAX
ejS2Wt4o6A3OzVCNE+AP4pbVmpRaLR0n19Uj61ArEFnHCpBr8p/EHQ+91vbXXeSmw2pCr7U0dmEm
vQTSXnLzyVNe/9RhhJvaI8XYYP+0WpH1Lb4uwFndckMp8K8VkPz+Sv2swqxK78IpTQlWCRn1rdql
ld0yjwaNC7k5lL6p7+rjDtwOd63GtMLSGFYAWcJ1Lm5HsFaK/ruI5Wq8Fmf8LCZ3xRTj5tMy3NvF
LsS5gkox/X4HTjGJ96JRCt7f2CgXlmjQKkJHxyiOppXQEdwYnG/rU7aZxrX6T4oYnIHon/wqg2l6
Yooqg27cC1Q0oHVIlgS7LB1NrItwQTYpDOX/ayLJrSML6ghuMqfsvbJkNBBnkRtQrsLFJGTZSlhK
2Cj/X/nTFbjgdnL3pvLMJaRVbwFuT0U7bk/FPTgrWEJG6XriyUoGKxBZ1HKv6HfxohKnJOXO0EQW
jxSE9vP0JSCSO04lcHVqqWIk/RjFcAdOqUqxKz9fClo8j3CKQy4EKVods51MPa3BCVitFrosn2QN
K0mhBCNcn8UpQq1EZOnqnb296G1mpm/67Pd6nKKQQNSnVj7ijfZ6nOfd42cerce5aCTEpZwW4LKF
ViXKU79oXOjZhZZOZaRtw7kwnyH3OAr141HvXl2TsaCYlJ6RYmzACW7NuUbLv6fJNcSkaNpwbkHx
p9s+p+MutHqS21D91ocbZ3g0TE9MUWVwPs7y0wSToJP1pRRDbcbZhRmACmwpa+R5nMLQYJNF3Y4T
6FI6EoBlOMF/LU7BNOFSPVWu7pHA1XJW2Ri1OAvP33Ube9c1oJXlcwFGkMta24dRLlW4Uxy15NcJ
oWrXIZyfV5uLpIRm2OvimzKHGnBBU01kpR/KXSDXnRTbapyAeJHcXan7cadXNnhlleOU5BGM4PPf
4nWXV6as2D7cKZdyUYkWlZ+0VvfgFKEscq0ilmKEs4SQlM98jyYpKglrQYFcpdJ2YQRcCU4xaBWm
+nW0hCx49fVuXMyrGBe70QrgXq8fpcDaccpZvL4YZ937ykiGRQan3Lpwxg/e9ZStTzuRy3GuKdUj
I0fGiAwJbUrTuNyKcTfdgluZSlQtIXfF2oZbHUuwy/WncaG9Cpp36rcLMPPlHsyms3twqc3TD1NU
GRzBWeh6yYgmVAO57psie18pbqBJUMzFrBh05IKeVTpfCc4ikwUoQaRUPFmnstzbMIOwGmeRafJJ
sMtCk+X2PE5Qd9tntEzXBFBmhs4FasYd0CVLXZaYbyVfi5tYUmSncJO+2CtPgknuN/naN2AsXyle
3598my33DpxwEE9exO00lZtISmYJRmj6mVvbcKeE3u7xR1avBKGEzSHLq0txAm+RpUXtUPlyV3XZ
8try9I+Up/pCQU1Zr9Ve2xTM1M70meQG6/1dtxsszwttm5V8oL6WItPxzkdt3eU44XUMY23LFddN
7iF+lbb9y8iNZ/kuTqUcN3nPqO/lptRuXiViqCwpTK2mD+GMAwlhbfiUD19uqRrLu7Rtg9JZ78Ap
dKXBynWrzLRyXKxKgl2rVyV3aKXzGku7DKoGBr/MZvq+3GaKKoNWcg/HUhbJPZhJdw+5qWopjBBN
ZoIogOZvdFE+vtIttRRWOcrIkGKRsNYArfDKl9tB9coS1ASuxwzmU7ilvXYAl2MmouoT5NroxllG
1Tgh6Qt9XdfyWQG+FozAkdvrXtxxBBJ2Uqbi41Kc9SlaFSepSNSnyXgSIwDqcIL9MsyEVcxA18WT
Q16dfpxmK26lJWGjnPF6XMKAypNgF03qRym338RZv7LI1T9zMEpO7inlxB/x7pGwl4CVFazxoLRN
CdMLyN2BLuEG7oiERTh/vPLmJSSLcEegJ4X0Vpz7ZY/HJ1nMGtfijYwS0VyKi2MsxWWZpXCKX+Nf
SncVzgCTsNdY1bhWdpHiey8yeHOb+kVjuRkzf8HtJdBKUxDdqk9eAcWUumwZ2sy5AbMDeYOtZ3pi
iiqDUzgBpwmmc39kOfvWQYxxGx3CDBJNcg2q45jBKYvJz/LQhJJVLDeUBLxy4VWWJpcyWl7ArTyU
VSRBpbNVVuMChbKIJIxVrixrLcmPkyt4/GW0vxFPFqEyQu7FKRq13c8mUvlJ4bYQI0Suw7l0JCTF
NwlV7VQuxwl9313k94vKl9Xf5fWt0nZX23rFRwk+5dHrOIK1XvkqVwJCKzsJtX24nb/KfZcgOoFR
crJ89bKgJo+XGl8SsGrfMVzGi99fL+KEp3ZDLyJ3v0g1Loax1vJIQrKE3L0Vqn+e5ZcU8ixcGrKO
FDmBMz7k0xdPZMiorSpfVr0MC//oCpWRIXf1qjGjvvBjCNr9exgzNuTKkqD3jy2pwh21ojJvw6ys
NuBWihqzyuhSDE3HsVTi5iteedMTU1QZlGEG5624QeTvM5B1ryDcNow7ZCm5Oe0SOv6BYXLRrMcM
TC2LJZhk9UsovBJ38JlcTLKqYoxQKbd1KU9eriedSV+PGdA6gGytR6PKVbuUHlqKEwD+YXNbccco
aHPbb2CETb+tvxq3SpCFKxePBEkDucpuLy6l09+8F+OEWDMuwKvz5NU/orXN0iTBK9ojryxtupK/
WvU2Y2IzReQeg3AM1/9yQy2yfIpxp6n6yq0fp4AutPzR+JDCEO91iFoJRtE24hS7eFCPc6/cgVvB
qX2duNWY6vXHw4Mer3wrWbEv8VhGiRILspgxJgXTjxm/2DZfh3OHpXAHFW7FrQYX4VYAokEB5Qbc
anKrLV+KU284i219EtIy0DSWdUzECtz7KsSfDkxfa+wqbqO5Wc9gt2GLfUaKVhvvtFJVXGgJzg2F
/dTrOqcfpqgymImZHHfgcrM1SSQgZG3J8qjFTTL5ebOYASiBqMHm7/qtseW8AjPZ5eeVC0ibnTSx
ynHpcdU4y3kWzpJRoE2rgIUYC/ounO9c1q92WEtYH8VtTDqJS1G81pahyd+I8+VrhSBL8Qhu048s
TAnAi2wZCi6ewky2mbjJ3YYRoCpPAlZph7LGWnGnr2qFJZpKMcJK/bUEd66NYgCyCrXX40Kcz/12
nNDRKxMfJFc5y8c9D2eVH8KdpKm4iQSg6G4gVwn0Y3z4q3ExFglyjYdV5O7ulRBSvy20fNuFMyj8
GM5aXOBcbpbZuFiEaJxl+SRBLyXYZNt1gdeX6hfFSbSyk/I7jNllfhgn/FWOYh0xuXEVjQ+8/llq
aZThIP5pHilTbDVuhaPxXYoZD1r9yQUoIyyLm0fiqV74pMC0DjQ8gOl7LD0tuHjC93DnME1PTFFl
sAg3cXWAVtJKbsBZAtoYI7+yUiA1WGVhyGLX97k4y09np0sJyPrSpGnHCIx6nJvIt/Q24PzIsmBi
3M5J/3iNaxns49ZklIWbwQljTWB/qb3Bu1f3aRdmFy42Ib7JZaD2FmOUygLMROvGWXPKxtLwUqZO
tUebBK/eoHUEFzjehhMkchsowOsrdLkZdK8+/c1nMUbQqU/FYyk77SVQkFa56i/iUnKxNPh7HiSk
d+HOATrI4JcNyepUgF/KVSmzSkWtwfTzJbgYiAwV9a2UnOJPS3H591rpyK2nerSikpKNvHKLce66
DV6/iEcX4c5zkpt1vr0uoaxDCTttmbK6L8QpG+1J6bX92I0RyhLe6qd63BhR0DmZAi4lIYW1Gjcv
FR+R61ErE9E6FzNeNU67cMeqNNvPVqYrpqgyaMIJL72/R1ayhGkTZkBqImdxWSiyKOX7luDVHgW5
Gs7DCRG9GF5pnBKm/u7fOzADU24ALeWrGRwj8FcirbhJLcGggKoC1cqckIW7EDNJdln65XK62dZ/
L87FIMWlDW09Xn0KHMoK3o97F8JFuIlXg3ObVFt+KdNFAspPldyKEX4S3Jq44rn6SVlFEsAFOAFx
CqPkJCAkrCUI1U/zPZ7qdFcp+gvtZz+5byY7hbG6X8Bl+RzCjBnFQHQwn7/XQspS7dDxBhLg8o+L
r9ro95K9pxE3ltS36lMdp6CYUoxzl2jvipSpUlvlXlzpPVON85PrCPAU7mRcrUSUQZTFWe+/iRnX
EsAyMGRhy4A5iFOIDfb6Csz4SuFeMaoMMbmLVN7FlteKd2n8yTiR4lLa6zbcqkR94Cdx+EebKK7R
Za+9wpZ7KeGguimHdpzPXgNNgkGTROfkS0gsY/BpmLKcT5EreH8D94KPKu95LYXX4yaw3FN+Zk8D
uRatJkAymKpBfR5uOS6BKv+urC8pqjbvPi2PFRCP7fdmS6OOwZ6PEajVuGV9N0ZoFdvyZmAUi4S2
Nu5IALfiNvop3nACI9yk1DShJfTOxwnuZOZTcjOalN9xr3/mYASAhJisY70w5iLczmC5XtTfolH8
0zk8/rt1ezDKwh8jdbhsFNGq/tvL4JjEAozA1tg6Dxcz2IYLsrfhNsLJWJDAVZ/K/aY9GZ04l6KC
8uJTjOljBUQ1pkpwylM8VpvFV7VXgddar9xf4lYLW3HzSRlPUgALcSuQpV7/aBWzFueG0zw4gBFJ
N5O7glO66C7cCiRrr3fg4iEai4rtqT1Kg1V/SWEux6Vb/w7ODTU9MUWVQRUuLa+E3HRQCWsJGW2S
OYyzho/g3CYxLsAmS7oBJ6w14P2NT1IoW3ExC03g3bgB7p/Df7NXvyaPhMAhcjcGbSV3YvmbjXow
grbAa6OW6Yo3yCqWr73H8kSxgyO4fHy9PKUfo0iUVeIfnqZJqYycavtbMni+FCOIdHBeAy51Ve4F
8VZCWjyRFVmB88NrksvvrjjAHIz7QhbgEZzl2pIoT7GPRbhNgvdgBKEERVJZ61RUxXQUW5L7bIOl
+4TlyyycBS/eSBlJSJ/n/SY+KslhgeWbhGgBbnXTgVEQUvxyyWmczLDXpTCX4DYS+hlOvlUvHmks
t+BWYzNt+87Hxdx0plQjbj7swykGvx9kuPjGgQwmiSO5HdfirPlee12uILk6L8bFSbSC19zXPNZK
Sn2g+FQLbh6BczVOT0xRZdCFex2jcpiTxzhICcg3uQg3+TSYJCiO2bJkYet1fQW4gShhpp3GHfZ/
BXRluffi3DJaaZRiBGQfRnjKhaBlbwe5aaCNODeKNjfJ/3ohRqhkGZymKQGk7/KlatIqKLcap0A0
getxr170hXUtLgCs/QWadE2WF0oxlKWmbKpZlv8S4IqPSJgpQH2z14/V9pnncRNZgl0BVwnxfvts
F7lvSlMcJbZ92oV7+Yt84/Lhy21yD04xiTdSRnIJXkruexnuwMWM9KIYlaGVq8bcYo9vEuhSxOJR
8tgF/30aflBeR51ch1PeSiLYjxnfJxm8uVH3ak+O+qsN55bRPFLf6g1/invJjTMPN44VQ9Jck3I4
aftR7e0n98VH4qO/UqzGbR5MYcZyl22z2thhyz1F7hH0Ot79MO7IlkZcXEdzZXpiiiqDFsxk2IAb
RJpoCvSC2yAlX7Um0OX2U8t2HeMg3+QijKA+D7fzsgS3+UcWzV04N4usky5cwE7+0KVePXW4jBat
TLRMvwd3RLXcU1IoEuQSNqswLpiNOKtQAlHWr1w0yumWAj2ImySyMBVM1GRXpoZcDse8/8XbDvu/
grTKA2/A+WylcP1zd9ZjLPuNlq934YREhLFO72DwTmq5C+R2KLbPnvB+q7Z962/Wu93jo3zrDR6d
stp3kasQRbOU7ku4lwv5sZQUTrHrXcH6LiG+F7dC7LY80AF8KuP/b+/co+yuqjv+uUkgr0lWEggJ
EyATIDlBglJeWgUfvLQ+moVWCfGJ2nb5WHX5aAONjS1LZELVVdCqy1BKVcjwUBNQa4GKElBAtEq1
cDDGiZAXIeRNXiS3f5zzXfvcm0lyM5m5E2b2d61Zvzv3/h77d3777PfZPxkaGuctmDchgSeF2Imt
jta+UjoK6SiPJiNB+8qLlne7CfPGHsPCN5fl51QK7Y1YVZj4TIK9goXBOrDXfOpVlEdjXoLuR/ys
vl26d+03DONvKRVBvYmkeM/Iz09dB/ZgRofaUXgL636GYzGB0InFSj+DJWnbqJ2MVay9QPlijTLG
KUtHVuxzmECQEJHlJGGg85exfb2lSZZZvcV3ImmSSBA/i03Qo+rOV/aT0f2IVr2DVpaYvAtZZWo7
3FbQegVp4stiVZWFJrQEiBTLJmwBjzyel2KrpC/LtHVgcfLBmAIYks8pgSolJ2GgcdX9bqX2xS2q
j1c+qEwuKiw2CrN65UGJP/S8lOOR0BlZjKWql6Zi7yLuoHZh13wSj1WoVcrlorIqJpD0vUI1rZne
GcU9KxwkC12GxtB8PfXgUs5GvDILywcpPq6qn/VYZZEs9WFYfmM+VmwwDnvV5JEkg0qLHfUM5DlK
SIsvOgsadK9Saor7i5cVptmAdaTV/cgrUzUY2ArkdhLP1Xd51byV5ytPfz3GYwqX6n0nwggGKvqp
MliPWQ6yGiokC1CWTCe1k3ESVrOtsMOzxTnkoiquWCF5FWoUpncRS+Dq+rK6ZFEfh8WEZa1K0IkW
KRB1q9yMCclypXMHFvYQo4u25zEBLktQ96WqDpUqljF9WbMKUUwgCcCydHYhViF0NPbCdQlPCcJy
3UZpgSpnsBR7V4QWikmQy2OQd6TrnlrQqzyKPDcJBSkJXVfPqYpZuLKCResqrH+O8igaSwkxJc0V
F1czOK0p2EZtaK8dW4yofZV3UmhO/aNWYWFI3bOeuXJWofh/Tj5GORc9YwlChbBkqZe9/UXLjnyN
DSQFpGcqxSjhOgnjFRksUoTlgruFGA+/gHnA4n0pNTUL7MSU6WX5OhNIvHlUfmbqj6QWGVpoODzT
fgKm6DVeG0nhUtEyNp+rXEynMVFvKrWj0OtQBx76pTI477wWkkCYR5r8ZXloaRmqXFQVKLJ2NNkl
ICQ46iuElmEx0xZql/gPIwk3CZKlWPfNNmonuSoyFAoSE3fmrZJ+cuFL4T+GWkaXMN2CWWSy0CWM
h1Hb4llJOQnZlcU4ySuqYkISzHotq32kNAdRuwJZ+8pq1H4jsPCaVsrKSpUwfDqPibyNZey9mE2l
mBrrqdTGy39LEnjzsGSsxlrlmkpIKqw4oXgOet7KdWh19Mp8b2ALyxSOVJiLfB878r7KHdWvkdiF
5SIU0pFSkMelChuFWcYWNARsMWBpwMhb+iOWzFfjQik3rXvRc5KAVwO4dcXYKteismi1uzg2X19V
PjPyPjp+FrX9rq6itkV7Jd/fYGrXS4ytu265ep88jqUBoSgAmFe0M59LOQR5coPYO4HsvYn6FW64
4X0kZnwJJkxkNa6gtuzsGdIkOAETXlrOLgEhi3p1PpdaMqtNdRm7X09iuG0k4VZ6F1dQ65WoIkP9
3aeRFMVqUuxYS/tXY26zVk7LbVYlkFzylZm2bVhLDk2oYcW9z6K2pns2JmTHYfFeHateMEq6SRBL
+E3GlOYukmWm8dK+GnMJwk3YZJRFKytbgkrjJsV2LNavXvFesbGEp0JnomcI9kYrWcE7SAaDnpOu
X7aPkOLVG7RE97h8rCxaPZO1eczVWbSar/M41rCu/rWosrCHYkJNK8S1EE+WrQwPJdPXYMlyPQfx
iRSYaG4jeXAvYIl+0aJtuQ7kN9QmepXfkqLSPQ/J4yfapYTUa0nhIIUHwTwctWoXjVWs2k9tKEqe
mlv8L89nN+YlKzGs33bk60shqiRcyhCMr8Ce+8BEv1QGY8eOwR7yCJKgktCGNDnBqkfkmpe9WE7B
XGKVgCpurzDLbvZuKyC3UxamQhZlR0hZdhKSilt25r+XkYSv4ryDMDdZE1b/l6GgJzA3uw1L0D1Z
HFNazFWSZSaBJAu7XHGq33QO3Z8EpeLOv8OEjOLKEuRa7auQ1lqst1DZVqNajJPivWX3z3bSRNZz
UOJdk185FlXDtOT7Oxpb6StP51hScnkzSUDo+uKBI7FQ2UkkhUk+byUfW1+nvxR705m8PrVGkGUt
AXtq/l/hlWnFMbovjZ+sZFnuOtdEbGGYqpVGkvgALHxDQetubEGcnm39Ct5p+R6k7CTkOzAPRAJc
/K3fZdjsoHZ9yaziWIXm5JnKAzm++E4rwbVmQO+BKCvGKvkZafxllGhMZAgqRyFjoXwLnPI/dxU0
DEz0S2WQIItJW1lqaool60RJxk1YwkyxWykUWR5ibpUcrsMmQxu1iWNZZvIYdK5VmHUjASfhKU9E
cV4J4KlYZ0lVRoixZRHWN+tqwSaM2hvIulNeYzD2gpV52CKxDdRW97RjlppceglKdYDcioXXJhX7
VLAQj7wXKdvN2JoLWfmdmMdWpbbdNXk8pQBFi56H4szqTLs93984zANUmEHGwSiSxSyhI5rVpbaK
CfBh+TjF+zWOEqITMQ9jQ6ZX5xP/6dg/YC2sZ5Oe9WpSsl73o0V8olVhEPHSBsxL0Hmq+Z7VfFAe
lsbxuIImhWkUQi3f+VB6u2DKUivdR+dj5d3K81ZI8sjiGa7CSqarWMhK/K26/05s3mgcRZOeufaV
J6JrXIblX2SYKTelkKC8XRlhS6ktLd2T/x+Y6MfKoIK1Y65giUMxuib6Kqw6RgJWMXVZ8LKkxIBi
/J2Y9d5JrfBS903VPqtJ11as86JqsyW027AEWDsmKBUXnYeteVAISROrvo/SGvZuo6wx0LG6v+mk
l4GrbHUHNnG1wErekCbS70hCQdc4HQuvSfCJFiksCW8p6MmYpzEU6+GkxLFK/doxAf9HbLFXGdZQ
aewcLBGu8MBTmEcgWnR/EjIqg5UX+Cy2ylYWsjwQ5V7kRSjRPx3jK0geqBSJwita1VvJ5yoLDY4h
Kc6ShlnUtoVeSG15r5S2hJoEfX2eQ11U12NKZUu+JxkJepZlh1KtdJbA1VgovKZz6TmJl0/Mz0q5
h2tI/DAvj9M1WCJbubmtpHl0ZTGOSrhLcSgUtKE4t8agbIxXepXiMb3RTy+n2l48B61AlvIbeOiX
yuC55zZggkFhnCn5VzHVu7C6fbmlqofXJCwrWbSvKoLEdHKXVZZXIVlMCtEoDi8BMb24phSTJqNo
00Klk0kTYzy2iEkhBL2RqY00sXTsinzMSfk68zFhWcbal9P16wIlONSDSPFk/aaqH3lPaoewGuvz
pHCHlM8zWGOyWdQuGNJ5ZQmelO9JK0+loDTBj8BKLGWRKzHdRq0glCI+ChOKYzK9a6hNQmsqVDCh
LU9R15ZhoXCN3jdQvpZS934kVqbYjr1CVUKzjJvPzdeSVd1adx21bx5LUmbl+6f13JXXKt9nsbDY
V/NBykBK7grsLXziXa1Q1vdjCprEu2Xn3nbs7X0azzXYeySmFsdehXkcg7CKtCvy/ydiLT8U5lIY
dx7G/+UraEuvu1T02opmJZQhzc8JWG8q3f90Bir6pTKYM+c+zOID6065HFsE9hi1Sc+3Yxb08eha
3gAAEfZJREFUn2BhDk3OKzBhJstpFLYyV4kvhWvqrRT1yVmGKaiy2kZhp3nULkSSMlIsVYJUIZ02
TJnNx/rnLMNWo8paHIW9G7aMtcvSlLU/FbPEJVi1VdVPuT5DFqLCDercqqqeiZkmTeCykqb+he2d
1E5g3a+8gOOLZ6vQiCa91omo3FJjv4a9w2mjM40qYdUqYoW/xmDJeRkFy+q2ZUmpEvPyEhTy03Yi
SRAqrCYhroVxbezdq6osMZ1NUjT/hFnn4zFFIZ5cms9fXxSgZzwJM2bKkGK5AO+IfE3xx3BM0JYJ
dikheXSzMMNpdXF+5Qj03MreW6Uyn4DxyJTieShUNhLjByn6kzBFqPYtyl9I4UtZry+OUQhNYw3m
HQ1M9EtlsHz5aGzCKiHUQmIoJbHOw5JIHcASjEnL5HNpFY/DFsCI4dtIgk4CVxauhKdiumLIZ7FY
sOLUqodvJSkNhVmOIQm1Z9i7zFEtBSQI1f2yDHu05c+awMOw2GpJq8pvlbtYiiUp5Qlokuv7UhjI
W5IHMhkLd1WpbZ8gJaqOmgpZKRGthGd9ea0m+u+L86wufiurSLaSFKysYlWLdWChoxaSVa81Crqe
lNLJ1L5dTTTOw5Ln9b1wBhX0auzrQ4AKe2i1bNn/RwJX3onCQhpreQplN04JTXlq00j8KEWiaiYJ
67FYaFS01CfrlWdQInY4tkCybITYTq2XLONLK4rLtQ1q2SLBOxd7X4LGvKXYpyxzVq5sTnFOhYmW
YYpha75XHXNEvpZKZUXjc8U1ZDh8A3sp1MBEt5VBCOGLIYSfhhAeCCGcVffbhSGEh0MID4YQPn3o
ZB4cJk/eCLyDJMR2AI8xbdpmZs58AbME/hMLWcwixQxPJDGE2vVKmEiYBpLVpRhkGzaBZOGKiSXk
FFpanf9/GdYFdWemWFZbK2liS0nIsh9NUgz/iAmkFpLikMsvptb9jcQmmYSZJoOsyLL8cSHmMq/D
hGMFe1PWRkwwqc5cIbVNmLcgYaMJq2OUU1Dd9x5MmI3M96Y6fCWspaylhFqKMZUwhiTQ9SxUgqn9
nsYUXtn9dA7mEZQ5nfY8jmWrDUjTZQRWVilFPyr/Phjz7vQcNNZSYKpeA2s5IU9IYS/locjPUK/K
FB9KCe5g70IFPcMyPHlKMVZLsYII0aLzlYu0KpgCkaKaRRL0v8FejSp+F21DSR7QRmz9gsZaIcVq
vsfXUpsXWoXxleaAvAtZ+zJK5E2MwHI7Z5NyX5oLerYqXJCHovDlRsyIek/eKvE/8NAtZRBCeDVw
cozxlcAHgevrdrkOuAQ4F7g4hNDUQNy1157PzJm/4vTTz2DmzNHE+BEeeOAtLFhwCWeeWcGal1WA
NwIdDB/+DVpb1fVyHNavXnXmC4FfkSyp8kUznVjiThUtHRgjahJpMcs6jBmPJ00stXgYks/Vmvcd
T2Lq44CPkYTyNNJkOx0re6yQwh9zsJr4Ywq6Vd+tiasJJYtJ7ZtllU3HLH5tTyBZnPKKFLo4O1+/
rEVXKamqM2T1TyEJICnK06j1Fsq3oL2CNLGVrFeIbg8mhCWsVEWic0mArCqOkWJS9Vd9XyGFb/bk
sZDHVJZnnkJtXFznkBI/NY/TVViMuwydtWNeoRRwuShMOZ1SoU/OY3MV9jw1fvIi52LWrhowKlQn
61jW8jZMIcqbVbhGyro+1n4cVnE2nCTIpRDlKahsWGNfhvgUitO6Ail8Jca35uNbMb5al8dCCln0
T8dKgaXcFRIrk/VzsLl5Qv5d5bfyYCaReGQucGPermSgoruewQXAIoAY4xPAmBBCC0AIYQqwLsa4
MsZYBX6Q928axo4dw4IFl3D33RewYMEled1Bwi23fJSZM6czZowsmTHALC6+GO677z3MnPlNZsyo
0tp6DTNmDKe1tZOpU9sYNuxxKpUqte0CnsOSbRJMKn2TYKpiglDtHWShTwFOo6VFVlAL0E5Lywu0
tnYyerQEvKo5wOLKsvpV2aLQxREkIbEVa42gMIYm7CCSZ3MGyU0fnLfbsFd3qjxPNdp6o9ZZJIEo
wb8zb8/BehCp3HAqtes7tNhH6xmWYQpPSlTj1olZv6pS6cBeUzkX86gkdLT6VUJB9et7SApqOUmY
PUZttc18rJJGdktbPv/jxThKuezGShXL+Hknpsy03kNKbBfWIlt8QjG+4zBr96n8HCTQFc7TMVoF
3klSYp/DQkryCLRwTCWma7AmbfUvnflQvs+zSApYHorGZBn2MiOt4FZIa1seV3UK1dw4HjMuBpN4
UF5e+Wa6duBPsRXd8qRUOLAda/c+D1MOMjhOKOiU0lEzQP0vj0fek166tJ1kzJyGvdzmbAYqhhx4
ly4xEXi0+P/Z/N3SvF1b/PYMyVxoGq6++stcd929pAeruOqTJKv6EZLg+hGJWZ4HRrB48dEsXvxX
pDDOM8AxrFz5QxIDfwe4EHvT1U9IjPTfJAE7G7g/n+shErPdRWLYJSR3+KZMwyLSEL0i7/MWtmz5
MUmo3g+8mi1b7mHLFtG4Hvh+3vdVeZ8I3IGtH6gAtwKXAt/DFMMMktC+g2Td3o71sJkPfCXT/u28
XZy3C0iP7Mp83p0kj0gJ2tnAzSSheDNJuN5GEmbn5n2eKvb9bt7eShIMt+ftLaQ8xluBr5NCe4/m
66oz5j0k7y2NTbItni/onEnqm1Re72aSAlicf789X+dtmc7ZwLfyOPwIOB/rZKtzPAr8PH/+ErYu
oJrPNxt4gPSsb8VaL5xJUnp35/PdRlLQi0nKfj1Jkd1BCnE8me/3LpJimA08SFIc38t0P0QSkotJ
VvXt+Zy/wMJgusfl+Tq/JAn9r2Xal2DPeBzwhky/xno28FWSgrgjn+vbeXs7FpK5A/iL4vn8AHgn
8EPg3fmY7fmZ/Ibk3YivPp+3iuvflI/9aqb7fpLS2kXi+Z15bN9F4oPZxXjembfKvQ3KtJR8fFc+
fweJ73Wf3yYZBQ+TFIXWMcQ8XpczENFdZVCPSjd/6xVcd91GkiK4hsTsjWznkxRBV7+xn+/391tX
/1P3uRHaurpO/Tm62kIKvezp4nqKj+7v2Eav05PH7Ov+uhqL8reu7rMR2vZ3vakHoL+rY6vYwsF9
HVPSur/7aoTGMxvct9wezL7dfbZXYvOpq9+uIgn9+u8P9jrdoa283svzZ1XGNV1cHTborjJYSTJv
hVaS36jfji1+m0SDgbjx40cdeKeGMC1vK1h1zYG2rZiL3+gx3bnO4X7Mi4HG/nbMi4HG/nZM/bF2
jgPJoZ6TU4cXuqsM7iaVtiwIIZwBrIgxbgWIMS4PIYwKIZxAUgJvxkoj9ou1azd3k5x6xLytYhUE
B9quwBqcNXpMd65zuB/zYqCxvx3zYqCxvx1Tf6w8gyf3K4fGjx/Vg3KqZ9BTyqlbyiDG+LMQwi9C
CA+SAscfCSG8F9gQY1xMykh1kEZ3YYxxaY9Q2yA++clRfOEL95DcwN/n7RN5+2De/heJAdSobByp
WuhKrJeKWj18L+/7nbz9Wt525OMrwH1530X5/0V1+34zb2/BVsN25O29+Vht62m8jeSIXUmKdZfn
vSFvb8pb5RBuJMV0K6TYenlMI1t68ZgFXRyj727cx7g1i7a+OObFQGN/O6b+2Gmk/M1XSTmdgYdK
tVrtaxqE6uGocZ2mxnA40uU0NQanqXEcjnSNHz+qcuC9Dox+uQLZ4XA4HAcHVwYOh8PhcGXgcDgc
DlcGDofD4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cGDofD4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cG
DofD4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cGDofD4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cGDofD
4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cGDofD4cCVgcPhcDhwZeBwOBwOXBk4HA6HA1cGDofD4QCG
dOegEMIQ4CZgMvACcHmMsbNun13AEqACVIELYozVQyHW4XA4HL2DbikDYDawPsb4rhDCRUA7MKtu
n/UxxvMPiTqHw+FwNAXdDRNdAHw3f74XeFUX+1S6eW6Hw+FwNBndVQYTgbUAOfSzJ4eOSgwLIXwr
hLAkhPDxQyHS4XA4HL2LA4aJQggfAD5IivtDsvjPqdutK6XySeBb+fP9IYSfxBh/2V1CHQ6Hw9F7
qFSrB5/TDSHcCCyMMd6TPYI/xBiP38/+84H/izH+R/dJdTgcDkdvobthonuAt+fPfw7cV/4YQpgW
Qrg5fx5Cyin8trtEOhwOh6N30d1qoluBi0IIS4DtwPsAQghzgB/HGB8OITwVQngE2A0sjjE+2hME
OxwOh6Pn0a0wkcPhcDj6F3wFssPhcDhcGTgcDofDlYHD4XA46H4C+aAQQpgBLAK+GGP8Sgjh1cDV
wC5gC/DuGOPGEMJLgX8jrWm4M8b42Ub6IPUyTZ8FXktaX7EoxvjPTaQpAF8H9gBPAh+KMe4JIbwT
+BgpOb8gxnjjYUDTpcAnMk0/ijF+uq9pKvZfCGyLMb6/t2g6GLr6mM/3RVMz+fxa4FxgMKmVzc+B
b5KM01WkuberyXzeKE3N5POGaCr2PyQ+73XPIIQwArie1LZC+AKJuPOBnwF/nb//OvDBGOM5wCkh
hGFYH6TzgM+RBqUpNIUQTgVeF2M8l/RQLg8hHNNEmuYDV8cYXwf8EXhH3u8fgPOB1wEfDyGM6WOa
hgPXkMbqlcCFIYTpfUjTpcX+FwFTin17nKaDoOsd+fu+5POunl8z+fy1wEsyn/wZ8C/AVcCXY4yv
AX4PvL/JfN4oTc3k84ZoKvY/ZD5vRphoO+lmVhXfrQXG589jgWcz842MMf4aIMb4zhjjdhrrg9Qr
NAEbgaEhhCOB4SRr4Pkm0jSVZA0A3A28Hng58EiMcUsenwdIE7ivaLo4xrgNOC3G+Hz+fh1wVF/S
BJCf21zgs8W+vUFTw3QdBnze1Vg1k89/gq1R2gCMBF4D3Jm/uwu4iObyeSM0XdhkPm90nHqMz3td
GcQY98QYd9R9/QlgUQjhcdIDvgloA9aHEP499zP6m7xvI32QeoWmGOPTwB3AcuAPwNdijFuaSNNj
wJvy59cDx5TXzlgLHAtM6COaJuR9twKEEE4juaYP0bfjBHAl8BVgc7Fvj9N0EHRNoO/5fC+amszn
1SxUAT4AfJ+kHBXueIY6fs7oTT5vlKZm8nkjNE3Mn3uEz/sqgfwlYGaM8RSSxv8IKVbZBnycZK1c
HkJ4SRfH9hbN9TR9OIQwBbgk0zUV+FAIYXwXx/YWTX8LXBpCuJc0Pno3RIl9dYdtJk0AhBCmAjcD
l8UYd/clTSGEk4GzYoy3sf8Our05B7oaq77m867Gqul8HkKYSQpzfJTa57OvZ9XrfN4oTc3k8wPR
1JN83lfK4KUxxofy53uBM4E1wG9jjBuyRnwQOBVYQdaA0mwxxheaQNNZwNnAQzHGHTHGTSSrqmk0
xRifjjG+JcZ4IfAw0AmsJFspGZMyPSv7kCZCCMcB3yEltf43796XNL0ROD6E8FPgX4E3hRA+RfP4
aV909Smf74OmpvJ5COH1JGv2DTHGzcDmEMLQ/HPJz03j8wZoWpn3axqfN0hTj/F5XymDVTnxAokR
fxdTpntUCGFMCGEQcDrwBKkPkhJve/VB6k2agKUkpUAI4QhgBrCMA/Rm6imEEP4xhPDG/O/lpDjh
I8BZIYTRIYQW4JWkN8r1JU0AN5AqU35d7H53X9EUY7w+xnh6TsB9GPh+jPHzNGmc9kHXnX3N5/t4
fk3j8xDCaOBa4M0xxo3563uBt+XPbwN+SBP5/CBogibxeaM09SSf93o7ihDCGaRKncmkss0VwN8D
nwd2As8B748xbgohnEOqfthDutGr8oS5geS+bgfeF2Nc0USaPkNy56vArTHGLzWRpjnAl/MuS2KM
n8r7vhX4O9I4XR9j7OhLmrLb/D+kCaxQ1heBH/QVTXXHvAZ4b0wldz0+TgdLVx/z+b5oahaf/yXw
GVJZq3jlvaRS26GkvMXlMcbdTeTzhmgCTqR5fN7wOBXHHBKfe28ih8PhcPgKZIfD4XC4MnA4HA4H
rgwcDofDgSsDh8PhcODKwOFwOBy4MnA4HA4HrgwcDofDgSsDh8PhcAD/D7mNRWO8CV6bAAAAAElF
TkSuQmCC
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># It appears there are some outliers that don&#39;t make sense - a batting average cannot be above 1... investigating...</span>

<span class="n">season_batting_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="o">&gt;</span> <span class="mi">1</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[17]:</div>

<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>playerID</th>
      <th>yearID</th>
      <th>stint</th>
      <th>teamID</th>
      <th>lgID</th>
      <th>G</th>
      <th>AB</th>
      <th>R</th>
      <th>H</th>
      <th>2B</th>
      <th>...</th>
      <th>CS</th>
      <th>BB</th>
      <th>SO</th>
      <th>IBB</th>
      <th>HBP</th>
      <th>SH</th>
      <th>SF</th>
      <th>GIDP</th>
      <th>TOTAL_HITS</th>
      <th>BATTING_AVERAGE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4782</th>
      <td>lynchja01</td>
      <td>1890</td>
      <td>1</td>
      <td>BR4</td>
      <td>AA</td>
      <td>1</td>
      <td>4.0</td>
      <td>2.0</td>
      <td>3.0</td>
      <td>2.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>5.0</td>
      <td>1.250000</td>
    </tr>
    <tr>
      <th>5880</th>
      <td>gumbebi01</td>
      <td>1893</td>
      <td>1</td>
      <td>LS3</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>5964</th>
      <td>oconnfr01</td>
      <td>1893</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>3</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>7675</th>
      <td>gastowe01</td>
      <td>1899</td>
      <td>1</td>
      <td>BRO</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>8697</th>
      <td>hopkimi01</td>
      <td>1902</td>
      <td>1</td>
      <td>PIT</td>
      <td>NL</td>
      <td>1</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>10393</th>
      <td>knollhu01</td>
      <td>1906</td>
      <td>1</td>
      <td>BRO</td>
      <td>NL</td>
      <td>2</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>11215</th>
      <td>gehrihe01</td>
      <td>1908</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>5</td>
      <td>5.0</td>
      <td>2.0</td>
      <td>3.0</td>
      <td>3.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>6.0</td>
      <td>1.200000</td>
    </tr>
    <tr>
      <th>13027</th>
      <td>phillde01</td>
      <td>1911</td>
      <td>1</td>
      <td>PIT</td>
      <td>NL</td>
      <td>3</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>13450</th>
      <td>irvined01</td>
      <td>1912</td>
      <td>1</td>
      <td>DET</td>
      <td>AL</td>
      <td>1</td>
      <td>3.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>4.0</td>
      <td>1.333333</td>
    </tr>
    <tr>
      <th>13830</th>
      <td>baskeji01</td>
      <td>1913</td>
      <td>1</td>
      <td>CLE</td>
      <td>AL</td>
      <td>2</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>14032</th>
      <td>griffcl01</td>
      <td>1913</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>14516</th>
      <td>bronkhe01</td>
      <td>1914</td>
      <td>1</td>
      <td>CHN</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>14550</th>
      <td>channle01</td>
      <td>1914</td>
      <td>1</td>
      <td>NYA</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>14714</th>
      <td>griffcl01</td>
      <td>1914</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>18101</th>
      <td>weinele01</td>
      <td>1919</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>1</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>18232</th>
      <td>devinha01</td>
      <td>1920</td>
      <td>1</td>
      <td>BOS</td>
      <td>AL</td>
      <td>1</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>18622</th>
      <td>wattal01</td>
      <td>1920</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>19247</th>
      <td>cotteho01</td>
      <td>1922</td>
      <td>1</td>
      <td>CHN</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>19288</th>
      <td>eubanue01</td>
      <td>1922</td>
      <td>1</td>
      <td>CHN</td>
      <td>NL</td>
      <td>2</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>19433</th>
      <td>lutzre01</td>
      <td>1922</td>
      <td>1</td>
      <td>CIN</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>20219</th>
      <td>altroni01</td>
      <td>1924</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>21102</th>
      <td>meyerbe01</td>
      <td>1925</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>22903</th>
      <td>windlbi01</td>
      <td>1928</td>
      <td>1</td>
      <td>PIT</td>
      <td>NL</td>
      <td>1</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>24914</th>
      <td>sherdbi01</td>
      <td>1932</td>
      <td>2</td>
      <td>SLN</td>
      <td>NL</td>
      <td>3</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>25718</th>
      <td>holleed01</td>
      <td>1934</td>
      <td>2</td>
      <td>PIT</td>
      <td>NL</td>
      <td>5</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>2.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>4.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>27861</th>
      <td>lefebbi01</td>
      <td>1938</td>
      <td>1</td>
      <td>BOS</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>27868</th>
      <td>livinmi01</td>
      <td>1938</td>
      <td>1</td>
      <td>WS1</td>
      <td>AL</td>
      <td>2</td>
      <td>4.0</td>
      <td>0.0</td>
      <td>3.0</td>
      <td>2.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>5.0</td>
      <td>1.250000</td>
    </tr>
    <tr>
      <th>28029</th>
      <td>suchech01</td>
      <td>1938</td>
      <td>1</td>
      <td>CLE</td>
      <td>AL</td>
      <td>1</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>28054</th>
      <td>vancejo01</td>
      <td>1938</td>
      <td>1</td>
      <td>NYA</td>
      <td>AL</td>
      <td>4</td>
      <td>4.0</td>
      <td>1.0</td>
      <td>3.0</td>
      <td>2.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>NaN</td>
      <td>5.0</td>
      <td>1.250000</td>
    </tr>
    <tr>
      <th>28167</th>
      <td>burkael01</td>
      <td>1939</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>5</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>NaN</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>73083</th>
      <td>charlno01</td>
      <td>1995</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>25</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>73389</th>
      <td>hickebr01</td>
      <td>1995</td>
      <td>2</td>
      <td>COL</td>
      <td>NL</td>
      <td>18</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>76579</th>
      <td>wettejo01</td>
      <td>1997</td>
      <td>1</td>
      <td>TEX</td>
      <td>AL</td>
      <td>61</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>76812</th>
      <td>candito01</td>
      <td>1998</td>
      <td>1</td>
      <td>OAK</td>
      <td>AL</td>
      <td>33</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>77745</th>
      <td>spradje01</td>
      <td>1998</td>
      <td>1</td>
      <td>PHI</td>
      <td>NL</td>
      <td>69</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>78761</th>
      <td>motagu01</td>
      <td>1999</td>
      <td>1</td>
      <td>MON</td>
      <td>NL</td>
      <td>51</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>79439</th>
      <td>cammaer01</td>
      <td>2000</td>
      <td>1</td>
      <td>NYN</td>
      <td>NL</td>
      <td>8</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>79927</th>
      <td>leshebr01</td>
      <td>2000</td>
      <td>1</td>
      <td>SEA</td>
      <td>AL</td>
      <td>5</td>
      <td>5.0</td>
      <td>1.0</td>
      <td>4.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>6.0</td>
      <td>1.200000</td>
    </tr>
    <tr>
      <th>79992</th>
      <td>mantoje01</td>
      <td>2000</td>
      <td>1</td>
      <td>COL</td>
      <td>NL</td>
      <td>7</td>
      <td>5.0</td>
      <td>2.0</td>
      <td>4.0</td>
      <td>2.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>7.0</td>
      <td>1.400000</td>
    </tr>
    <tr>
      <th>80616</th>
      <td>yanes01</td>
      <td>2000</td>
      <td>1</td>
      <td>TBA</td>
      <td>AL</td>
      <td>43</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>81445</th>
      <td>mooretr01</td>
      <td>2001</td>
      <td>1</td>
      <td>ATL</td>
      <td>NL</td>
      <td>2</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>82628</th>
      <td>lidgebr01</td>
      <td>2002</td>
      <td>1</td>
      <td>HOU</td>
      <td>NL</td>
      <td>6</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>84465</th>
      <td>tamje01</td>
      <td>2003</td>
      <td>1</td>
      <td>TOR</td>
      <td>AL</td>
      <td>44</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>84512</th>
      <td>valvejo01</td>
      <td>2003</td>
      <td>1</td>
      <td>ARI</td>
      <td>NL</td>
      <td>54</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>84895</th>
      <td>cottsne01</td>
      <td>2004</td>
      <td>1</td>
      <td>CHA</td>
      <td>AL</td>
      <td>56</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>85117</th>
      <td>gonzami02</td>
      <td>2004</td>
      <td>1</td>
      <td>PIT</td>
      <td>NL</td>
      <td>47</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>87021</th>
      <td>rogered01</td>
      <td>2005</td>
      <td>1</td>
      <td>BAL</td>
      <td>AL</td>
      <td>8</td>
      <td>1.0</td>
      <td>4.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>87969</th>
      <td>kimsu01</td>
      <td>2006</td>
      <td>1</td>
      <td>COL</td>
      <td>NL</td>
      <td>6</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>88180</th>
      <td>muntesc01</td>
      <td>2006</td>
      <td>1</td>
      <td>SFN</td>
      <td>NL</td>
      <td>27</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>88738</th>
      <td>balenwl01</td>
      <td>2007</td>
      <td>1</td>
      <td>SEA</td>
      <td>AL</td>
      <td>3</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>2.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>4.0</td>
      <td>1.333333</td>
    </tr>
    <tr>
      <th>89201</th>
      <td>hammeja01</td>
      <td>2007</td>
      <td>1</td>
      <td>TBA</td>
      <td>AL</td>
      <td>24</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>89299</th>
      <td>jimerch01</td>
      <td>2007</td>
      <td>1</td>
      <td>SEA</td>
      <td>AL</td>
      <td>11</td>
      <td>2.0</td>
      <td>5.0</td>
      <td>2.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>3.0</td>
      <td>1.500000</td>
    </tr>
    <tr>
      <th>89551</th>
      <td>moraljo02</td>
      <td>2007</td>
      <td>1</td>
      <td>MIN</td>
      <td>AL</td>
      <td>1</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>3.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>4.0</td>
      <td>1.333333</td>
    </tr>
    <tr>
      <th>89662</th>
      <td>peraljo01</td>
      <td>2007</td>
      <td>1</td>
      <td>KCA</td>
      <td>AL</td>
      <td>62</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>90631</th>
      <td>hernafe02</td>
      <td>2008</td>
      <td>1</td>
      <td>SEA</td>
      <td>AL</td>
      <td>31</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>93073</th>
      <td>chacigu01</td>
      <td>2010</td>
      <td>1</td>
      <td>HOU</td>
      <td>NL</td>
      <td>44</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>94955</th>
      <td>lyonbr01</td>
      <td>2011</td>
      <td>1</td>
      <td>HOU</td>
      <td>NL</td>
      <td>15</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>98722</th>
      <td>dedunsa01</td>
      <td>2014</td>
      <td>2</td>
      <td>HOU</td>
      <td>AL</td>
      <td>5</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>100908</th>
      <td>pindebr01</td>
      <td>2015</td>
      <td>1</td>
      <td>NYA</td>
      <td>AL</td>
      <td>25</td>
      <td>1.0</td>
      <td>0.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>101213</th>
      <td>tsaoch01</td>
      <td>2015</td>
      <td>1</td>
      <td>LAN</td>
      <td>NL</td>
      <td>5</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>1.0</td>
      <td>...</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>0.0</td>
      <td>2.0</td>
      <td>2.000000</td>
    </tr>
  </tbody>
</table>
<p>98 rows × 24 columns</p>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now that I know it is 98 records, do I really care?  I'm going to check what impact it has to the overall set of data.  I will print off the mean of all batting averages, then the mean of the batting averages at or below 1.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[30]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Print off batting averages</span>
<span class="k">print</span> <span class="s2">&quot;Batting Average of all batter entries&quot;</span> 
<span class="k">print</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="c1">#Print off batting average after &quot;removing&quot; the rows where a batter had a batting average greater than 1.</span>
<span class="k">print</span> <span class="s2">&quot;Batting Average after removing the rows where a batter had a batting average greater than 1&quot;</span> 
<span class="k">print</span> <span class="n">season_batting_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">1</span><span class="p">][</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="k">print</span> <span class="s2">&quot;Batting Average difference between batters with a valid batting average and batters without a valid batting average&quot;</span>
<span class="k">print</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span> <span class="o">-</span> <span class="n">season_batting_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">1</span><span class="p">][</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="c1">#Printing off standard deviation for all &quot;normal&quot; batters</span>
<span class="k">print</span> <span class="n">season_batting_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span> <span class="o">&lt;=</span> <span class="mi">1</span><span class="p">][</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">ddof</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt"></div>
<div class="output_subarea output_stream output_stdout output_text">
<pre>Batting Average of all batter entries
0.260304319586
Batting Average after removing the rows where a batter had a batting average greater than 1
0.258511905514
Batting Average difference between batters with a valid batting average and batters without a valid batting average
0.00179241407159
0.148956951644
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>While the batting average changes by ~.002, the standard deviation for the "normal" set is .148, and .002 falls well within.  I am going to say the 98 records do not have a signficant impact..... carrying on.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>What is the trend of batting average for each player</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[70]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">season_batting_average_df</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[[</span><span class="s1">&#39;playerID&#39;</span><span class="p">,</span><span class="s1">&#39;yearID&#39;</span><span class="p">,</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]]</span>
</pre></div>

</div>
</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Picking a couple random playerID out of the list to do a check on.<br>
I could plot all of the players, but that was getting very challenging to interpret in a single graph.
I found with the players I picked it does have an impact... though this is not a valid statistical model, to demonstrate plotting I will call it good :)</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[191]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Graphing some random samples</span>
<span class="n">season_batting_average_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_average_df</span><span class="p">[</span><span class="s1">&#39;playerID&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;aaronha01&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="s1">&#39;yearID&#39;</span><span class="p">,</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">)</span>

<span class="n">season_batting_average_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_average_df</span><span class="p">[</span><span class="s1">&#39;playerID&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;manushe01&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="s1">&#39;yearID&#39;</span><span class="p">,</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">)</span>

<span class="n">season_batting_average_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_average_df</span><span class="p">[</span><span class="s1">&#39;playerID&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;hayesfr01&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="s1">&#39;yearID&#39;</span><span class="p">,</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">)</span>

<span class="n">season_batting_average_df</span><span class="o">.</span><span class="n">loc</span><span class="p">[</span><span class="n">season_batting_average_df</span><span class="p">[</span><span class="s1">&#39;playerID&#39;</span><span class="p">]</span> <span class="o">==</span> <span class="s1">&#39;lavagco01&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="s1">&#39;yearID&#39;</span><span class="p">,</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[191]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7f481c1d7f90&gt;</pre>
</div>

</div>

<div class="output_area"><div class="prompt"></div>


<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

<div class="output_area"><div class="prompt"></div>


<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

<div class="output_area"><div class="prompt"></div>


<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

<div class="output_area"><div class="prompt"></div>


<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
gg==
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Is there a correlation between</p>

<pre><code>* H to Batting Average
* 2B to Batting Average
* 3B to Batting Average
* HR to Batting Average</code></pre>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[186]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1">#Defining a correlation function using same one from the lessons</span>

<span class="k">def</span> <span class="nf">correlation</span><span class="p">(</span><span class="n">x</span><span class="p">,</span> <span class="n">y</span><span class="p">):</span>
    <span class="n">standard_x</span> <span class="o">=</span> <span class="p">((</span><span class="n">x</span><span class="o">-</span><span class="n">x</span><span class="o">.</span><span class="n">mean</span><span class="p">()))</span> <span class="o">/</span> <span class="n">x</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">ddof</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
    <span class="n">standard_y</span> <span class="o">=</span> <span class="p">((</span><span class="n">y</span><span class="o">-</span><span class="n">y</span><span class="o">.</span><span class="n">mean</span><span class="p">()))</span> <span class="o">/</span> <span class="n">y</span><span class="o">.</span><span class="n">std</span><span class="p">(</span><span class="n">ddof</span><span class="o">=</span><span class="mi">0</span><span class="p">)</span>
    
    <span class="k">return</span> <span class="p">(</span><span class="n">standard_x</span> <span class="o">*</span> <span class="n">standard_y</span><span class="p">)</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>

<span class="c1">#Gathering required fields to do the correlation review</span>
<span class="n">hits</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;H&#39;</span><span class="p">]</span>
<span class="n">doubles</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;2B&#39;</span><span class="p">]</span>
<span class="n">triples</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;3B&#39;</span><span class="p">]</span>
<span class="n">home_runs</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;HR&#39;</span><span class="p">]</span>
<span class="n">batting_average</span> <span class="o">=</span> <span class="n">season_batting_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE&#39;</span><span class="p">]</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[186]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.35304917956480913</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[187]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># Run correlation function for H to Batting Average</span>
<span class="n">correlation</span><span class="p">(</span><span class="n">hits</span><span class="p">,</span> <span class="n">batting_average</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[187]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.45115600827229935</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[188]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># Run correlation function for 2B to Batting Average</span>
<span class="n">correlation</span><span class="p">(</span><span class="n">doubles</span><span class="p">,</span> <span class="n">batting_average</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[188]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.4547350357714893</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[189]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># Run correlation function for 3B to Batting Average</span>
<span class="n">correlation</span><span class="p">(</span><span class="n">triples</span><span class="p">,</span> <span class="n">batting_average</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[189]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.3357264206386593</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[190]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="c1"># Run correlation function for HR to Batting Average</span>
<span class="n">correlation</span><span class="p">(</span><span class="n">home_runs</span><span class="p">,</span> <span class="n">batting_average</span><span class="p">)</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[190]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.35304917956480913</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Now I am going to compare for players who have made it to the post season, if there batting average is better or worse in the post season.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[198]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="sd">&#39;&#39;&#39;Merging the two dataframes together - I am doing an inner merge as </span>
<span class="sd">for this data as I want to evaluate players who made it to the post season</span>
<span class="sd">&#39;&#39;&#39;</span>
<span class="n">combined_player_df</span> <span class="o">=</span> <span class="n">season_batting_average_df</span><span class="o">.</span><span class="n">merge</span><span class="p">(</span><span class="n">post_season_batting_df</span><span class="p">,</span><span class="n">how</span><span class="o">=</span><span class="s1">&#39;inner&#39;</span><span class="p">,</span> <span class="n">on</span><span class="o">=</span><span class="p">[</span><span class="s1">&#39;playerID&#39;</span><span class="p">,</span><span class="s1">&#39;yearID&#39;</span><span class="p">])</span>

<span class="n">combined_player_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE_DIFF&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="n">combined_player_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE_x&#39;</span><span class="p">]</span> <span class="o">-</span> <span class="n">combined_player_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE_y&#39;</span><span class="p">]</span>

<span class="n">combined_player_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE_DIFF&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[198]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.050550728507725455</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[199]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython2"><pre><span></span><span class="n">combined_player_df</span><span class="p">[</span><span class="s1">&#39;BATTING_AVERAGE_DIFF&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">std</span><span class="p">()</span>
</pre></div>

</div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area"><div class="prompt output_prompt">Out[199]:</div>


<div class="output_text output_subarea output_execute_result">
<pre>0.26491535507142844</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The information above tells me two things:</p>

<pre><code>1. Players in the post season on average bat ~.051 worse in the post season than in the regular season
2. Even though they bat worse, the standard deviation is only .26, so there is not a significant difference</code></pre>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1 id="Report">Report<a class="anchor-link" href="#Report">&#182;</a></h1>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered">
<div class="prompt input_prompt">
</div>
<div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Baseball Data</p>
<p>I used the baseball data (specifically Batting.csv and BattingPost.csv) and had the following questions:</p>

<pre><code>1. What was the batting average of each player during the regular playing season?
2. Over time, has batter's averages gone up, down, or stayed the same during the regular playing season?
3. Is there a correlation between the number of singles (H), doubles (2B), triples (3B), or home runs (HR) to batting averages?
4. Is there a correlation between the number of singles (H), doubles (2B), triples (3B), or home runs (HR) to batting averages?
5. Do players who make it to the post season perform the same, better, worse in the post season?

</code></pre>
<p>While all of the metrics were somewhat interesting, the one I was most curious about was "Do players who make it to the post season perform same, better, or worse in the post season?".  As players progress throughout the year and into the post season, it would seem to be that although there is some excitement/adrenaline in playing the post season, I had suspected that during the post season players would perform worse, but not significantly worse.</p>
<p>These results are tentative and to really determine the answer to that question, I would need to do more analysis (for example: Did the pitchers perform better or worse, weather conditions, stadium conditions, did they play home vs. away, etc), here is what I came away with.</p>
<p>Players who make it to the post season on average bat .051 worse than they do during the regular season, though the standard deviation is not significant enough (.265) to really say that players perform signficantly worse in the post season.</p>

</div>
</div>
</div>
    </div>
  </div>
</body>
</html>

