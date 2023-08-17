# Collective noun prompts for generative art

This is a small project to build a small website that generates a randomised prompt for generative art. Prompts are 


It could show pre-written template classes in JavaScript or Processing / Java that could be copied and pasted.

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

Protected words in p5.js and Processing:
- `point`

Other (randomisable) variables: 
- How many members of the collective noun are there?
- What properties do the consituent objects have?
- Is the collection itself an object, or an array?