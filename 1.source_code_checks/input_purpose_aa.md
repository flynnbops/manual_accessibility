#  Identify Input Purpose (AA)

## Background
[Success Criterion 1.3.5](https://www.w3.org/WAI/WCAG21/Understanding/identify-input-purpose.html)

> HTML is formatted correctly.

This test is for autocompletion being handled by the webpage and NOT by the browser.
If the webpage does not support any autocomplete, except via browser, set this test to N/A

## Test Steps

|Step|Action|
|--|--|
|1|Navigate to Webpage and view source|
|2|For each input field that has `autocomplete=` (can be autocompleted), confirm that a unique autocomplete value is present.|

## Notes
If no `autocomplete=`  fields are present, then this test can be skipped.

