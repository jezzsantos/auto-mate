# auto-mate

At some point in every software product/project, you will have created patterns and structure (in your classes/objects/layers/systems) that you want to repeat over and over again with some pre-defined patterns. 

Yeah for sure, those patterns will evolve over time, and when they do you'll want them to change where ever they are used in your code. That, after all is what refactoring is all about. Change, optimization, simplification, clarity.


For example, let's say that you are creating a web API and you have already figured out how to create your `customer` resource. All the way from endpoint's route and DTO's to the repository and persistence DTO's. Then you go to create two other new resources `order` and `product` that pretty much follow the same patterns (different data, different operations for sure), but also differ in two ways: different names, different data, different contracts (i.e. the name of the resource, the name of its collection of resources, the HTTP verbs it supports, the database's connection string, etc, etc, etc). This "variablity" of your pattern is highly predictable. Then, there's the stuff that varies but not in a predictable way. Your domain behavior. That "variability' is beyond predictability. 

Now, the job is to create 2, maybe more new resources similarly to the `customer` resource, that are going to follow the same patterns as your `customer` resource throughout your architecture, but with some minor but predictable variance, and some major unpredictable variance.

Your initial design patterns of whatever the resource is in this API may have stabalized by this point and there isn't any need for creativity or exploration of that for now. You just need to write the code for these new resources and it has to be consistent with the existing stuff, right across the code base. The real creativity is not in the definitions of the interfaces or data transfer objects of the predictable variability. Its in the behavior of this new resource - the unpredictable variability. That's where you want your team to focus. So why spend so much time paving down all the scaffolding one keystroke at a time. That problem is already solved. The tools can do that for you. Why risk manual typos and spelling mistakes? Wouldn't smart refactoring tooling be able to accelerate this process for you, and put you where you really want to be, defining the behavioral code instead?

This is the exact time when we get the most value out of tools and automation so we can get back to the creative and exploratory parts of the solution. Why follow a written guide, painstakingly written and kept up to date by your tech lead, when they could have just written the tools could to do the job for you?



We know similar tools already exist in some frameworks/languages, such as Ruby on Rails, Ember.js, Resharper and Yeoman. But we don't always start with these tools and it doesn't always make sense to start with an initial scaffolding. 

Many products should emerge organically, tailored to the specific problem at hand. But they still end up with predictable structure, naming and patterns that should be consistent across the codebase.

At that essential point in time, you are going to wish you had some kind of "helper" that could _just_ learn and apply your patterns for you, throughout your codebase given just a few variables (names. monikers and options) and have those tools write the code for you the same way you would have written it without descending into copy/paste hell. Only, infinitely faster and more reliably than you would have done yourself!
And then what if the patterns change? What if you learn a better way to achieve the same thing but now with this extra benefit? You now have the arduous job of manually refactoring all the places the pattern is used and re-used, and dealing with all that variability keeping that up to date. Welcome to search and replace hell! well what if those tools did that refactoring for you in one command? right across your codebase?

Sure, once we identify our patterns we _can_ write the templates ourselves in our IDE's using any of the tools available to us, but do we? 

We likely don't because it's too difficult to see the value in that work when we're in the midst of getting it done. We might also think that the patterns will change any day now, and that will invalidate the work of creating the templates in the first place. Now we have to get those updates to everyone else before they push.  

But what if we had something to help us detect and harvest those patterns for us, create and maintain those patterns and templates for us? What if that something then made it easy to modify the templates when the patterns change, and we could enjoy the change right across the code base instantly?

That's what auto-mate is: it learns your implementation patterns from your code, makes them easy to repeat and maintain. And if your patterns change, it's easy to apply them across your whole codebase, and your whole team

## [Documentation](https://github.com/jezzsantos/auto-mate/wiki/Home)
