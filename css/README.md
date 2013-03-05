# CSS #

## Third-party ##
### Normalize.css ###
Set styles to be universal for operating system and browser.  Much better than reset.css as it doesn't obliterate useful styles.

## Selectors ##
### Type Selector (element) ###
Type selectors should only be used to describe default or base styles.  They should never be used in conjunction with id's or classes.

	div.some-type-of-class		X
	.some-type-of-class			√
	
### Id ###
An Id should only be placed on elements that meet one of the following conditions

1. Used for a javascript hook
2. To create an anchor for jumping to sections within a document

### Classes ###
Classes should be the primary method for styling content.  The focus should be on making them highly reusable and decoupling structure from skin.  This is the primary stable of OOCSS.

## Naming Convention ##
Class selectors should be named semantically to allow for readability.  The following format should be followed.

	[type-of-element]-[specific-identifier]-[element description]
	layout-home-navigation
	icon-facebook
	
## Grid ##

## Responsive ##
