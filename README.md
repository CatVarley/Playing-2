# Playing-2
var chalk = require('chalk');
console.log(chalk.green("Hi Matty"));
var family = ['Matt', 'Cat', 'Richard', 'Lucy', 'Ellie'];

for(member in family) {

if(family[member] === 'Cat'){
	console.log(chalk.red(family[member]));
} else if(family[member] === 'Richard'){
	console.log(chalk.blue(family[member]));
} else if(family[member] === 'Lucy','Ellie'){
	console.log(chalk.green(family[member]));
} else {
 console.log(family[member]);
}
}
