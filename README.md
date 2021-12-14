Reproduction steps
========================================

[![npm version](https://badge.fury.io/js/%40ckeditor%2Fckeditor5-build-classic.svg)](https://www.npmjs.com/package/@ckeditor/ckeditor5-build-classic)
[![Coverage Status](https://coveralls.io/repos/github/ckeditor/ckeditor5/badge.svg?branch=master)](https://coveralls.io/github/ckeditor/ckeditor5?branch=master)
[![Build Status](https://travis-ci.com/ckeditor/ckeditor5.svg?branch=master)](https://travis-ci.com/ckeditor/ckeditor5)

1. Check the console of sample/index.html

Or

1. `rm -rf node_modules`
2. `npm install`
3. `npm run build`
4. Check the console of sample/index.html

To make it work, just comment out this in src/ckeditor.js and rebuild:
`import RestrictedEditingMode from '@ckeditor/ckeditor5-restricted-editing/src/restrictededitingmode';`
