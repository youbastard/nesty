nesty - Nicholas Ortenzio 2013

View a sample at http://downwith.us/nesty

=====

an alternative to nested "for" loops

====

It occured to me that I really hated dealing with nested for loops. two layers are bad, three is even worse... etc;

Nesty provides an cleaner alternative to deep nesting in your code.
Simply call the nesty function with the arrays you want to loop through and it takes care of the rest.

for example, to print out the numbers in 0 - 255; which would normally take 8 nested loops, you can do this 

var a=[0,1];

var func = function(a,b,c,d,e,f,g) { console.log("" + a + b + c + d + e +f + g); }

nesty(func, a,a,a,a,a,a,a,a);

