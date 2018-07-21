#Tutorial-I HelloWorld


In this program we try to print "Hello World" using Perl5.

We try to touchbase on 
 - basic program structure
 - some best practices
 - what is package
 - Introducing perldoc
 - Introducing perlcritic
 - Introducing perltidy

Every perl program starts with a comment and exclamation line which is also known as singel. It looks something like
`#!/usr/bin/perl` which basically tells the interpreter the perl to use in case not specified

Then comes the package name. Though its optional to enclose the program in a package at smaller level but its always
the best thing to do. This makes the program to be available in modules which fosters reusability in larger deals.
Also as this whole tutorial is focused to teach you those smaller best practices on the way so that
you get habitual to using these from day 1. The next line of code would be package name and would look like

`package HelloWorld;`

Another thing to remember is that make sure your filename matches to your package names and try to keep just one package
per file exception being only to package `main` which is standard package and can be mixed in the file.

The third and fourth line of the program start with `use`. This is something similar to `#include` or `import` in C and Java
programming languages respectively. It is used to load Perl Modules. Some modules are standards and come default with Perl
installation while some need to be installed as your requirement increase. Detailed help of each module can be accessed using
below command from command prompt.

`perldoc -X strict`

If you need a specific details of some of the standard functions those could be accessed using `perldoc -f <>`.

Moving on remember that each line of code ends with a semi-colon except the comment line(s). Comments are lines of code
which are ignored. Single line of comments are preceeded by `#` and multiline are block like

```
=begin
printf 'In to the comments section';
=cut
```
