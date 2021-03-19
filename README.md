# my-class-repo

Readme

Code Refactoring project

I was supplied with index.html and style.css fyles for the purpose of refactoring. 
Upon observing the the behavior of the page in the browser, it was apparent that the 
search engine optimization button was not functional. Other nav funtions seemed fine. 
upon inspection of HTML it became apparent that div on line 29 lacked an id. Inserting 
id made nav button funtional. 

Scrutiny of CSS revealed redundancies. All expressions with class of "search-engine-optimization"
were exactly the same. 2 could be eliminated by changing the class. First test revealed img 
sizing bug. Renaming the img expressioncorresponding to "search-engine-optimization" card 
resolved this issue. From there various other redundancieswere located and resolved in the 
same way. Furthermore, CSS expressions related to benefit-lead, benefit-brand, and benefit-cost 
had no corresponding class in HTML, and could be deleted.
