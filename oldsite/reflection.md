###What did you learn about CSS padding, borders, and margin by doing this challenge?

I learned that less is more. I didn't use any borders but some margins and padding. I think you want to us margins on no main content if possible, meaning it is good to put it on headers and footers to keep them distanced from your main content, but let the main content flow as much as possible.


###What did you learn about CSS positioning?

I only used a couple floats. I didn't use any CSS position parameters. My page is not that complex, which I think looks better. I learned a lot about CSS positioning in the previous exercise, but not this one so much.


###What aspects of your design did you find easiest to implement? What was most difficult?

I think most of it was easy. I tried to get the results with as little CSS as possible to maintain as much flexibility as possible. There was some strange padding that I couldn't seem to track down in my nav at first, but a lot of it has to do with webkit inheritence, which I fixed by putting reset rules at the top of my stylesheet, to just clear out any default styles, which let me address all the elements myself.


###What did you learn about adding and formatting elements with CSS in this challenge?

I learned, as I just mentioned, that it is good to add some reset rules just to clear the palette. I also learned more about CSS planning, in order to keep it as efficient as possible. For instance I put some font-family parameters in farious selectors, then realized that if I just put that in another blanket text reset rule, then it would just cascade down through everything. I think this is really what you always have to keep in mind. Take an overall look and plan the CSS accordingly. If you want the same font family in general, put that in the widest rule possible, then make more specific rules when and only when needed.