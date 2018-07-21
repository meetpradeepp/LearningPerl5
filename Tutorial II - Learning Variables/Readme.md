# Tutorial II - Learning Variables

In this section of the Perl 5 tutorial we introduce the learners to:
 - variables
 - The types of variables
 - Scope
 - Best practices

Variables are basically used to store values which are then further used during the program
to perform various actions upon. There are different types of values which are required to be
stored during the execution of program. Some of them are single values and sometimes group.

Perl 5 supports three types of variables. These types are not defined by restricted by data types but
could be used to store multiple types of values.
- Scalar :-  Single value of any data type(string, float, integer, boolean)
  Example:
     - `$count = 6;`
     - `$name = "YourName";`
- Array :- Store multiple scalar values together
  Example:
     - `@fruits = ['apple', 'guava'];`
     - `@mixed_values = ['apple', 23, 'road', "closed", 11.47];`
- Hash :- Store key value pair
  Example:
     - `%fruits = ('apple' => 3, 'guava' => 4);`

We cannot complete this section without mentioning the way in which scalar variables
could be used to store the references of other variables. The above mentioned hash could
also be stored as:
 `my $obj = {'apple' => 3, 'guava' => 4};`

Notice the braces. Those braces return the reference of the hash value which could be used further in the program.
