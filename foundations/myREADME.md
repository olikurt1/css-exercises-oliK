More specific CSS declaration will take precedence over less specific declaration. ID would be the most specific with Type being the least specific

This will only occur when an element has conflicting declarations.
If there are two equal selectors, the one with more selectors will be more specific

Inheritance occurs when CSS properties that are applied to a certain element are also passed down to that elements descendant. This doesn't always work however as direct element targeting will change the descendants CSS properties. 

If a parent has an ID selector then the child will have that selector also applied unless, the child has its own selector directly applied inline even if the selector is lower specificity such as a class

If every single rule has been applied and the confilct still hasn't been resolved, then the latest css rule is applied. 