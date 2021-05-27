## REVENGE.CSS

<img src="russell.jpg" alt="blade" width="400" />

[![Total Downloads](https://img.shields.io/npm/dt/@fiskhandlarn/REVENGE.CSS.svg)](https://www.npmjs.com/package/@fiskhandlarn/REVENGE.CSS)
[![Latest Version](https://img.shields.io/npm/v/@fiskhandlarn/REVENGE.CSS.svg)](https://www.npmjs.com/package/@fiskhandlarn/REVENGE.CSS?activeTab=versions)
[![License](https://img.shields.io/npm/l/@fiskhandlarn/REVENGE.CSS.svg)](https://www.npmjs.com/package/@fiskhandlarn/REVENGE.CSS)

The premise of `revenge.css` is simple: A *CSS snippet/bookmarklet* that uses selectors to find bad markup, displaying ugly pink error messages in *comic sans serif* wherever you write bad HTML. If you activate the bookmarklet and the page gets lots of pink blotches, the author has included at least one of the following:

* Misplaced &lt;div&gt;s
* Deprecated elements
* Malformed hyperlinks
* Inaccessible forms
* Empty elements
* Inaccessible images
* Missing ARIA landmarks
* Badly authored sectioning elements
* Erroneous lists
* Obsolete attributes

## Try the bookmarklet

GitHub won't let me use javascript in my README. Pretty sensible.

`javascript:(function(){revenge=document.querySelector('link[href="https://rawgithub.com/AmyAmy/REVENGE.CSS/master/revenge.css"][rel="stylesheet"][media="all"]');if(revenge!=null){revenge.parentElement.removeChild(revenge);}else{revenge=document.createElement('LINK');revenge.href='https://rawgithub.com/AmyAmy/REVENGE.CSS/master/revenge.css';revenge.rel='stylesheet';revenge.media='all';document.body.appendChild(revenge);}})();`

Or, go to the original <a href="http://heydonworks.com/revenge_css_bookmarklet/">hot pink, skull-festooned demo page</a>.

## Install

```bash
npm install fiskhandlarn/REVENGE.CSS --save-dev
```
