# Module Inquiry 2

## Questions

1. What technical choices did you make today? 
> - We decided to use the DS API directly and not have a dedicated Web backend. 
> - We settled on Redux for state management. 
> - We decided to use the Google Maps (Places) API to support auto-complete in our search bar.
> - We decided to route all data through one endpoint rather than having multiple endpoints to manage different sorts of data.
2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?
    - Take a moment to think about the advantages in choosing the route that you did.
    - Now take a moment to consider the disadvantages.
> Maps API: This was ultimately a fairly easy decision. The main consideration was how much complexity it would add to the project. We did some exploratory research and determined that, for our purposes, we could use just a small chunk of the API in a fairly straightforward manner. The main advantage is that we don't need to program out own auto-complete system. The main disadvantage is that we're reliant on Google's servers being responsive to keep our application running smoothly.

> Single vs multiple endpoints: This was actually a rather contentious decision. We spent some time going back and forth discussing the benefits and drawbacks of both set-ups. The advantages of the system we agreed on is that the frontend needs to only make a single request to get all the data, which should simplify frontend programming. The main disadvantages are that this design potentially wastes server time and bandwidth if we don't intend on displaying all of the data immediately and complicates backend programming.
3. In one or two sentences, summarize why you ultimately made the choice you did.
> We determined that the extra layer of adding Maps API would ultimately make the overall program simpler. We decided the simplicity of making one API call was worth any potential waste, which should be small given the efficiency of the underlying systems.
4. Extracting useful conclusions from your process: 
    - According to your understanding, what makes a good technical choice?
> A good technical choice is one that increases the simplicity, flexibility, or power of your program. A good technical decision is one that most team members can agree on.