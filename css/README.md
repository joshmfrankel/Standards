# CSS Best Practices

## Basis of Standards

### Google Code HTML/CSS Standards
All Google Code CSS Standards **MUST** be followed.  They **SHOULD** provide a foundation
for all other standards.  **Note:** All other sections proceeding this one are either not defined in the Google Code Standards or are special cases.

* [Google Code HTML/CSS Standards](http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml)
* **Linter:** Sublime Linter - [CSSLint](http://csslint.net/)

## Coding Standards

### Selectors
1. Selectors **SHOULD NOT** have a tag prepended by a class or an ID `div.class-name`  
2. Selectors **SHOULD** be grouped with common styles

### Classes
1. Classes **MUST** be in lowercase
2. Classes **SHOULD** use a hyphen(-) to separate words
`.home-header-link`
3. Classes **SHOULD** be semantic and descriptive
4. Classes **SHOULD** be abstracted into common classes for reusability if appearing many times per page

### IDs
1. ID's **MUST NOT** be used for styling multiple elements as they are not resuable
2. ID's **MUST** appear only once per page
3. ID's **MAY** be used to define top level page sections
4. ID's **SHOULD** be used to define anchor points on a page

### Properties & Values
1. Shorthand properties are **RECOMMENDED** to reduce file size and increase readability
2. Values of zero **SHOULD NOT** include units
3. Properties **MUST** be in alphabetical order

### Font
1. Font-size using rem units **MUST** provide a pixel fallback for older browsers
2. HTML element **SHOULD** be styled using 62.5% for font-size to allow easy px to rem conversions and flexible typography

### Line Height
1. Line-height **SHOULD NOT** include units (unitless line-height)

## Documentation
See [Universal standards](https://github.com/joshmfrankel/Standards#universal-standards). 

### [CSSDOC](http://cssdoc.net/)
CSSDoc is based off of jsdoc.  The full manual is included [here](https://github.com/joshmfrankel/Standards/blob/master/css/cssdoc-0.2.22.pdf)

1. All files **MUST** be cssdoc compliant
2. Files **MUST** contain a file comment and multiple section comments

## Third-party Plugins

### Normalize vs Reset
1. [Normalize](http://necolas.github.io/normalize.css/) **SHOULD** be used in favor of reset to prevent removing useful styles

### Grids
1. [Semantic grid system](http://semantic.gs/) **SHOULD** be used for grid based
layouts. 
