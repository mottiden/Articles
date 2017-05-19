# The stack data structure

A **stack** can be imagined as a vertical pile of books. The end of the stack is known as the top, while the beginning as the base. It is not possible to remove the books from the base before moving the elements from the top of the stack. This mechanism is called **LIFO** - last in first out.

To create a new stack object in Javascript we can use a class.

```js

class Stack {
	constructor(){this.elements = [];}
	push(el) {return this.elements.push(el);}; 
	pop() {return this.elements.pop();};
	peek() {return this.elements[this.elements.length-1];};
	isEmpty() {return this.elements.length===0;};
	clear() {this.elements = [];};
	size() {return this.elements.length;};
	print() {console.log(this.elements.toString());};
}

const pileOfBooks = new Stack();
```

## Pushing elements

## Popping elements

## Peek

## Other functions

 
