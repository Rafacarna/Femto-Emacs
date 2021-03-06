## CONTRIBUTER CODING STANDARD

When coding in C it is very important that a consistant coding standard is adopted and
that all contributers ensure that there code complies with this standard.

This is because there are a number of area's in the C language where
a silly mistake can lead to disaster, particularly when performing
pointer arithmetic.

The C allows you to do a lot of direct manipulation on memory through
pointers.  However this also allows you to corrupt programme memory
when you make mistakes.  Such errors can be very hard to find as they
dont reproduce consistantly.

The coding style used in Atto, Femto and FemtoEmacs is Kernighan and Ricthie style otherwise known as K&R.

If you are short of time WikiPedia contains a short description of K&R 
   https://en.wikipedia.org/wiki/Indent_style#Variant:_1TBS_.28OTBS.29

The following link contains and excellent discussion around the reasons for these choices and
the problems that are avoided by using these standards.
   https://users.ece.cmu.edu/~eno/coding/CCodingStandard.html

All the original Atto. Femto code was written in this way to enhance readability of the code.

Another very detailed discussion of coding standards was written by
Sun Microsystems a number of years back.  When I worked for Sun your
code would be rejected if it did not comply.

https://www.cis.upenn.edu/~lee/06cse480/data/cstyle.ms.pdf

All the above papers are worth a read if you are going to contribute
to the C code and may save you hours of debugging and looking for
errors.


## GENERAL PRINCIPLES

Most extensions will be done in femtolisp.
