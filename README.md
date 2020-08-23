### Hello visitor

I got some really great OSS projects pinned here that I'm very proud of.

[Aquaman](https://github.com/evernote/Aquaman) is the biggest one. It's one of the most important things we use on the Growth Team at Evernote and has helped us quickly build out and maintain really complex onboarding flows. It's Redux middleware, but it combines the Redux store with RxJS observables so that you can depend on changes to both your client state and server state to kick off flows.

[use-structure] is my newest creation. It allows you to use JavaScript data collections (arrays, objects, maps, and sets) for React component state in a more ergonomic way. Mutative updates to those objects are intercepted so that they're actually immutable, which will update the component correctly. Lot's of crazy stuff with Proxy.

[fromable](https://github.com/baron816/fromable) gives you a super efficient and ergonomic way of interfacing with iterables (arrays, strings, maps, sets, etc.). It's similar to [transducers](https://medium.com/javascript-scene/transducers-efficient-data-processing-pipelines-in-javascript-7985330fe73d), but requires only a single import, packs its own combining function (so you can output the result into pretty much any type of value), and would be really familiar to anyone who's used `Array.prototype.map` or `Array.prototype.filter`. Getting the indexes and types to be perfect for this was probably the greatest challege here.

[Tagged-Table](https://github.com/evernote/Tagged-Table) has the ugliest code of the bunch, but it can make your code much prettier where it's used. It turns table data in your code into arrays of objects--essentially allowing you to make your code look like a spreadsheet by having columns of like values.

More projects coming soon!
