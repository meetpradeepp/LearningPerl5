# Tutorial III - Scalar Variables
##


In this tutorial lets learn how to use scalar variables. As you must be remembering the scalar
variables is defined using `$` sigil and can be used to store any type of singular values.

This tutorial also covers multiple ways available in perl to access the values. These ways are to showcase the flexibility
available in Perl to access data. As we work with Arrays and Hashes in upcoming tutorials these basics would make more sense.

Rule of thumb

- Single `$` sigil = value in the variable

   e.g: 
   
        $cost = 5; 
        say $cost; # would print 5

- Double `$$` sigil = value stored at the address value stored in variable.

   e.g: 
   
        
        $cost = 5;
        $cost_ref = \$cost;
        say $cost_ref;  # would print address        
        say $$cost_ref; # would print 5
        
Please go through the program to refer the various ways you could access the scalar.
