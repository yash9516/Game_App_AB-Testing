<!DOCTYPE html>
<html>
<head><meta charset="utf-8" />

<title>A_BTest</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
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
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
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
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
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
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
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
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
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
.fa-facebook-f:before,
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
.fa-feed:before,
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
.fa-gittip:before,
.fa-gratipay:before {
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
.fa-pied-piper-pp:before {
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
.fa-resistance:before,
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
.fa-y-combinator-square:before,
.fa-yc-square:before,
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
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
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
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
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
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
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
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
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
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
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
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
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
.modal-header {
  cursor: move;
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
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
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
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
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
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
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
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
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
  vertical-align: text-bottom;
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
[dir="rtl"] .list_item > div input {
  margin-right: 0;
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
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
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
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
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
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
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
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
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
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
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
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
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
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
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
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
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
.move-button {
  display: none;
}
.download-button {
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
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
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
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
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
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
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
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
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
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
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
  min-width: 0;
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
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
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
div.output_area .mglyph > img {
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
  padding: 1px 0 1px 0;
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
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
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
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
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
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
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
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
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
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
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
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
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
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
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
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
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
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
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
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
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
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
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
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
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
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
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
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
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
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
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
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
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
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
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
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
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
  width: 21ex;
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
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
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
.toolbar-btn-label {
  margin-left: 6px;
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
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
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
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
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
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
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
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
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
  width: 100%;
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
.terminal-app .terminal .xterm-rows {
  padding: 10px;
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
    pre { line-height: 125%; margin: 0; }
td.linenos pre { color: #000000; background-color: #f0f0f0; padding: 0 5px 0 5px; }
span.linenos { color: #000000; background-color: #f0f0f0; padding: 0 5px 0 5px; }
td.linenos pre.special { color: #000000; background-color: #ffffc0; padding: 0 5px 0 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding: 0 5px 0 5px; }
.highlight .hll { background-color: #ffffcc }
.highlight { background: #f8f8f8; }
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
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
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
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
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
}@media print {
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
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
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

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[5]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">os</span>
<span class="nb">print</span><span class="p">(</span><span class="n">os</span><span class="o">.</span><span class="n">environ</span><span class="p">[</span><span class="s1">&#39;PATH&#39;</span><span class="p">])</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>C:\ProgramData\Anaconda3;C:\ProgramData\Anaconda3\Library\mingw-w64\bin;C:\ProgramData\Anaconda3\Library\usr\bin;C:\ProgramData\Anaconda3\Library\bin;C:\ProgramData\Anaconda3\Scripts;C:\ProgramData\Anaconda3\bin;C:\ProgramData\Anaconda3\condabin;C:\Program Files (x86)\Common Files\Oracle\Java\javapath;C:\Windows\System32;C:\Windows;C:\Windows\System32\wbem;C:\Windows\System32\WindowsPowerShell\v1.0;C:\Windows\System32\OpenSSH;C:\Program Files\Java\jdk-12.0.2\bin;C:\Program Files\Java\JavaFX\javafx-sdk-13.0.1\lib;C:\Program Files\Java\JavaFX\javafx-sdk-13.0.1\bin;C:\Program Files\Git LFS;C:\Program Files\Git\cmd;C:\PROGRA~1\Java\JDK18~1.0_2;C:\spark\spark-2.4.5-bin-hadoop2.7\bin;C:\PROGRA~2\sbt\bin;C:\Program Files\Pandoc;C:\Program Files (x86)\Microsoft SQL Server\150\DTS\Binn;C:\Program Files\Azure Data Studio\bin;C:\Program Files\Microsoft SQL Server\Client SDK\ODBC\170\Tools\Binn;C:\Program Files (x86)\Microsoft SQL Server\150\Tools\Binn;C:\Program Files\Microsoft SQL Server\150\Tools\Binn;C:\Program Files\Microsoft SQL Server\150\DTS\Binn;C:\Users\Yash\AppData\Local\Programs\Python\Python37\Scripts;C:\Users\Yash\AppData\Local\Programs\Python\Python37;C:\Program Files\MySQL\MySQL Shell 8.0\bin;C:\Users\Yash\AppData\Local\GitHubDesktop\bin;C:\spark\spark-2.4.5-bin-hadoop2.7\bin;C:\Progra~1\Java\jdk1.8.0_231;C:\winutils;C:\Progra~2\sbt\bin;C:\ProgramData\Anaconda3\python.exe;C:\Users\Yash\AppData\Local\Programs\Microsoft VS Code\bin;C:\Program Files\Docker Toolbox;C:\Users\Yash\AppData\Local\Microsoft\WindowsApps;C:\Program Files\Java\jdk1.8.0_231\bin;.;C:\Program Files\Azure Data Studio\bin
</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="o">!</span>pip install latex
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Requirement already satisfied: latex in c:\programdata\anaconda3\lib\site-packages (0.7.0)
Requirement already satisfied: tempdir in c:\programdata\anaconda3\lib\site-packages (from latex) (0.7.1)
Requirement already satisfied: future in c:\programdata\anaconda3\lib\site-packages (from latex) (0.18.2)
Requirement already satisfied: shutilwhich in c:\programdata\anaconda3\lib\site-packages (from latex) (1.1.0)
Requirement already satisfied: data in c:\programdata\anaconda3\lib\site-packages (from latex) (0.4)
Requirement already satisfied: six in c:\programdata\anaconda3\lib\site-packages (from data-&gt;latex) (1.15.0)
Requirement already satisfied: decorator in c:\programdata\anaconda3\lib\site-packages (from data-&gt;latex) (4.4.2)
Requirement already satisfied: funcsigs in c:\programdata\anaconda3\lib\site-packages (from data-&gt;latex) (1.0.2)
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[4]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">import</span> <span class="nn">sys</span>
<span class="k">if</span> <span class="s2">&quot;c:\programdata</span><span class="se">\a</span><span class="s2">naconda3\lib\site-packages\latex&quot;</span> <span class="ow">not</span> <span class="ow">in</span> <span class="n">sys</span><span class="o">.</span><span class="n">path</span><span class="p">:</span>
    <span class="nb">print</span><span class="p">(</span><span class="s1">&#39;adding path&#39;</span><span class="p">)</span> <span class="c1"># I just add this to know if the path was present or not.</span>
    <span class="n">sys</span><span class="o">.</span><span class="n">path</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="s2">&quot;c:\programdata</span><span class="se">\a</span><span class="s2">naconda3\lib\site-packages\latex&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[1]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="o">!</span><span class="nb">export</span> <span class="nv">PATH</span><span class="o">=</span>/Library/TeX/texbin:<span class="nv">$PATH</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stderr output_text">
<pre>&#39;export&#39; is not recognized as an internal or external command,
operable program or batch file.
</pre>
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
<div class=" highlight hl-ipython3"><pre><span></span><span class="kn">from</span> <span class="nn">google.colab</span> <span class="kn">import</span> <span class="n">drive</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[3]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">drive</span><span class="o">.</span><span class="n">mount</span><span class="p">(</span><span class="s2">&quot;/content/drive&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Mounted at /content/drive
</pre>
</div>
</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[27]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">#Python Imports</span>
<span class="kn">import</span> <span class="nn">re</span>
<span class="kn">import</span> <span class="nn">string</span>
<span class="kn">from</span> <span class="nn">collections</span> <span class="kn">import</span> <span class="n">Counter</span>


<span class="c1">#Pandas</span>
<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="n">pd</span><span class="o">.</span><span class="n">set_option</span><span class="p">(</span><span class="s1">&#39;display.max_rows&#39;</span><span class="p">,</span> <span class="mi">500</span><span class="p">)</span>
<span class="n">pd</span><span class="o">.</span><span class="n">set_option</span><span class="p">(</span><span class="s1">&#39;display.max_columns&#39;</span><span class="p">,</span><span class="mi">120</span><span class="p">)</span>

<span class="c1">#Numpy</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>


<span class="c1">#Visualization</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span> 
<span class="kn">import</span> <span class="nn">seaborn</span> <span class="k">as</span> <span class="nn">sns</span>
<span class="kn">import</span> <span class="nn">plotly.express</span> <span class="k">as</span> <span class="nn">px</span>
<span class="kn">import</span> <span class="nn">plotly.graph_objects</span> <span class="k">as</span> <span class="nn">px</span> 
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[13]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;/content/drive/My Drive/DS/ABTest/cookie_cats.csv&quot;</span><span class="p">,</span><span class="n">low_memory</span><span class="o">=</span><span class="kc">False</span><span class="p">)</span>
                 
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[14]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">shape</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[14]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>(90189, 5)</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[15]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[15]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>userid</th>
      <th>version</th>
      <th>sum_gamerounds</th>
      <th>retention_1</th>
      <th>retention_7</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>116</td>
      <td>gate_30</td>
      <td>3</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>337</td>
      <td>gate_30</td>
      <td>38</td>
      <td>True</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>377</td>
      <td>gate_40</td>
      <td>165</td>
      <td>True</td>
      <td>False</td>
    </tr>
    <tr>
      <th>3</th>
      <td>483</td>
      <td>gate_40</td>
      <td>1</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>488</td>
      <td>gate_40</td>
      <td>179</td>
      <td>True</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[16]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">isna</span><span class="p">()</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[16]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>userid            0
version           0
sum_gamerounds    0
retention_1       0
retention_7       0
dtype: int64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h1>The data is from <strong>90,189</strong> players that installed the game while the AB-test was running. <br></h1>
<p>The variables are:</p>
<ul>
<li><strong>userid</strong> - a unique number that identifies each player.</li>
<li><strong>version</strong> - whether the player was put in the control group (gate_30 - a gate at level 30) or the test group (gate_40 - a gate at level 40).</li>
<li><strong>sum_gamerounds</strong> - the number of game rounds played by the player during the * first week after installation</li>
<li><strong>retention_1</strong> - did the player come back and play 1 day after installing?</li>
<li><strong>retention_7</strong> - did the player come back and play 7 days after installing?
When a player installed the game, he or she was randomly assigned to either gate_30 or gate_40.</li>
</ul>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Count distribution across Both groups</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[17]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;version&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">value_counts</span><span class="p">(</span><span class="n">normalize</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[17]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>gate_40    0.504374
gate_30    0.495626
Name: version, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>We see, the proportion of Control group and Test group is almost same</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>How many players of Gate_40 are retained for 1 day</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[26]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">count_by_gamerounds</span> <span class="o">=</span> <span class="n">df</span><span class="p">[[</span><span class="s1">&#39;userid&#39;</span><span class="p">,</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">]]</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="n">by</span><span class="o">=</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">)</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
<span class="n">count_by_gamerounds</span><span class="o">.</span><span class="n">columns</span> <span class="o">=</span> <span class="p">[</span><span class="s1">&#39;Number_of_Players&#39;</span><span class="p">]</span>
<span class="n">count_by_gamerounds</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[26]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Number_of_Players</th>
    </tr>
    <tr>
      <th>sum_gamerounds</th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>3994</td>
    </tr>
    <tr>
      <th>1</th>
      <td>5538</td>
    </tr>
    <tr>
      <th>2</th>
      <td>4606</td>
    </tr>
    <tr>
      <th>3</th>
      <td>3958</td>
    </tr>
    <tr>
      <th>4</th>
      <td>3629</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">ax</span> <span class="o">=</span> <span class="n">count_by_gamerounds</span><span class="o">.</span><span class="n">head</span><span class="p">(</span><span class="mi">100</span><span class="p">)</span><span class="o">.</span><span class="n">plot</span><span class="p">()</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_xlabel</span><span class="p">(</span><span class="s2">&quot;number of games played&quot;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_ylabel</span><span class="p">(</span><span class="s2">&quot;number of users&quot;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>Text(0, 0.5, &#39;number of users&#39;)</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The distribution is highly skewed, with a long tail on the right. A huge number of players played fewer than 20 rounds and left the game. For rounds greater than 60, the number of players stayed steady at about 300.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[36]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># df[&#39;sum_gamerounds&#39;].plot.box(figsize=(5,10))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">boxplot</span><span class="p">(</span><span class="n">y</span><span class="o">=</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[36]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7ff467973ef0&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Removing outlier row where sum_gamerounds is around 50000</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[30]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">drop</span><span class="p">(</span><span class="n">df</span><span class="p">[</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">]</span><span class="o">&gt;=</span><span class="mi">40000</span><span class="p">]</span><span class="o">.</span><span class="n">index</span><span class="p">,</span> <span class="n">inplace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[38]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># df[&#39;sum_gamerounds&#39;].plot.box(figsize=(5,10))</span>
<span class="n">sns</span><span class="o">.</span><span class="n">boxplot</span><span class="p">(</span><span class="n">y</span><span class="o">=</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">values</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[38]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7ff4673c9940&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;sum_gamerounds&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">describe</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>count    90188.000000
mean        51.320253
std        102.682719
min          0.000000
25%          5.000000
50%         16.000000
75%         51.000000
max       2961.000000
Name: sum_gamerounds, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>As we can see, 50% of players played fewer than 16 game rounds during the first week after installation, and 75% of players played fewer than 51 rounds.</p>
<p>Nearly 4000 players did not even play a single round after installation. Possible reasons may include:</p>
<p>They downloaded a number of new games at the same time and were attracted by other games.
They opened the app but did not like the design/interface/music, so they quit even before playing the game.
They have not started playing the game yet.
<br> 
<br></p>
<p>Another number worth attention is that more than 14,000 players played fewer than three rounds. For these players, the reasons for leaving may include:</p>
<p>They did not enjoy the game. (This is probably the most common reason).
The game turned out to be different from what they expected.
The game was too easy and they got bored of it.
<br>
<br></p>
<p>It is important to understand why a large number of players quit the game at an early stage. Tactile Entertainment can try to collect player feedback, for example, through an in-app survey.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;retention_1&#39;</span><span class="p">]</span><span class="o">==</span><span class="kc">True</span><span class="p">]</span><span class="o">.</span><span class="n">count</span><span class="p">()</span><span class="o">*</span><span class="mi">100</span><span class="o">/</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;retention_1&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>userid            44.521444
version           44.521444
sum_gamerounds    44.521444
retention_1       44.521444
retention_7       44.521444
dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="p">[</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">==</span><span class="kc">True</span><span class="p">]</span><span class="o">.</span><span class="n">count</span><span class="p">()</span><span class="o">*</span><span class="mi">100</span><span class="o">/</span><span class="n">df</span><span class="p">[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>userid            18.605579
version           18.605579
sum_gamerounds    18.605579
retention_1       18.605579
retention_7       18.605579
dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Comparing-1--Day-Retention-for-each-A-B-group">Comparing 1- Day Retention for each A-B group<a class="anchor-link" href="#Comparing-1--Day-Retention-for-each-A-B-group">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_1&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>version
gate_30    0.448198
gate_40    0.442283
Name: retention_1, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Comparing-7-Day-Retention-for-each-A-B-group">Comparing 7 Day Retention for each A-B group<a class="anchor-link" href="#Comparing-7-Day-Retention-for-each-A-B-group">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>version
gate_30    0.190183
gate_40    0.182000
Name: retention_7, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>It appears that there was a slight decrease in 1-day retention when the gate was moved to level 40 (44.2%) compared to the control when it was at level 30 (44.8%). It's a small change, but even small changes in retention can have a large impact. But while we are certain of the difference in the data, how certain should we be that a gate at level 40 will be worse in the future?</p>
<p>There are a couple of ways we can get at the certainty of these retention numbers. Here we will use bootstrapping: We will repeatedly re-sample our dataset (with replacement) and calculate 1-day retention for those samples. The variation in 1-day retention will give us an indication of how uncertain the retention numbers are.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>Bootstrapping: Should we be confident in the difference?</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Creating an list with bootstrapped means for each AB-group</span>
<span class="n">boot_1d</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">1000</span><span class="p">):</span>
    <span class="n">boot_mean</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">sample</span><span class="p">(</span><span class="n">frac</span> <span class="o">=</span> <span class="mi">1</span><span class="p">,</span><span class="n">replace</span> <span class="o">=</span> <span class="kc">True</span><span class="p">)</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_1&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="n">boot_1d</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">boot_mean</span><span class="p">)</span>
    
<span class="c1"># Transforming the list to a DataFrame</span>
<span class="n">boot_1d</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">boot_1d</span><span class="p">)</span>
    
<span class="c1"># A Kernel Density Estimate plot of the bootstrap distributions</span>
<span class="n">boot_1d</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s1">&#39;density&#39;</span><span class="p">)</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>&lt;matplotlib.axes._subplots.AxesSubplot at 0x7f0a76e478d0&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAYUAAAD4CAYAAAAD6PrjAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3deXxcdd3o8c83e7M2bZImTdImTbd0X1JadlAQUKkCIhVlUaSy6L0+XB/Ex41H8aVXfOSCIgiyCggIsskqRfYCTUu6pm2Wpk3SNGuzN2mS+d0/zkyapkkz+5lpvu/Xa15n5pwz53wzTeeb3y7GGJRSSimACLsDUEopFTo0KSillBqkSUEppdQgTQpKKaUGaVJQSik1KMruAHyRlpZm8vLy7A5DKaXCysaNG5uMMekjHQvrpJCXl0dxcbHdYSilVFgRkb2jHdPqI6WUUoM0KSillBoUsKQgIg+KSIOIbBuy7ykRKXE+qkSkxLk/T0QODTl2b6DiUkopNbpAtik8DPwReNS1wxhzmeu5iPwP0Dbk/ApjzJIAxqOUOgH09fVRU1NDT0+P3aGEvLi4OHJycoiOjnb7PQFLCsaYd0Ukb6RjIiLAV4HPBOr+SqkTU01NDUlJSeTl5WF9laiRGGNobm6mpqaG/Px8t99nV5vC6UC9MaZsyL58EflURN4RkdNHe6OIrBWRYhEpbmxsDHykSqmQ0tPTw+TJkzUhjEFEmDx5ssclKruSwteAvw15XQdMM8YsBW4CnhCR5JHeaIy5zxhTZIwpSk8fsZutUuoEpwnBPd58TkEfpyAiUcDFwHLXPmNML9DrfL5RRCqA2YAOQlAWY6BxJ1T8G2LiYcElEJtkd1RKnXDsGLx2DrDTGFPj2iEi6UCLMWZARGYAs4BKG2JToWSgHyrfht2vQdnr0LrvyLH374CrX4aUHNvCU2o0P/vZzzjjjDM455xz7A7FYwFLCiLyN+AsIE1EaoCfG2MeANZwdNURwBnAL0SkD3AA1xljWgIVmwoDW5+BN34CHXUQHQ/5Z8JpN8Gsc6GlEv52OTx3HVz1EmhVgrKBMQZjDBERx9bC/+IXv7AhIv8IWJuCMeZrxpgsY0y0MSbHmRAwxlxtjLl32LnPGmPmG2OWGGOWGWNeClRcKgys/xM8ew0kZ8Nlj8PNe+DyJ6Hom1bJIP8MOOfnUPUeVKyzO1oV5m655Rbuvvvuwde33norv/vd77j99ttZsWIFixYt4uc//zkAVVVVzJkzhyuvvJIFCxZQXV3N1VdfzYIFC1i4cCF33HEHAFdffTXPPPMMAOvWrWPp0qUsXLiQb33rW/T29gLWND0///nPWbZsGQsXLmTnzp1B/slHpiOaVWip326VEOZ+Eb71OhR+EaLjjj1v2VWQmAkf6ThH5ZvLLruMp59+evD1008/TXp6OmVlZXzyySeUlJSwceNG3n33XQDKysq44YYb2L59O01NTdTW1rJt2za2bt3KN7/5zaOu3dPTw9VXX81TTz3F1q1b6e/v55577hk8npaWxqZNm7j++uv53e9+F5wfeAyaFFRoeetXEJcMq/8Akcep3YyKgSWXQ8Vb0NUcvPjUCWfp0qU0NDSwf/9+Nm/eTGpqKlu3buWNN95g6dKlLFu2jJ07d1JWZvWgnz59OqtWrQJgxowZVFZW8r3vfY/XXnuN5OSjO03u2rWL/Px8Zs+eDcBVV101mFwALr74YgCWL19OVVVVEH7asWlSUKHjYBXsegWKroH4SWOfP/8iMAOw6+WAh6ZObJdeeinPPPMMTz31FJdddhnGGH70ox9RUlJCSUkJ5eXlXHPNNQAkJCQMvi81NZXNmzdz1llnce+99/Ltb3/bo/vGxsYCEBkZSX9/v/9+IB9oUlCh49PHrUbjFde4d37mQkjKsrqpKuWDyy67jCeffJJnnnmGSy+9lPPOO48HH3yQzs5OAGpra2loaDjmfU1NTTgcDi655BJuu+02Nm3adNTxOXPmUFVVRXl5OQB//etfOfPMMwP/A/kgrNdTUCeYnS/DtJMheap754tYjc7l66xxDCHcC6l/wMHLW+uoaurmc/OnUJg14thMZZP58+fT0dFBdnY2WVlZZGVlUVpaysknnwxAYmIijz32GJGRkUe9r7a2lm9+85s4HA4Afv3rXx91PC4ujoceeohLL72U/v5+VqxYwXXXXRecH8pLYoyxOwavFRUVGV1k5wRxsAruXAyf+xWc8l333/fp4/DCDXD9hzBlfsDC80Vr92GufbSYDVUHAYiOFO67soiz52TYHFl4Ki0tpbCw0O4wwsZIn5eIbDTGFI10vlYfqdDgqgKafZ5n75t+irWt/sS/8fhJZ28/Vz34CZtr2rjjssVs+um5zMpI4gdPb6ajp8/u8JQ6hiYFFRqqP4b4NJg807P3pebBhFTYv2nMU4PNGMMPn93C1to2/nT5Mi5amsOkhBh+ffFCmrsO8/jH+8a+iFJBpklBhYZ9H8G0VZ63C4jA1KWw/9PAxOWDhz+s4uUtdfzneXM5Z96Uwf2LcyeyIi+VpzdUE87Vt+rEpElB2a+jHg7usZKCN6Yug/od0HfIv3H5oKy+g1+/spNzCjP4zhkzjjl+aVEulU1dfFrdakN0So1Ok4KyX/XH1jbX26SwxBqv0LDDfzH5YMBh+M9ntpAQG8lvLllERMSxpZ/z5mUSIfDvncd2c1TKTpoUlP3qNoNEWuMOvJHu7FnREBpzxzy6voqS6lZuXT2ftMTYEc9JiY9m2bRU3tmtC0Wp0KJJQdmvfhukzR55jiN3pOZBZKy13oLNOnr6uGtdGafNTGP14uOPtzhrTjpbato42HU4SNEpNTZNCsp+9dt9G2MQGQVps0IiKfzlvT0c7O7j5vPnjLnq1Yo8ayqPEm1XOOE9//zz7NjhXfXmvffey8KFC1myZAmnnXbaUdf59a9/zcyZM5kzZw6vv/66X2LVpKDsdeggtFVD5gLfrpM+1/bqo87efh54fw8XLMhkUc7EMc9fmJNCZISwad/BIESn7ORLUrj88svZunUrJSUl3Hzzzdx0000A7NixgyeffJLt27fz2muvccMNNzAwMOBzrDrNhbJXvfM/yhQ/JIVtz0BvJ8Qm+h6XF57dWENnbz/fObPArfPjY6KYm5nEp/u0pOCt/35pOzv2t/v1mvOmJvPzC8cuuf7yl7/kscceIz09ndzcXJYvX05KSgr33Xcfhw8fZubMmfz1r3+lpKSEF198kXfeeYfbbruNZ599FoAbb7yRxsZG4uPjuf/++5k7d+6I9xk682pXV9dgCfSFF15gzZo1xMbGkp+fz8yZM/nkk08Gp+bwlpYUlL3qt1tbX5NChvM/VNMu367jJWMMj66vYnFOCktyxy4luCydNpGS6lYGHDpeIZxs2LCBZ599ls2bN/Pqq6/imm7n4osvZsOGDWzevJnCwkIeeOABTjnlFFavXs3tt99OSUkJBQUFrF27lj/84Q9s3LiR3/3ud9xwww3Hvd/dd99NQUEBN998M3fddRdgzbuUm5s7eE5OTg61tbU+/2xaUlD2ai6D2GRIyvTtOq6R0M2VkL3c97g8VFLdSkVjF7+9ZJFH71uSm8pjH+2jorGT2VOSAhTdicudv+gD4YMPPuBLX/oScXFxxMXFceGFFwKwbds2fvKTn9Da2kpnZyfnnXfstC2dnZ18+OGHXHrppYP7XKuxjebGG2/kxhtv5IknnuC2227jkUce8e8PNIQmBWWvlkqYlO/7DKepedb24B6fQ/LGi5v3ExMVwfkLPUtu86daVQOlde2aFE4AV199Nc8//zyLFy/m4Ycf5u233z7mHIfDwcSJEykpKfH4+mvWrOH6668HIDs7m+rq6sFjNTU1ZGdnex27S8Cqj0TkQRFpEJFtQ/bdKiK1IlLifHx+yLEfiUi5iOwSEQ9nRVNhq6USJh074tdj0RMgaap1vSAbcBj+uaWOs+ekkxwX7dF7C9ITiYoQdh3oCFB0KhBOPfVUXnrpJXp6eujs7OSf//wnAB0dHWRlZdHX18fjjz8+eH5SUhIdHda/cXJyMvn5+fz9738HrKrHzZs3j3ov14pvAC+//DKzZs0CYPXq1Tz55JP09vayZ88eysrKOOmkk3z+2QJZUngY+CPw6LD9dxhjjlqMVETmAWuA+cBU4E0RmW2M8b0pXYWugT5o3WetoOYPk2ZAS/BLCiXVB2ns6OULi9xcB2KImKgICtIT2alJIaysWLGC1atXs2jRIqZMmcLChQtJSUnhl7/8JStXriQ9PZ2VK1cOJoI1a9Zw7bXXctddd/HMM8/w+OOPc/3113PbbbfR19fHmjVrWLx48Yj3+uMf/8ibb75JdHQ0qampg1VH8+fP56tf/Srz5s0jKiqKu++++5j1HrwRsKRgjHlXRPLcPP1LwJPGmF5gj4iUAycB6wMUngoFbdXg6PdPSQFgUh7sfsM/1/LA27saiRA4c1a6V++fm5XEhj0tfo5KBdoPfvADbr31Vrq7uznjjDNYvnw5y5YtG6zeGerUU089pkvqa6+95tZ97rzzzlGP/fjHP+bHP/6xZ4GPwY7eR98VkS3O6qVU575soHrIOTXOfccQkbUiUiwixY2NOkVAWHP9Ve+3pDADuhqsbqlB9O9dDSyblkpKvGdVRy5zM5PZ39ZD2yFdXyGcrF27liVLlrBs2TIuueQSli1bZndIfhHshuZ7gF8Cxrn9H+BbnlzAGHMfcB9YK6/5O0AVRK76f38lhdR8a3twj/fzKHmooaOHbbXt/OBzs72+xtxMq4F514EOTsqf5K/QVIA98cQTfr3er371q8F2BpdLL73U7yWBsQQ1KRhj6l3PReR+4J/Ol7VA7pBTc5z71ImsZQ9Ex0PilLHPdYcrubQELym8u7sJgLN8WFpzZoY12K6isVOTwjgWiKogbwS1+khEsoa8vAhw9Ux6EVgjIrEikg/MAkJzfUXlPy2V1l/3vnZHdZmUf+S6QfJRZTOp8dHMy0oe++RRZE+cQGxUBJWNwa32UmokASspiMjfgLOANBGpAX4OnCUiS7Cqj6qA7wAYY7aLyNPADqAfuFF7Ho0DLZXWRHb+EpdiLc3Zutd/1xzDhqoWivImjbhmgrsiIoT8tAQqGrv8GJlS3glk76OvjbD7geOc/yvgV4GKR4UYx4BV9z/bz0NSUnKhtXrs8/ygob2Hvc3dfGPldJ+vVZCeyPb9bX6ISinf6NxHyh7t+2HgsP8amV0mToO2Gv9ecxQbqqzZTVf4oR1gRnoC1QcP0duvBWRlL00Kyh7+7nnkkpJjjX8wge+YtqGqhQnRkYNTVfhiRnoCAw7DvuZuP0SmQo0vU2e7PPvss4jI4OR7oOspqBNJwJJCLhzuhJ7AT0f9yZ4Wlk6bSHSk7/+NCtJdPZC0XeFE5GtS6Ojo4M4772TlypWD+3Q9BXViObjHWkIz2fcJvI6SkmNtW6utRucA6ejpY+eBdr73Gf80lOenJQBQ2aQ9kDzy6i1wYKt/r5m5EC74zZinBWs9BYCf/vSn/PCHP+T2228f3KfrKagTS0ulNbNphJ9/BSc6h7sEuF1ha20bDgPLpvsn8STFRZORFEtFg5YUwkEw11PYtGkT1dXVfOELXzhqv66noE4sLXuOjCvwpxRXUghsD6QtNVZPoUXZKX67ZkF6opYUPOXGX/SBEKz1FBwOBzfddBMPP/xwQH6OkWhSUMFnjFVSyD/D/9dOSLeqpVr3+f/aQ2ytaSN30gRSE2L8ds0Z6Qn8c0sdxpjBJRdVePH3egodHR1s27aNs846C4ADBw6wevVqXnzxxfBbT0GpUXXWQ1+3/xuZwRodnZIT8OqjLbWtLMp2f9lNd+SnJdB2qI+D3ToxXqgL1noKKSkpNDU1UVVVRVVVFatWreLFF1+kqKgoYOspaFJQwTfY8ygA1UdgtSsEsProYNdhqlsOsTDHf1VHYJUUAPZoFVLIG7qewgUXXHDMegqnnnrqUQ3Ha9as4fbbb2fp0qVUVFTw+OOP88ADD7B48WLmz5/PCy+84HEMQ9dTOP/880N/PQWlRhWo7qguKTlQ9q/AXBurkRn8254AkJ9mdUutbOxi+XSdGC/UBWs9haGGV0cFYhI9TQoq+FoqISIKUqYF5vop05xVVD0QHef3y7uSwnw/J4Wc1AlERQhVzdoDKRysXbuWHTt20NPTw1VXXaXrKSjltZZKazqKyAD9+rnGKrTXwuQCv19+S00r+WkJpEzwblGd0URHRjBtUjx7mjQphANdT0Epf2nZE7iqIxgyVqE6QEmhjRV5ganeyU9LoFJHNY/pROyhFYiqIOPFdC/a0KyCy5jAJwVXSaHN/+s0NXf2UtfWw4Js3+c7Gkl+WgJVzV04HLqo4Gji4uJobm726gtvPDHG0NzcTFycZ1WoWlJQwdXdAr1tR5bODATX1BkB6Ja684DVrXBeln/bE1zy0xPo6XNwoL2HqRMnBOQe4S4nJ4eamhp0jfaxxcXFkZOT49F7NCmo4Ap0zyOAqFhIyIB2/yeF0rp2AOZmJfn92nBkDqQ9TV2aFEYRHR1Nfn4A/6gY57T6SAVXMJICQEp2wEoKaYmxpCXG+v3aADNc3VK1sVnZRJOCCq6WSkAg1ffVyo4rOTsgbQo7D7RTGKBSAsCU5FgmREeyRxublU00Kajgaqm0Jq2LCsxf2oNScq2Sgh8bI/sHHOyu76QwKzCNzAAiQl5ago5qVrbRpKCCq6UycNNbDJWSDX1dfl1sZ09TF4f7HczNDFxJAWBGWoKOVVC2CVhSEJEHRaRBRLYN2Xe7iOwUkS0i8pyITHTuzxORQyJS4nzcG6i4lM1aKgPfngAB6ZZa6ux5NDczcCUFsBqbqw8eom/AEdD7KDWSQJYUHgbOH7bvX8ACY8wiYDfwoyHHKowxS5yP6wIYl7LLoVY41BKckkKyKyn4r7F5Z107URFCQUaC3645kvw0a73m6hZdr1kFX8CSgjHmXaBl2L43jDH9zpcfAZ51oFXhraXC2k6eGfh7DU514cekcKCDgvREYqN8n4nyePLTj3RLVSrY7GxT+Bbw6pDX+SLyqYi8IyKnj/YmEVkrIsUiUqyDV8JMszMpTPL/1BPHSMywJt3zY0mhtC6wPY9cZqRpUlD2sSUpiMiPgX7AtQpFHTDNGLMUuAl4QkRGrLg1xtxnjCkyxhSlp6cHJ2DlH80VgASn+igiEpKn+q1NobX7MHVtPcwNYM8jl4nxMaTGR+tYBWWLoCcFEbka+CLwdeOcvMQY02uMaXY+3whUALODHZsKsOZya7K6QHdHdUn23wpsu5yNzHMC3PPIJT8tQccqKFsENSmIyPnAzcBqY0z3kP3pIhLpfD4DmAVUBjM2FQQtFcGpOnJJyfZbm0J5ozVuYFZGol+uN5b8tEStPlK2CGSX1L8B64E5IlIjItcAfwSSgH8N63p6BrBFREqAZ4DrjDEtI15YhSdjoLkyOI3MLik50F4HjgGfL1Xe0MmE6EimpgRnPqIZ6QkcaO+hq7d/7JOV8qOATYhnjPnaCLsfGOXcZ4FnAxWLCgFdTdbsqAFY32BUydng6IPOBkjO8ulS5Q2dFGQkEBERnDn8XRPjVTV3MX9qYGZkVWokOqJZBUcwu6O6pDgX22n3vbG5oqGTmenBqTqCo2dLVSqYNCmo4BjsjhqE0cwuKa51Fap9ukxXbz/723ooCGJSyJvsTAra2KyCTJOCCo7mcmvcwMQAz446lJ+munAtjzkzSI3MABNiIslKidOSggo6TQoqOFoqIDUPIoO4rlPcRIhO8Llbanmj1R01mEkBnOs1a1JQQaZJQQVHU1lw2xMARPzSLbW8oZPICGH65MDOeTSca71mpYJJk4IKvIE+Kymkzw3+vVNyfK4+Km/oZPrkeGKigvvfpSA9kdbuPho7eoN6XzW+aVJQgddSaXUNzSgM/r2TfV+WszzIPY9cXKOnd9d3BP3eavzSpKACr6HU2tpSUsiFrgbo9+6v7b4BB3ubu4PengBHksLOA5oUVPBoUlCB17gTEEizYTorV7dUL8cq7G3upt9hgtod1SUtMZbJCTHs1qSggkiTggq8hlKr51FMfPDv7WO31PIGa84jO0oKALOnJLFTq49UEGlSUIHXuNOe9gQ4sgKblyWFCudEeAU2JYU5mUmU1XfgcBhb7q/GH00KKrD6D1sD1+xoTwBrTQXwelRzeUMnWSlxJMYGcXzFEHMyk+g+PEBt6yFb7q/GH00KKrBaKsDRb19JISYe4if7VH1kV9URaGOzCj5NCiqwDmyztnYlBfC6W6oxhorGTlsamV1c6zdot1QVLJoUVGDVFkN0PKTbmBRScr1qU6hr66H78ICtJYWkuGiyJ07QkoIKGk0KKrBqN0LWkuDOeTRcinclBVfPIztLCgBzM5O0W6oKGk0KKnD6D0PdFshZbm8cKTnQ2w497R69ze7uqC5zMpOoaOykp8/3FeSUGosmBRU49VthoBeyi+yNI9m7AWzljZ2kTIgmLTEmAEG5b0F2Cv0Oo+0KKig0KajAqd1kbbNDoKQAHlchuXoeiQRnCc7RzJ+aDMD2/Z6VdJTyhiYFFTg1xZA45ciXsl28TAqVjfZMhDfctEnxJMVFsa22ze5Q1DgQ0KQgIg+KSIOIbBuyb5KI/EtEypzbVOd+EZG7RKRcRLaIyLJAxqaCoLbYqjqy+S9tEjNBIjxKCq3dh2nqPGx7ewKAiDAvK1lLCiooAl1SeBg4f9i+W4B1xphZwDrna4ALgFnOx1rgngDHpgLp0EFrJHN2COT2yChImupRm8Jgz6OM4C6sM5oF2SmU1rXTP+CwOxR1ggtoUjDGvAu0DNv9JeAR5/NHgC8P2f+osXwETBSRrEDGpwLI1Z6QY3Mjs4uH3VIHex6lJwUqIo/Mn5pMb79Dl+dUAedWUhCRf4jIF0TEH0lkijGmzvn8ADDF+TwbGDpBTY1z3/BY1opIsYgUNzY2+iEcFRC1GwGBqUvtjsSSkuNxUoiNiiA7dUIAg3LfguwUALbv13YFFVjufsn/CbgcKBOR34jIHH/c3BhjAI+mfzTG3GeMKTLGFKWnp/sjDBUINcXW+glxKXZHYknOhvb94HCv+qW8sZMZ6YlERtjcHuI0Iy2B2KgIttVqu4IKLLeSgjHmTWPM14FlQBXwpoh8KCLfFJFoD+9Z76oWcm4bnPtrgdwh5+U496lwY4xVUgiVqiOwSgoDvdDd5Nbpdk+EN1xUZASFWclaUlAB53Z1kIhMBq4Gvg18CtyJlST+5eE9XwSucj6/CnhhyP4rnb2QVgFtQ6qZVDhp3Wt9+do9PmEoD7qlHnJOVR0K3VGHmj/V6oFkFbCVCgx32xSeA94D4oELjTGrjTFPGWO+B4z6P0dE/gasB+aISI2IXAP8BjhXRMqAc5yvAV4BKoFy4H7gBi9/JmW3mmJrG1JJwVkIbd075qmVTZ0YY//0FsMtyE6ho6ef6hZdW0EFjruzlN1vjHll6A4RiTXG9BpjRq0jMMZ8bZRDnx3hXAPc6GY8KpTVboKoOJgy3+5Ijpg0w9o2V4x5aqh1R3VxjWzetr+NaZNtWNpUjQvuVh/dNsK+9f4MRJ1AaoudM6N62twUQLGJ1ujqlj1jnlrR0EmEQH5aaCWF2VOSiIoQbVdQAXXckoKIZGJ1C50gIksBV1eMZKyqJKWONtAHdZthxbftjuRYkwqsleDGUNbQyfTJCcRGRQYhKPfFRUcyMyNReyCpgBqr+ug8rMblHOD3Q/Z3AP8VoJhUOKvfBv09oTGSebjJM6Bs7H4RodbzaKj5U1N4t0zH56jAOW71kTHmEWPM2cDVxpizhzxWG2P+EaQYVTip3Wht7Z4ueySTCqCzHnpHn4K6b8DBnqaukE0K86Ym09jRS0NHj92hqBPUWNVH3zDGPAbkichNw48bY34/wtvUeFazERLSYeI0uyM5lquxuaUSshaPeMre5m76HWZwbeRQ42ps3rG/nYw5cTZHo05EYzU0u1raEoGkER5KHa222OqKavfMqCOZXGBtWypHPaW8wSpFzMoIzV/vwixnUqjTdgUVGMctKRhj/uzc/ndwwlFhracNmnbDwq/aHcnI3OiWGqrdUV1SJkSTO2mCTqOtAsbdwWu/FZFkEYkWkXUi0igi3wh0cCrMDM6MGkKD1oaKSbCm0G4qG/WUsoZOsidOID7G3SE8wTcvK5lSTQoqQNwdp/A5Y0w78EWsuY9mAv8ZqKBUmKp1jmSeGoI9j1wyCqGxdNTDZfWh2/PIZV5WCnuau+jq7bc7FHUCcjcpuP5s+gLwd2OMjp5Rx6rdBJNnwYSJdkcyuoxCaNwFjoFjDg04DBWNnSHbyOwyf2oyxsDOA1paUP7nblL4p4jsBJYD60QkHdA+cepo+z8NzfEJQ2UUWuMoDlYdc6j24CF6+x3MmhLaSWGesweStiuoQHB36uxbgFOAImNMH9CFtVKaUpb2OuioC51FdUaTUWhtG3Ycc6i80ep5FOrVR1kpcaTGR7NDk4IKAE9a0+ZijVcY+p5H/RyPCld1JdY21JNCmnN9qIadUHjhUYfK6kNrCc7RiAjznNNoK+VvbiUFEfkrUACUAK7KWIMmBeWy/1OQCMhcaHckxxebCBOnj1hSKGvoJD0plpT4EJrIbxTzp6bw8IdV9A04iI4M6FLrapxxt6RQBMwzurqHGk3tJkifa3X7DHUZ80ZMCqV17czNDO1Sgsu8rGQO9zuoaOxkbmay3eGoE4i7f2JsAzIDGYgKY8ZYJYVQrzpyyVxoDbI73DW4q2/AQVl9J/OywuMLdrCxWWdMVX7mbkkhDdghIp8Ava6dxpjVAYlKhZe2Gmv5zXBJCtnLwDisKb6nnwJAZWMXhwccg9NIhLoZaQnEREVot1Tld+4mhVsDGYQKc/s/tbbhkhRcg+tqNw0mhVLnXELhkhSiIiOYMyWJ0rrRZ3xVyhvudkl9B2skc7Tz+QZgUwDjUuFk/6cQERVay28eT9IUSM6B/Ud+hUvr2omJjGBGehi0iTjNzUyitK4dbepT/uTu3EfXAs8Af3buygaeD1RQKszUbbYamaMn2B2J+7KXHln7AWvW0VlTEsOqJ0Rz4xIAAB3KSURBVE9hVjLNXYdp7Ogd+2Sl3OTu/4AbgVOBdgBjTBmQ4c0NRWSOiJQMebSLyPdF5FYRqR2y//PeXF/ZoH47TFlgdxSembrMGtXc3QJAaV1H2FQdueg02ioQ3E0KvcaYw64XzgFsXpVZjTG7jDFLjDFLsKbN6Aaecx6+w3XMGPOKN9dXQdbVDJ0HwqfqyCVnhbWt/pjGjl6aOnvDLim4ekppu4LyJ3eTwjsi8l/ABBE5F/g78JIf7v9ZoMIYs9cP11J2aNhubcMxKUTGQtX7bN9vze9YmBUeYxRcUuKjmZoSpz2QlF+5mxRuARqBrcB3gFeAn/jh/muAvw15/V0R2SIiD4pI6khvEJG1IlIsIsWNjbqAue3qXUkhzKqPouMg9ySoeo+S6lZEYGF2it1ReWxuVvJgzyml/MHd3kcOrIblG4wxXzHG3O/r6GYRiQFWY5U6AO7BmkpjCVAH/M8osdxnjCkyxhSlp6f7EoLyh/rtED8ZEr1qYrJX3mlQt4XdVdXMykgkKS70p7cYrjAriYrGLnr6jp0KXClvHDcpiOVWEWkCdgG7nKuu/cwP974A2GSMqQcwxtQbYwacCeh+4CQ/3EMFWv12q+ooFNdkHkveaYAhpvYjluSG8BoQx1GYlcyAwwwuI6qUr8YqKfwHVq+jFcaYScaYScBK4FQR+Q8f7/01hlQdiUjWkGMXYU2toUKZYwAaSsOv6sglZwWOqDiW9JWwJHfE2sqQpz2QlL+NNaL5CuBcY0yTa4cxptK5PvMbwB3e3FREEoBzsdonXH4rIkuwejVVDTumQtHBKug/FH6NzC5RsdRPXsln6j6lKzf82hMA8iYnEBcdwU7tgaT8ZKykED00IbgYYxpFxOsKWGNMFzB52L4rvL2eskm9szCXMc/eOHxQHLOCCyPeYSCyDgi/xBAZIczJ1MZm5T9jVR8d9vKYGg/qt1trKKTPtTsSrz3Vaq3EFln+hs2ReK8wM4nSAzrdhfKPsZLCYueI4+GPDiDEV1NRAVe/HSYVQEy83ZF4pamzl/cbJ9CUMBPKwjgpZCXT2t3HgXZdNl357rhJwRgTaYxJHuGRZIwJv/57yr9cPY/C1EeVzQD0F5wL+9ZDT5vNEXmncHBks1YhKd+Fz+xfKrT0dsLBPWGdFNZXNJMYG0XastXg6IfydXaH5JW5zpHYOt2F8gdNCso7jTutbZgmBWMMb+9qZNWMyURNWwkTUmH363aH5ZXkuGhyUidoSUH5hSYF5R1Xz6MwTQqldR3Uth7i3HkZEBEJsz5ntSs4wnNkcKFOd6H8RJOC8k79dohJhJRpdkfilTdL6xGBz8ydYu2YfT4caoGaDfYG5qXCzCT2NOl0F8p3mhSUd+p3QEYhRITfr5Axhle3HWBJ7kTSk2KtnTM/a60et/s1e4PzUmFWMg4Duw5ou4LyTfj9j1b2M8aaMjtMB61t2tdKaV07lyzLObIzLsVar3lX+CYFQKfRVj7TpKA813EADh0M2/aER9dXkRQbxUVLs48+MPt8aCy1pu8IM9MmxZMQE6k9kJTPNCkoz7kW1gnDkkJjRy+vbK3jkuU5JMQOm+Vl9vnWNgx7IUVECHMyk3RiPOUzTQrKc/U7rG0YlhSe2rCPvgHDFSdPP/bg5AKYPCus2xVK63S6C+UbTQrKcw07IDET4ifZHYlH+gccPP7xPk6bmUZBeuLIJ80+D/a8Zw3OCzNzs5Lp6OmntvWQ3aGoMKZJQXmufjtMCb+qozdLG6hr6xm5lOBS8Blw9MG+j4IXmJ/Mc45s1mm0lS80KSjPDPRD466wbE94dH0VU1Pi+Ozc4ywdOu1kiIiGPe8ELS5/mZOpcyAp32lSUJ5pqYSB3rBrTyhv6ODDima+vmo6UZHH+bWPiYfck8IyKSTGRjF9cjyl2i1V+UCTgvJMmPY8+uv6vcRERrBmRe7YJ+efCXVboLsl8IH5WWFmsnZLVT7RpKA8U7/DubDOHLsjcVtnbz/PbqrlC4uymJwYO/Yb8s8ADFS9H/DY/G1uVhJVzV10H+63OxQVpjQpKM807LAW1omeYHckbnv+01o6e/uP38A8VPZyiE6APe8GNrAAKMxKxuh0F8oHtiUFEakSka0iUiIixc59k0TkXyJS5tym2hWfGkX9trDrefTkhn0UZiWzNHeie2+IioHpJ0PVe4ENLADmDS64o0lBecfuksLZxpglxpgi5+tbgHXGmFnAOudrFSoOtVpTQGQusjsSt22rbWNbbTtfOykXEXH/jdNWWWtGhFm7Qk7qBJJio7QHkvKa3UlhuC8BjzifPwJ82cZY1HAHtljbqUvsjcMDT22oJjYqgi8tzh775KGmnWxtw2wqbRFhblaSJgXlNTuTggHeEJGNIrLWuW+KMabO+fwAMGX4m0RkrYgUi0hxY2NjsGJVAHWbrW1WeCSFnr4Bni+p5fMLs0iJ93BJ8anLrKm0960PTHABVJiVzM4DHTgcOt2F8pydSeE0Y8wy4ALgRhE5Y+hBY03gcsxvtTHmPmNMkTGmKD09PUihKgD2l0ByDiSk2R2JW97Z3UhHTz8XL/OwlADWeIWsJbDvY/8HFmCLcybS2dvP7gZtV1Cesy0pGGNqndsG4DngJKBeRLIAnNsGu+JTI6jbDFmL7Y7Cba9urSM1PppVMyZ7d4Fpq6B2I/T3+jewACvKs/pnFFcdtDkSFY5sSQoikiAiSa7nwOeAbcCLwFXO064CXrAjPjWC3g5oLg+b9oTe/gHWlTbwuXmZRB9vBPPxTFtljd52VZuFiWmT4klLjGXjXk0KynNRY58SEFOA55y9QaKAJ4wxr4nIBuBpEbkG2At81ab41HAHtgImbEoKH5Q30dHbz/kLM72/SO5Ka7tvvTX1RZgQEYqmp1K8N7x6TqnQYEtSMMZUAsd8uxhjmoHPBj8iNabaTdY2TBqZX9l6gKS4KE4t8KH9IzHDGqi372M41X+xBUNRXiqvbT9AQ3sPGclxdoejwkiodUlVoar6I5g4HZKO6RAWcowxvLO7kbPmZBAT5eOv+LRV1s8eZgvXFOVZa118UqWlBeUZTQpqbMZYfy1PW2V3JG7ZVd9BY0cvp8/yQy+paauguxmayny/VhAtmJpMUmwUH5Q32R2KCjOaFNTYDu6BroawqVd/v8z6Ijxtpj+SgnMQW3V4LboTFRnByQWTea+sSZfnVB7RpKDG5uqrnxseJYX3y5uYkZ7A1Il+mLRv8kyInxyWK7GdPiuNmoOH2NvcbXcoKoxoUlBjq/4IYpMho9DuSMbU2z/Ax5Ut/iklAIhYpYW9H/rnekF02ixrcOd7WoWkPKBJQY1tz7tW3XpEpN2RjOnTfa0c6hvwX1IA62c/uAc6DvjvmkGQNzme7IkTeHe3Tgej3KdJQR1fyx5rCc6C8Ogp/H5ZE5ERwqoCL0cxj8TVrhBmVUgiwjmFGbxX1qiL7ii3aVJQx1fxlrWdGR5J4b3yJhbnpJAc5+EEeMeTtRiiJoRdUgA4f0EWPX0O3tmlpQXlHk0K6vgq3oKUXKvBNcS1dfextaZ1sC7dbyKjIacoLGdMXZGXyqSEGF7dFl5VX8o+mhTU6PoPW+0JBZ+xGlxD3PrKJhzGT11Rh5t2srWeRG94zTwaFRnBuYVTeGtnAz19A3aHo8KAJgU1usp/Q287zP2C3ZG45f3yJhJiIlk6zc1lNz0xbRUYR9gtugPwxcVZdPb2868d9XaHosKAJgU1um3/gLgUmHG23ZG45f2yJlbNmOz9rKjHk7MCJCIs2xVOLUgje+IEni6utjsUFQY0KaiR9fXArldg7oXWQvYhrrqlm6rmbk4NRNURQFwyZC4My3aFiAjhK8tzeL+8idrWQ3aHo0KcJgU1sl2vWFVHCy6yOxK3uOb48ct8R6OZdjLUFFttLWHmK8tzMAaeKa6xOxQV4jQpqGMZA+v/CKn5YVN19F55E1OSY5mZkRi4m+SfAX3dUPNJ4O4RILmT4jl9Vhp/+2QffQMOu8NRIUyTgjrWvvXWMpQn3xgWo5gdDsOH5U2cOjMNCWQvqbzTQSKPjN0IM986NZ8D7T28vKXO7lBUCNOkoI71wV3WJHBLvm53JG7ZUdfOwe6+wFYdgdWukLMibJPCmbPTKUhP4C/vV+rMqWpUmhTU0Rp3we5XYcW1EBNvdzRuebfMGq3r0ypr7ir4DOwvge7wW7wmIkK45rQZbKtt5+M94Re/Cg5NCupo6/8IUXFw0rV2R+K293Y3MTczKTjLThacDRhrDEcYunhZNpMSYvjzOxV2h6JClCYFdURHPWx+EpZcDglB+KvbD7p6+yne28KZs/08tcVopi6DuImw+43g3M/P4qIj+eYpefx7VyPb97fZHY4KQUFPCiKSKyL/FpEdIrJdRP63c/+tIlIrIiXOx+eDHdu498mfYaAPTv6u3ZG47eM9zfQNGE7393xHo4mMgjmft6rYwrBrKsCVJ+eRGBvFn97W0oI6lh0lhX7g/xhj5gGrgBtFZJ7z2B3GmCXOxys2xDZ+9XbChgeg8IswucDuaNz27u4m4qIjKMpLDd5NCy+Enjaoei949/SjlPhorjh5Oq9sraOisdPucFSICXpSMMbUGWM2OZ93AKVAdrDjUMN8+hj0tMIp/8vuSDzy7u5GVs2YTFx0ELvOFpwN0QlQ+lLw7uln15yWT2xUBPdoaUENY2ubgojkAUsB5yLAfFdEtojIgyIy4p9+IrJWRIpFpLixUeeI94uBfvjobmsN5tyT7I7GbdUt3VQ2dXFGsKqOXKInwKxzYec/wRGeM4+mJcayZsU0nv+0lpqDuoazOsK2pCAiicCzwPeNMe3APUABsASoA/5npPcZY+4zxhQZY4rS04P8ZXCiKn0RWvfBKd+zOxKPvL2rAYAzgtXIPNSCi6GrMWzHLACsPWMGIvDndyrtDkWFEFuSgohEYyWEx40x/wAwxtQbYwaMMQ7gfiB8/mQNdx/fa01pMSe82vbf2FHPjPSEwE5tMZrZF1gD/D79a/Dv7SdTJ07g4qU5PFVcTUNHj93hqBBhR+8jAR4ASo0xvx+yP2vIaRcB24Id27hUuxGqP4aV34GI8Omh3Haoj/UVzXxuXqY9AUTFwKLLYOcr0NVsTwx+cP1ZBfQPOHjgvT12h6JChB3fAqcCVwCfGdb99LcislVEtgBnA/9hQ2zjz0f3QkxS2Exp4fLvnQ30OwznzZ9iXxBLvwGOPtjylH0x+CgvLYEvLprKYx/tpbU7PLvYKv+yo/fR+8YYMcYsGtr91BhzhTFmoXP/amOMztoVaB0HYPtzsPTr1rw+YeS1bQfISIplcU4AVllz15T5kHOSNb4jTBucAW44u4CuwwM89EGV3aGoEBA+9QXK/zY8AI5+OGmt3ZF4pLX7MG/tbOCLi6YSEWHz2tEn3wgHq2Dny/bG4YO5mcmcUziFhz+soqOnz+5wlM00KYxXfT1Q/CDMPj+sBqsB/HNLHYcHHFy8LASGtxReCBOnW3NGhbHvfWYmbYf6eFhLC+OeJoXxatuz0N0Eq66zOxKP/WNTDXOmJDF/aghUeUVEwqobrMb6Pe/aHY3XFudO5JzCDO5/r5K2Q1paGM80KYxHxsDH90B6IeSfaXc0Htl1oINN+1q5eFl2YBfU8cTyqyApC976lfXZhqnvnzOb9p5+HnxfeyKNZ5oUxqO9H8KBrVYpIVS+WN300Ad7iIuO4KtFuXaHckT0BDjjP6H6IyhfZ3c0XluQncL58zN58P092hNpHNOkMB59fC9MSIWFX7U7Eo80dvTyj09ruXhZDqkJMXaHc7SlV8DEabDu1rDuifT9c2fRebif+97VUc7jlSaF8aZ1nzVnz7KrwmZlNZe7/13OgMPw7dPy7Q7lWFExcM6tVgls0yN2R+O1uZnJfHHRVB76oIoDbTrKeTzSpDDefHI/ILDi23ZH4pF9zd08/vFevlqUw4x0G6a1cMf8iyHvdFj3i7BcrtPl5vPmMOAw/Pb1nXaHomygSWE86W6B4odg3mqYGEJ18mMwxvBfz20lNiqS//3Z2XaHMzoRuOD/Qk87vHmr3dF4LXdSPNecns8/NtWyubrV7nBUkGlSGE8+vhcOd1iNomHk4Q+reL+8iR9eMJfMlCCsw+yLKfNh1fVWFVIYNzrfcFYBaYkx/OKfO3A4wrdHlfKcJoXx4lCrNc9R4YXWF1eY+LC8idteLuWcwgy+ftI0u8Nxz2d+Amlz4IXvwqGDdkfjlaS4aG4+by4b9x7k6eJqu8NRQaRJYbx457fQ2w5n3Gx3JG5bV1rPtx7ZQH5aAndctsT+KS3cFT0BLv4zdDXAS98P27ELlxblsGrGJH71Sin17droPF5oUhgPGnZak7YtuxKyFtkdjVue/GQf1z5azOwpSfzt2lUkxUXbHZJnpi61Sgw7nocP77I7Gq+ICL++eBGH+x389PltmDBNbsozmhROdP2H4fnrISYRPvszu6MZkzGG//fmbm75x1ZOn5XO365dRXpSrN1heefU78O8L1uNzrtftzsar+SnJfB/PjebN3bU89jH++wORwWBJoUT3Vu/gP2b4MI7ISHN7miOq3/AwY/+sZX/92YZX1mew1+uKiIhNsrusLwnAl+6G6YsgKevhKoP7I7IK98+bQZnzUnnly/tYFttm93hqADTpHAi++R++PAPUHQNzP+y3dEcV/fhfr7z1408uaGa7549k9u/sojoyBPg1zM2Ea54zhrt/MRlsO9juyPyWESE8PuvLmFSQgzXPbaRBm1fOKGdAP/r1DGMgQ/uhFd+YK27fMFv7Y7ouJo7e7n8/o95a1cDv/zyAn5w3pzQmezOHxLS4MoXIDEdHl0dlmsvTEqI4b4rl9PSdZgrH/yEtm6dSfVEpUnhRNPTBs9dB//6Gcy/CL7yEESGbhVMeUMnl9zzIaV17dzz9eVcsWq63SEFRvJUuOZfVnfgp74B7/0eHA67o/LIopyJ3HdFERWNnVx233r2tx6yOyQVAJoUTiQVb8GfToGtT8OZt8AlD0J06A72eq+skYv+9AEdPf08ce1Kzl+QaXdIgZWQBle9BPO+BOv+Gx7/CrTV2h2VR06blcZDV59E7cFDXPiH93l5S532SjrBSDj/gxYVFZni4mK7w7BfcwW88VPY9TJMngkX/RlyiuyOalSH+x3c8eZu7n2ngjlTkvjLVUXkpIbX5Hw+MQY2PgSv/QgkEs76obUkavQEuyNzW3lDB//x1Ga21raxOHciV508nc8WTiFlQph1HR6nRGSjMWbEL4mQSwoicj5wJxAJ/MUY85vRzh33SeHAVlh/N2z9O0TFwek3WauAheiXy4DD8Mb2A9z+xi4qG7tYsyKXn35xXnj3MPLFwSp49RbY/SokZMDK78CSy62qpjDQP+DgqeJq/vxOJftauomKEOZkJrEoZyJzM5OYmZHIzIxEMpJiT6w2ohNA2CQFEYkEdgPnAjXABuBrxpgdI50/rpJC3yHoOAANpVBbDLtehYYdEJ0Ay66A026CpCl2R3mUrt5+Gjp6Ka1rp7jqIK9uq6OurYdZGYn81+cLOXtuht0hhoaq9602hop1gEDuSsg7FbKXQ2oepORCbFLILojkcBhKalp5q7SBzTWtbK5upb2nf/B4UmwUMzISKUhPYGZGItMmxZOWGEtaYixx0RFEiGCAzp5+2g710Xaoj/ZDfXT09NHR009nbz+9/Q5ioyKIjYpgQkwUSXHWIzku2vk8enBfQkxU+Ix+t0k4JYWTgVuNMec5X/8IwBjz65HO9zop1G+Hv38TcP7sxgx7jvV66PNjzsPN844+1jfgoLPn6FWtBINghlxzyD4gkgHiOdINcIAItkXM4d+Rp/B65Jl0SNKIMym4/m0HIxhyjnHuNcN+HDP05xq278g5x7mu80W/w9B9+MhiMzGREZw2K41LluVw/oJMIvU/7bGaymH7P2DXK1C3BcyQxXok0hqAGBMPkTHOBCFHbyViyD77GKxS4eF+B88XPcLOFkNFYyflDZ3Ut/d6fL0YZzLoG3DQ2+8Yc9YQEUiMtRJGTNSRZtOjPhU5dt/Q0kw4/HaeNSedH39hnlfvPV5SCLVyezYwdPatGmDl0BNEZC2wFmDaNC8nSIuKg4xC1wVdVz76+eAx8fA8jnNM6D7Ux7aa9sFrHPn9ttKACBiOvpdB6IxKpSMylcbYadTEzaI/wmpALhzy2yvO98mwUI68HnZ8hP8lbr936DuHfQmJQKQIkxNjyUiKpSAjkcKsJGKjIlHHkTYTzrzZehzutkqCrXuhtdqat+pwFxzuhIG+I394HLO1v0eTYH2xRAGXr8yDmITBYx09fdS2HqKp4zDNXb309jkwGIyxJuFLnhBFyoTowRJAYlzUUb83xhh6+hx09PTR3tM/WJroOOq561g/fQPW5zE0jwz/o2b4C8MYWSdETEkOTCeSUCspfAU43xjzbefrK4CVxpjvjnT+uKo+UkopPzleSSHUuqTWAkNXf8lx7lNKKRUEoZYUNgCzRCRfRGKANcCLNseklFLjRki1KRhj+kXku8DrWF1SHzTGbLc5LKWUGjdCKikAGGNeAV6xOw6llBqPQq36SCmllI00KSillBqkSUEppdQgTQpKKaUGhdTgNU+JSCOwN4C3SAOaAnh9X2l8vtH4fKPx+cbO+KYbY9JHOhDWSSHQRKR4tFF/oUDj843G5xuNzzehGp9WHymllBqkSUEppdQgTQrHd5/dAYxB4/ONxucbjc83IRmftikopZQapCUFpZRSgzQpKKWUGjRukoKInC8iu0SkXERuOc55l4iIEZEi5+uTRKTE+dgsIhd5ek0b46sSka3OYz6tRuRtfEP2TxORThH5gafXtDE+2z8/EckTkUND/o3vHXLucmd85SJylwxfAs/++N52XtN1zOtFuX359xWRRSKyXkS2Oz+vOOd+2z+/MeLz2+fnEWPMCf/Amoa7ApgBxACbgXkjnJcEvAt8BBQ598UDUc7nWUAD1uyybl3Trvicr6uANDs/vyHHngH+DvzAk2vaFV+ofH5AHrBtlOt+AqzCWgHzVeCCEIvv7eGfsw3xRQFbgMXO15OByBD6/I4Xn18+P08f46WkcBJQboypNMYcBp4EvjTCeb8E/i/Q49phjOk2xvQ7X8ZxZDVXd69pV3z+5HV8ACLyZWAPMHRtjJD4/I4Tnz/5FN9IRCQLSDbGfGSsb5BHgS+HSnx+5kt8nwO2GGM2Axhjmo0xAyH0+Y0Yn5dx+MV4SQrZQPWQ1zXOfYNEZBmQa4x5efibRWSliGwHtgLXOb+Ex7ymzfGBlSDeEJGNIrLWy9h8ik9EEoEfAv/t6TVtjg9C4PNzyheRT0XkHRE5fcg1a453TZvjc3nIWfXxUx+qZ3yJbzZgROR1EdkkIjcPuWYofH6jxefij8/PIyG3yI4dRCQC+D1w9UjHjTEfA/NFpBB4REReDWJ4XsVnjOkBTjPG1DrrIv8lIjuNMe8GOb5bgTuMMZ1B+p0+hg/xhcLnVwdMM8Y0i8hy4HkRme/vGPwdnzGmHfi68/NLAp4FrsD6izyY8UUBpwErgG5gnYhsBNr8HYc/4zPGrCNIn99w46WkUAvkDnmd49znkgQsAN4WkSqsesYXZVhjpDGmFOh0njvWNe2OD2NMrXPbADyHVcwNdnwrgd86938f+C+xllwNlc9vtPhC4vMzxvQaY5qdcWzEqrue7Xx/znGuaXd8Qz+/DuAJ7Pn9qwHeNcY0GWO6sVZ1XEaIfH7Hic+fn59ngt2IYccDKxtXAvkcaQiaf5zz3+ZIQ1A+RxpupwP7sWY39OiaNsSXACQ59ycAHwLnBzu+Yftv5UhDc0h8fseJLyQ+PyCdIw2PM7C+bCY5Xw9vKP18qMTnvGaac380VkP+dTbElwpswtkhA3gT+EIIfX4jxufPz8/Tx7ioPjLG9Dv/+nsdq6fAg8aY7SLyC6DYGPPicd5+GnCLiPQBDuAGY0wTwEjXDJX4RGQG8JyzSiQKeMIY85oN8Xl0zVCJD5hCaHx+ZwC/GPLve50xpsV57AbgYWAC1peaV9WagYhPRBKA10Uk2nnNN4H7gx2fMeagiPwe2IDVRvSKOVKvb/vnN1p8/vz8PKXTXCillBo0XtoUlFJKuUGTglJKqUGaFJRSSg3SpKCUUmqQJgWllFKDNCkopZQapElBKaXUoP8P0uR6yHoeLdMAAAAASUVORK5CYII=
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>These two distributions above represent the bootstrap uncertainty over what the underlying 1-day retention could be for the two AB-groups. There seems to be some evidence of a difference, albeit small. Let's plot the % difference to have a closer look.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">boot_1d</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>version</th>
      <th>gate_30</th>
      <th>gate_40</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>retention_1</th>
      <td>0.449741</td>
      <td>0.437246</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.451816</td>
      <td>0.441358</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.448291</td>
      <td>0.444074</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.450427</td>
      <td>0.441869</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.448662</td>
      <td>0.442401</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Adding a column with the % difference between the two AB-groups</span>
<span class="n">boot_1d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">boot_1d</span><span class="o">.</span><span class="n">gate_30</span> <span class="o">-</span> <span class="n">boot_1d</span><span class="o">.</span><span class="n">gate_40</span><span class="p">)</span><span class="o">/</span><span class="n">boot_1d</span><span class="o">.</span><span class="n">gate_40</span><span class="o">*</span><span class="mi">100</span>

<span class="c1"># Ploting the bootstrap % difference</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">boot_1d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s1">&#39;density&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">% d</span><span class="s1">ifference in 1-day retention between the two AB-groups&#39;</span><span class="p">)</span>

<span class="c1"># Calculating the probability that 1-day retention is greater when the gate is at level 30</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Probability that 1-day retention is greater when the gate is at level 30:&#39;</span><span class="p">,(</span><span class="n">boot_1d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">)</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Probability that 1-day retention is greater when the gate is at level 30: 0.96
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>From this chart, we can see that the most likely % difference is around 1% - 2%, and that 96% of the distribution is above 0%, in favor of a gate at level 30.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">boot_1d</span><span class="o">.</span><span class="n">head</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[&nbsp;]:</div>



<div class="output_html rendered_html output_subarea output_execute_result">
<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>version</th>
      <th>gate_30</th>
      <th>gate_40</th>
      <th>diff</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>retention_1</th>
      <td>0.449741</td>
      <td>0.437246</td>
      <td>2.857707</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.451816</td>
      <td>0.441358</td>
      <td>2.369461</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.448291</td>
      <td>0.444074</td>
      <td>0.949586</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.450427</td>
      <td>0.441869</td>
      <td>1.936873</td>
    </tr>
    <tr>
      <th>retention_1</th>
      <td>0.448662</td>
      <td>0.442401</td>
      <td>1.415214</td>
    </tr>
  </tbody>
</table>
</div>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<h2 id="Comparing-7-day-Retention">Comparing 7-day Retention<a class="anchor-link" href="#Comparing-7-day-Retention">&#182;</a></h2>
</div>
</div>
</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p>The bootstrap analysis tells us that there is a high probability that 1-day retention is better when the gate is at level 30. However, since players have only been playing the game for one day, it is likely that most players haven't reached level 30 yet. That is, many players won't have been affected by the gate, even if it's as early as level 30.</p>
<p>But after having played for a week, more players should have reached level 40, and therefore it makes sense to also look at 7-day retention.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[39]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">sum</span><span class="p">()</span> <span class="o">/</span> <span class="n">df</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">count</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt output_prompt">Out[39]:</div>




<div class="output_text output_subarea output_execute_result">
<pre>version
gate_30    0.190183
gate_40    0.182000
Name: retention_7, dtype: float64</pre>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><strong>Insights:</strong></p>
<p>Like with 1-day retention, 7-day retention is slightly lower when the gate is at level 40 (18.2%) than when the gate is at level 30 (19.0%).
This difference is also larger than for 1-day retention, presumably because more players have had time to hit the first gate.
The overall 7-day retention is lower than the overall 1-day retention; fewer people play a game a week after installing than a day after installing.</p>
<p>But as before, let's use bootstrap analysis to figure out how certain we should be of the difference between the AB-groups.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[40]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># Creating a list with bootstrapped means for each AB-group</span>
<span class="n">boot_7d</span> <span class="o">=</span> <span class="p">[]</span>
<span class="k">for</span> <span class="n">i</span> <span class="ow">in</span> <span class="nb">range</span><span class="p">(</span><span class="mi">500</span><span class="p">):</span>
    <span class="n">boot_mean</span> <span class="o">=</span> <span class="n">df</span><span class="o">.</span><span class="n">sample</span><span class="p">(</span><span class="n">frac</span><span class="o">=</span><span class="mi">1</span><span class="p">,</span><span class="n">replace</span><span class="o">=</span><span class="kc">True</span><span class="p">)</span><span class="o">.</span><span class="n">groupby</span><span class="p">(</span><span class="s1">&#39;version&#39;</span><span class="p">)[</span><span class="s1">&#39;retention_7&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">mean</span><span class="p">()</span>
    <span class="n">boot_7d</span><span class="o">.</span><span class="n">append</span><span class="p">(</span><span class="n">boot_mean</span><span class="p">)</span>
    
<span class="c1"># Transforming the list to a DataFrame</span>
<span class="n">boot_7d</span> <span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">DataFrame</span><span class="p">(</span><span class="n">boot_7d</span><span class="p">)</span>

<span class="c1"># Adding a column with the % difference between the two AB-groups</span>
<span class="n">boot_7d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span> <span class="o">=</span> <span class="p">(</span><span class="n">boot_7d</span><span class="o">.</span><span class="n">gate_30</span> <span class="o">-</span> <span class="n">boot_7d</span><span class="o">.</span><span class="n">gate_40</span><span class="p">)</span><span class="o">/</span><span class="n">boot_7d</span><span class="o">.</span><span class="n">gate_40</span><span class="o">*</span><span class="mi">100</span>

<span class="c1"># Ploting the bootstrap % difference</span>
<span class="n">ax</span> <span class="o">=</span> <span class="n">boot_7d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span><span class="o">.</span><span class="n">plot</span><span class="p">(</span><span class="n">kind</span><span class="o">=</span><span class="s1">&#39;density&#39;</span><span class="p">)</span>
<span class="n">ax</span><span class="o">.</span><span class="n">set_title</span><span class="p">(</span><span class="s1">&#39;</span><span class="si">% d</span><span class="s1">ifference in 7-day retention between the two AB-groups&#39;</span><span class="p">)</span>

<span class="c1"># Calculating the probability that 7-day retention is greater when the gate is at level 30</span>
<span class="nb">print</span><span class="p">(</span><span class="s1">&#39;Probability that 7-day retention is greater when the gate is at level 30:&#39;</span><span class="p">,(</span><span class="n">boot_7d</span><span class="p">[</span><span class="s1">&#39;diff&#39;</span><span class="p">]</span> <span class="o">&gt;</span> <span class="mi">0</span><span class="p">)</span><span class="o">.</span><span class="n">mean</span><span class="p">())</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>


<div class="output_subarea output_stream output_stdout output_text">
<pre>Probability that 7-day retention is greater when the gate is at level 30: 1.0
</pre>
</div>
</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,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
"
>
</div>

</div>

</div>
</div>

</div>
<div class="cell border-box-sizing text_cell rendered"><div class="prompt input_prompt">
</div><div class="inner_cell">
<div class="text_cell_render border-box-sizing rendered_html">
<p><strong>Conclusion</strong>
The bootstrap result tells us that there is strong evidence that 7-day retention is higher when the gate is at level 30 than when it is at level 40. The conclusion is: If we want to keep retention high — both 1-day and 7-day retention — we should not move the gate from level 30 to level 40.</p>
<p>There are, of course, other metrics we could look at, like the number of game rounds played or how much in-game purchases are made by the two AB-groups. But retention is one of the most important metrics. If we don't retain our player base, it doesn't matter how much money they spend in-game.</p>

</div>
</div>
</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[&nbsp;]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span> 
</pre></div>

    </div>
</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>
