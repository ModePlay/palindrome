# Phrase object (with palindrome detector)
This is a sample NPM module created as part of
[*Learn Enough JavaScript to Be Dangerous*](https://www.learnenough.com/javascript-tutorial). The module can be used as follows:
$ npm install --global modeplay-palindrome
$ vim test.js
let Phrase = require("modeplay-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true