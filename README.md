Pizza Builder
=============

A browser JavaScript and DOM manipulation exercise.

Based on [css3pizza](http://codepen.io/dsmoore/full/fiwAl)
by [Derek S. Moore](http://dereksmoore.com).

We've got the munchies for a nice, fresh pie of pizza.
Of course, we want to order online.
After all, talking to a person will only delay the consumption of pizza.
There's only one problem: our local pizzeria's pizza builder **isn't working**.
This time,
the local pizzeria is in luck because their customer today is a Web developer.
We always hear about how developers should give back to their community.
I can't think of a more meaningful contribution
than helping the community get pizza more easily.

Taking a look at their pizza builder,
it seems like their JavaScript file, `pizza.js`, is empty.
They must have ran out of money before the developer delivered their JavaScript.
Let's help them out by writing the pizza builder's JavaScript.


Instructions
------------

### Iteration #1: Add and remove toppings ###

There are five buttons on the left of the pizza builder.
Three of those are supposed to add and remove toppings from the pizza.
Write the JavaScript necessary for those three buttons to **add and remove**
**pepperonni**, **mushrooms** and **green peppers** from the pizza.
**Don't worry about updating the price.**
We will do that later.

It appears that each individual topping has its own HTML element.
Here are examples of each of the toppings HTML.

```html
<!-- pepperonni -->
<section class="pep one">1</section>
<section class="pep two">2</section>

<!-- green peppers -->
<section class="green-pepper one"></section>
<section class="green-pepper two"></section>

<!-- mushrooms -->
<section class="mushroom one">
  <div class="cap">3</div>
  <div class="stem"></div>
</section>
<section class="mushroom two">
  <div class="cap">3</div>
  <div class="stem"></div>
</section>
```

How could you conceal and display those elements when the buttons are clicked?


License
-------

ISC © [Nizar Khalife Iglesias](https://twitter.com/khalifenizar)
