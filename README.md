# codingchallenge-es6-es2015

### CODING CHALLENGE

Suppose that you're working in a small town administration, and you're in charge of two town elements:
1. Parks
2. Streets

It's a very small town, so right now there are only 3 parks and 4 streets. All parks and streets have a name and a build year.

At an end-of-year meeting, your boss wants a final report with the following:
1. Tree density of each park in the town (forumla: number of trees/park area)
2. Average age of each town's park (forumla: sum of all ages/number of parks)
3. The name of the park that has more than 1000 trees
4. Total and average length of the town's streets
5. Size classification of all streets: tiny/small/normal/big/huge. If the size is unknown, the default is normal

All the report data should be printed to the console.


##### Notes: You should install these folder in order to create files that will convert your code from es6 to es2015:

**In the computer, you should have node install and set the node modules npm to install these specific folder in your local folder following these commands:**

>$ node install 
>$ npm install npm --save-dev babel-cli babel-preset-ess2015 babel-polyfill

After installation of the packets, you will have a folder called node_modules inside your local folder where contains: .bin, .babel-cli, .babel-preset-es2015, .babel-polyform. Additionally, you will have in your local folder two files: script-transpiled.js and polyfill.min.js, which are the js scripts es2015 converted from the script.js es6.

This conversion is used nowdays for browsers compatibilty.

Here is some sites to test to know if your site work in a specific browser:
(https://www.powermapper.com/products/sortsite/checks/browser-compatibility/)
