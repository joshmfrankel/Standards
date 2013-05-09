# CSS

## Best Practices

### Normalize vs Reset
1. Normalize **SHOULD** be used in favor of reset to prevent removing useful styles

### Classes
1. Classes **MUST** be in lowercase
2. Classes **SHOULD** use a hyphen(-) to separate words
`.home-header-link`
3. Classes **MUST** be semantic and descriptive
4. Classes **SHOULD** be abstracted into common classes for reusability if appearing many times per page

### IDs
1. ID's **MUST NOT** be used for styling multiple elements as they are not resuable
2. ID's **MUST** appear only once per page
3. ID's **MAY** be used to define top level page sections
4. ID's **SHOULD** be used to define anchor points on a page

### Properties & Values
1. Shorthand properties are **RECOMMENDED** to reduce file size and increase readability
2. Values of zero **MUST** not include units

### Font
1. Font-size using rem units **MUST** provide a pixel fallback for older browsers
2. HTML element **SHOULD** be styled using 62.5% for font-size to allow easy px to rem conversions and flexible typography

### Line Height
1. Line-height **MUST** not include units (unitless line-height)
