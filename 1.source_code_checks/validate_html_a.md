# Validate the HTML (A)

## Background

[Success Criterion 3.1.2 ]('https://www.w3.org/WAI/WCAG21/Understanding/parsing.html')

> HTML is formatted correctly.


## Test Steps

|Step  |Action |
|--|--|
|1  |Copy the page source information (right click on the page, click `view page source`, then copy it ) |
|2|Visit https://validator.w3.org/#validate_by_input|
|3|Paste in the page source and click `validate`, to generate a report|

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




