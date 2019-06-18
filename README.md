# DRUMS

You will make drums on this project, to be the best drum master !

## Instructions

Edit the `script` tag in `index.html` to make sounds when you use keys from q to l (azerty) or a to l (qwerty).

It should also animate the letter when you strike it whith the css class `.playing` and remove it right after it finishes to add a feeling of STRIKING something.
Try to coordinate the removal of the `.playing` class so that you can change the transition time in the css.

The objectif of this kata is to do 100% native js to stay true to our Bio label.

## Knowledge

* Listen to a key : `addEventListener()` for `keydown` event
* To play a sound : `play()`
* Rewind a sound : `currentTime = 0`
* Transition end : `addEventListener()` for `transitionend` event

## Tips

`data-*` attributes are custom attributes.
