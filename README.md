Download Link: https://assignmentchef.com/product/solved-prl-assignment-2
<br>
<ol>

 <li>Let L be a language over the alphabet å= {a,b} that contains strings over {a,b} such that <strong>each string has at least one a</strong> and every a is immediately followed by <strong>0 or 1 </strong>b. E.g. a, aa, ab, aab, aba, aabab… Give a regular expression that describes L.</li>

 <li> Draw an automaton that accepts the regular expression <strong>b(c<sup>+ </sup>b)<sup>*</sup></strong></li>

</ol>

<ol start="3">

 <li> Question 5.8 (a) Draw the symbol table for the following C program at the three points (point 1, point 2, and point 3) using static scope. (b) What does the program print using static scope rule ? (c) What does the program print using dynamic scope rule ?</li>

</ol>

#include &lt;stdio.h&gt;

int a, b ;

int p(void) { int a, p ;    /* point 1 */   a = 0 ; b = 1 ; p = 2 ;   return p ;

}




void print(void) {  print(%d
%d
 , a,b) ;

}




void q(void)

{ int b ;   /* point 2 */   a = 3 ; b = 4 ;   print() ;

}




main()

{ /* point 3 */   a = p() ;

q() ;

}




<ol start="4">

 <li> Question 5.26</li>

 <li>Question 8.9 Give the output of the following program using call-by-value, call-by-reference, and call-by-name.</li>

 <li> <strong>Let input.txt</strong> be a file containing a sequence of strings. The strings are separated using new lines. Write a Perl program <strong>pl</strong> which reads a file <strong>input.txt </strong>and print (1) strings that contain the text “or”,  (2) strings that contain at least two vowel characters (i.e. a, e, i, o, u),  (3) strings that do not start with “h”, (4) strings that have “e” as the second symbol, and end with the letter “y”, and (5) strings that contain both letters and digits.  Assume that input.txt contains only letters a-z and digits 0-9.</li>

</ol>




E.g. input.txt:

<strong>today </strong>

<strong>lord </strong>

<strong>tomorrow helloy helloa </strong>

<strong>abc34 </strong>




Output: <strong>today contains at least two vowel letters today does not start with h lord contains or lord does not start with h tomorrow contains or </strong>

<strong>tomorrow contains at least two vowel letters tomorrow does not start with h helloy contains at least two vowel letters helloy has e as the second symbol and ends with y helloa contains at least two vowel letters abc34 does not start with h abc34 contains both letters and digits </strong>