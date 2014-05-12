JavaScript-for-Dummies
======================

Some assignments from The Telerik Academy on JS Fundamentals

  1.Convert number to it's English word.html
  
    3 switch-cases was all that it needs.
    
    
  2.Binary search.html
    
    The assignment was to put the binary search to some use.
    
  
  3.Find words in text.html
  
    The assignment was to find how many times a given word is found in a text and also there has to be a case-sensitive
    and a case-insensitive search.Also there must be function overloading or "fake overloading" since JS doesn't support
    overloading and I did it using a switch case and the functions arguments length.
    
    First I remove all dots and commas with "someText.replace(/\W+/g, ' ');	" and then I make an array of all the words
    in the text with "tempString.split(' ');".After that it's a simple comparing of strings.Case 2 is the case-sensitive
    search and case 3 is the insensitive.
