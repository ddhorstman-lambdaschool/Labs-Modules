# Module Inquiry 4

## Questions

1. Link to the pull request you are most proud of.
> [Feature - Redux City Store](https://github.com/Lambda-School-Labs/Labs26-Citrics-FE-TeamB/pull/4)
2. Why are you proud of this feature? What was difficult about its implementation?
> It took some time to figure out how to work with the folder structure and re-exporting things. I'd never used contexts before, and it was fun to learn something new!
3. How does this feature help the user?
> It is a pretty core feature - it makes it possible to keep track of which cities you're interested in to be able to generate a comparison or a detail view. 
4. Think about the process of delivering this feature: from ideation, to scoping, to pairing, to testing. Knowing what you know now, what would you change about the way in which you delivered this feature?
> There were definitely things to change, and in fact, I changed some of them in a later pull request. I changed the name of the variable from `cities` to `selectedCities` to better match its functionality and allow for easier expansion of the state store in the future. We spent a lot of time discussing how to manage detailed data, and in retrospect, I think I would have tried to implement caching of details in `localStorage` (although it isn't too late to do so later).