# auto-mate

At some point in every software project, you will have created patterns (of classes/objects/layers/systems) that you need to repeat over and over again. Let's say that you are creating a web API and you have already figured out how to create the `customer` resource, all the way from endpoint's route to database. Then you create two other resources that pretty much look the same, but differ in some small way (i.e. the name of the resource, the HTTP verbs it supports, the database's connection string, etc). 

At some point, the design will have stabalized and there isn't any need for creativity or exploration. You just need the code and it has to be consistent across the project. This is when we get the most value out of a tool so we can get back to the creative and exploratory parts of the solution.

We know similar tools already exist in some frameworks/languages, such as Ruby on Rails, Ember.js, Resharper and Yeoman. But we don't always start with these tools and it doesn't always make sense to start with an initial scaffold. Many solutions need to emerge organically, but they still end up with predictable patterns that should be consistent throughout the codebase.

At that essential point in time, you are going to wish you had some kind of helper that could _just_ apply your pattern for you 
throughout your codebase given just a few variables (names, options, etc) and have it write the code for you the same way you would have written it without descending into copy/paste hell. Only infinately faster and more reliably than you would have done!

Sure, once we identify the patterns we _can_ write the templates ourselves using any of the tools available to us, but do we? We don't because it's too difficult to see the value in that work when we're in the midst of it (only creating one resource at a time, for example). We also might think the patterns will change, nullifying the work of creating the templates. But what if we had something to detect the patterns and make it way easier to create the templates?

That's what auto-mate is: it learns your implementation patterns from your code, and makes them easy to repeat. And if your patterns change, it's easy to apply them across your whole codebase.



We have been building these kinds of developer tools for the last decade and no longer want to be constrained to a specific platform, language, editor or toolchain. We understand that expensive tools, IDE's, licenses, platforms, language choices etc just get in the way of developers doing the right thing, so we are going to focus instead on you the developer gaining this capability in the work you do no matter who you do it for. Whether that is as an open source contributor, startup, freelancer or corporate developer, you can choose to use tools like auto-mate to write the software for you.

Our goal, at auto-mate, it to revolutionize the way quality software is built and maintained long-term, so that you can focus on getting software systems working and optimized just the way you like them implemented.

Dont be a code monkey! Add auto-mate to your tool-chain and get more productive as a software craftsman.
