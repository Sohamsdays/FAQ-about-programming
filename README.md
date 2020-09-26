# FAQ-about-programming

## difference between local variable and instance variable
40

The main differences that I see are in their :

Scope: Local variables are visible only in the method or block they are declared whereas instance variables can been seen by all methods in the class.

Place where they are declared: Local variables are declared inside a method or a block whereas instance variables inside a class but outside a method.

Existence time: Local variables are created when a method is called and destroyed when the method exits whereas instance variables are created using new and destroyed by the garbage collector when there are no reference to them.

Access: You can't access local variables whereas instance variables can be accessed if they are declared as public.

Where they are declared: Local variables are declared in a method or a block before they are called, whereas instance variables can be declared anywhere in the class level (even after their use).
