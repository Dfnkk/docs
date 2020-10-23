# Welcome to the coded docs!

## JS

### Importing / Exporting

First lets make a function: 
```JavaScript
function combine(first, second) {
  return `${first}, ${second}`;
}

// now we will export it 

export { combine } 

```
importing

```JavaScript
import { combine } from 'filePath' // filePath is the filepath
```

[Here is a link to a gist example!](https://gist.github.com/Dfnkk/5b3e1395eb27b02189c369784a65350e)

### Libs

#### React

React is a front-end lib that is very popular!

To get started with it you will first need node installed [click here to do so](https://nodejs.org/en/download/).

Then run `npm i create-react-app -g`, this will let you start making React apps.

to make one run `create-react-app nameapp` "nameapp" should be replaced with the name of your app (caps not allowed)!

### Other Stuff
#### SPA's

SPA stands for single page application

#####makeing SPA's

first download this code [here](https://repl.it/@dfnk/singlePageApplications-SPAs-example.zip)

then to add a new page in `index.html` add:
```html
<section id="[pageNameHere]">
  [pageContentHere]
</section>
```

replace pageNameHere with you page name, and pageContentHere with you pages content
in `style.css` you can type `#[pageNameHere]` to edit the styles for that page
finally to add the new page go to `script.js` and in the pages array add you page at the end. To add a button in you page do `<button id="go[pagenamelowercase]"`; replace pagenamelowercase with you pages name in lowercase. After that go to script.js and at the bottom of the `$(document).ready()` function add `clickAddListPageC('[btnid]')` and replace btnid with you buttons id.

##### done!
