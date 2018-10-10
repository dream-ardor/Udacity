```javascript
/*
 * Programming Quiz: Colors of the Rainbow (6-4)
 *
 * Use only the splice() method to modify the rainbow variable:
 *  - remove "Blackberry"
 *  - add "Yellow" and "Green"
 *  - add "Purple"
 */

var rainbow = ['Red', 'Orange', 'Blackberry', 'Blue'];

/* My Code Below */

rainbow.splice(2,0);
rainbow.splice(2,3,"Yellow", "Green","Blue", "Purple");

console.log(rainbow);

/* Returns [ 'Red', 'Orange', 'Yellow', 'Green', 'Blue', 'Purple' ] */
