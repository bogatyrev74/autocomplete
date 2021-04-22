# SGAutocomplete

Realizes a customizable autocomplete that only handles the autocomplete itself.
The rest ist totally up to you. There are some configuration options and
three callbacks that let you customize every aspect of the autocomplete item
creation to the selection of an item or the appearance of an autocomplete item in the list.

You may install this package via npm install `@smply-gd/autocomplete --save`.

Add these two lines to your .npmrc file:
```
@smply-gd:registry=https://npm.pkg.github.com/smply-gd
//npm.pkg.github.com/:_authToken=GITHUB_TOKEN
```

You can include the files you need in our gulp package build 
workflow (in gulpfile.js javascript entry) like this:
```
distFiles: [
    componentsFolder + '@smply-gd/autocomplete/js/SGAutocomplete.js'
],  
```

You can also copy the base scss file and adjust it to your needs or 
use it as a starting point.

## Publish package
Log in to npm via `npm login --registry=https://npm.pkg.github.com` and use your 
Github username and Github token as password. After that use 
`npm publish` to push your new version to github npm package repository.