# Sean Yen

Hi! I’m Sean, a second-year undergraduate at UC San Diego majoring in computer engineering. I have been doing web development since 2016.

[My main website](https://sheeptester.github.io/) lists all my interests and projects, but I'll include some of my interests [below](#interests).

For employers, here are my location preferences:

1. San Diego, CA
2. San Francisco Bay Area, CA
3. Seattle, WA

![Me standing on a wall surrounded by water at Sutro Baths with the sun setting behind me.](https://sheeptester.github.io/img/sean-at-sutro-baths-by-cat.jpg)

## Interests

My main three interests are

- Sheep
- Web development
- Linguistics

I also like JavaScript quirks. Here's one I discovered a few months ago:

> The ECMAScript specification has a special case for JavaScript's `for`-`of` syntax.
>
> This is **invalid** syntax:
>
> ```js
> for (async of [2]) async
> ```
>
> However, the following are valid syntax and execute without a runtime error (they all return `2` when evaluated with `eval` or in the console).
>
> ```js
> for (let async of [2]) async
> for ((async) of [2]) async
> for await (async of [2]) async // Inside an async function
> ```
>
> This is because the specification specifies that a `for` keyword followed by an open parenthesis cannot be immediately followed by the exact sequence `async of`. This only applies to `for`, not `for await`.

## Required screenshots

- [x] [Screenshot of command line git transactions](./screenshots/Screenshot%20of%20command%20line%20git%20transactions.png)
- [x] [Screenshot of staged commit in VS Code](./screenshots/Screenshot%20of%20staged%20commit%20in%20VS%20Code.png)
