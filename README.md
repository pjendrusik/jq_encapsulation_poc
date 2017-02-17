Example how to handle two different versions of jQuery loaded at the same time on single page.


Output:

jQuery from header is loaded - global scope

1nd loaded jQuery version ($): 1.10.2

jQueryValidator loaded 

Secondary jQuery loaded, before $.noConflict(true) - global scope

2nd loaded jQuery version ($): 1.6.2

jQueryValidator not loaded 

$.noConflict(true) is called - global scope

After $.noConflict(true) - global scope

1st loaded jQuery version ($): 1.10.2

jQueryValidator loaded 

2nd loaded jQuery version (jq162): 1.6.2

jQueryValidator not loaded 


Self-invoking scope, injected jq162

Injected version1.6.2

jQueryValidator not loaded 


Self-invoking scope, injected global jQuery

Injected version1.10.2

jQueryValidator loaded 