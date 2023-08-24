# Collective noun prompts for generative art

This is a small project to build a small website that generates a randomised prompt for generative art. Prompts are collective nouns that can be used to rename and revamp the characterless hoards of `Particle` and `Walker` objects used in generative art programs.

Collective nouns that are specific to certain kinds of animals are known as 'terms of venery' or 'nouns of assembly', and are thought to have been brought to England from France sometime before the 14th century. See https://en.wikipedia.org/wiki/Collective_noun#Terms_of_venery. Apparently, they were used as a way to demonstrate one's intellect, and for that, I find them to be a bit ridiculous. However, the colourfulness of the language lends fertility to comparably beige nomenclature that can sometimes be found in generative art programs.

It could show pre-written template classes in JavaScript or Processing / Java that could be copied and pasted, something like this:

---

## This is a `swarm` of 100 `bees`:

``` javascript
class Bee {
	constructor() {

	}
}

const NUM_OF_BEES = 100;

let swarm = [];

function setup() {
	for (let i = 0; i < NUM_OF_BEES; i++) {
		swarm.push(new Bee());
	}
}

function draw() {
	for (let bee of swarm) {

	}
}
```

## What are `x` and `y`?

They could be idiomatic, subject-specific, figurative or archaic collective nouns. For example:

> A herd of cats

> Grains of sand

> Seeds in a garden

> A network of nodes

> Stars in the sky

> Rays of sunshine


## Notes

> "ce n'est pas un système de particules"


Protected words in p5.js and Processing:
- `point`

Other (randomisable) variables: 
- How many members of the collective noun are there?
- What properties do the consituent objects have?
- Is the collection itself an object, or an array?