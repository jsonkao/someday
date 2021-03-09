## `data-image`

An algorithm that can (a) find a noteworthy trend to visualize in a dataset and then (b) find an image with an entity that is related to that dataset to help communicate the visual.

The model wouldn't need to match two visuals. It already knows the underlying structure of the target data. For example, what if we did a non-linear dimensionality reduction on the image using the structure of the data as the target embedding?

## `comparative-constitutional-challenges`

Visualize cases: constitutional challenges affecting communities of color.

The _Federal Reporter_ contains all reported cases in the nation's lower federal courts.

## `gh-stolen-land`

Visualize land that was stolen by Land Comission/Court of Private Land Claims after the Treaty of Guadalupe Hidalgo.

## `reactive-viz`

A Redux-like state container bound to a reactive visualization.

### Wishlist

* Asynchronous event streams but previous transitions are interrupted (in [`ivy-coronavirus-response`](https://github.com/spec-journalism/ivy-coronavirus-response) this took manual transition naming)
* Built-in scroll triggers
* Interface question: Should users write a state for every step or write a diff for every step? (People must have figured out more efficient ways of storing/exposing/selecting/reducing state than either of these options — the first may be too redundant for the programmer, the second may be too unclear/confusing.)
  * The first option: [`lede.js#L44`](https://github.com/spec-journalism/ivy-coronavirus-response/blob/master/src/scripts/lede.js#L44)
  * [Rich Harris](https://youtu.be/AdNJ3fydeao?t=423): "Frameworks are not tools for organizing your code, they are tools for organizing your mind."
  * But [Mike Bostock](https://youtu.be/lNbqfQlGkzc?t=365): "Code has unparalleled expressiveness... Creativity requires composition."

### Questions

* How can you combine a grammar-of-graphics-like specification with declarative HTML?
* is this observable

### Look at

* [Svelte 3: Rethinking reactivity](https://svelte.dev/blog/svelte-3-rethinking-reactivity): Compiling declarative code to imperative code.
  * Using invalidation

### Examples

See [`ivy-coronavirus-response v0.2`](https://github.com/spec-journalism/ivy-coronavirus-response/releases/tag/v0.2).
