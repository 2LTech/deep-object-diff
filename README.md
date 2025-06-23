**Forked from [mattphilipps/deep-object-diff](https://github.com/mattphillips/deep-object-diff)**

Deep difference between two Javascript objects

## Installation

<!-- prettier-ignore-start -->
##
    	yarn add @2ltech/deep-object-diff

##
    	npm i --save @2ltech/deep-object-diff
<!-- prettier-ignore-end -->

## Available functions

- `diff(originalObj, updatedObj)` returns the difference of the original and updated objects

- `addedDiff(original, updatedObj)` returns only the values added to the updated object

- `deletedDiff(original, updatedObj)` returns only the values deleted in the updated object

- `updatedDiff(original, updatedObj)` returns only the values that have been changed in the updated object

- `detailedDiff(original, updatedObj)` returns an object with the added, deleted and updated differences
