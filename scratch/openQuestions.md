##Open Questions

###Syntax
1. Should users be given the ability to customize/extend the syntax? 
  * This could be useful if we want to represent variables in our text 
  * Example: `the date today is {namespace: bash, cmd: date}` could be replaced by a custom syntactic element (in this case the  `$` symbol to represent the running of a command with bash) which would then look like the following `{import: bash} the date today is {$date}`
