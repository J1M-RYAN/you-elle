# :spiral_calendar: you-elle
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
 ![Dependencies](https://img.shields.io/david/J1M-RYAN/you-elle)
 ![npm](https://img.shields.io/npm/v/you-elle)
 ![vulnerabilities](https://img.shields.io/snyk/vulnerabilities/npm/you-elle)
 ![last commit](https://img.shields.io/github/last-commit/j1m-ryan/you-elle/master)  
A nodejs cli for University of Limerick course timetables. [View on npm](https://www.npmjs.com/package/you-elle)  


![](images/program.gif)  
## :computer: Installation

This package can be installed from the NPM registry or installed after cloning or downloading the repo.

To install from the npm registry run `npm i -g you-elle`  
To install after cloning the repo run `npm i -g .`

`you-elle` can also be used without installing  via `npx`  

## :keyboard: Usage

To use the program run the command `you-elle`  
You can then select your year and course from the menus

Alternatively you can specify year and course as command line arguments in the form `you-elle year course`  
Eg: `you-elle 1 LM121`  
The course must be the UL prefix  
The year must be between 1 and 5  

To use the program without installing run `npx you-elle`

## :hammer: Built With

- [Node.js](https://nodejs.org/en/) - The runtime

- [inquirer.js](https://www.npmjs.com/package/inquirer) - For the interactive commands

- [cli-table3](https://www.npmjs.com/package/cli-table3) - To form a table

- [form-data](https://www.npmjs.com/package/form-data) - To send a request to the UL timetable web app

- [jsdom](https://www.npmjs.com/package/jsdom) - To traverse the dom sent as a response by the web app

- [cfonts](https://www.npmjs.com/package/cfonts) - The fancy you-elle front

- [chalk](https://www.npmjs.com/package/chalk) - To color some of the text  

## :construction_worker_man: Dev Dependencies

- [eslint](https://www.npmjs.com/package/eslint) - The Google javascript coding style is used for this project  

- [jest](https://www.npmjs.com/package/jest) - Is used for the unit tests

## :speaking_head: Acknowledgments

- The `you-elle` cli pulls information [from this web app](https://www.timetable.ul.ie/UA/CourseTimetable.aspx)
