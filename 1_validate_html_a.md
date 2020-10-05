# Validate the HTML (A)

## Background

> 4.1.1 Parsing: In content implemented using markup languages, elements have complete start and end tags, elements are nested according to
> their specifications, elements do not contain duplicate attributes,
> and any IDs are unique, except where the specifications allow these
> features. (Level A)

Start and end tags that are missing a critical character in their formation, such as a closing angle bracket or a mismatched attribute value quotation mark are not complete.

## Test Steps

|Step  |Action| Expected Result |
|--|--|--|
|1  |Copy the page source information (right click on the page, click `view page source`, then copy it ) |Source copied to clipboard|
|2|Visit https://validator.w3.org/#validate_by_input|On the validate by input screen|
|3|Paste in the page source and click `validate`|A Report is produced listing `Errors` and `Warnings`|

### Warnings
Confirm with your Accessibility Champion (or relevant person) as to if these can be resolved.

### Errors
Raise a bug/defect. Or whatever your defect management process describes.


## Notes on Errors
This check throws up some errors with GOV.UK templates which we do not believe are genuine.

**WIP: To be confirmed**

The following 'errors' are `accepted failures`, with the Gov.UK templates:

- Error: Element h1 not allowed as 
child of element legend in this 
context. (Suppressing further 
errors from this subtree.)
- Error: A link element with a sizes 
attribute must have a rel attribute 
that contains icon or value 
apple-touch-icon
- Error: Attribute src not allowed on 
element image at this point.




