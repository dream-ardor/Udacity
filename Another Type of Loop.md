Directions:

Use the array's forEach() method to loop over the following array and add 100 to each of the values if the value is divisible by 3.
```javascript
var test = [12, 929, 11, 3, 199, 1000, 7, 1, 24, 37, 4, 19, 300, 3775, 299, 36, 209, 148, 169, 299, 6, 109, 20, 58, 139, 59, 3, 1, 139];
```

Remember that the "Test Run" button will display any logged content, so feel free to use console.log() to test your code.

My Code:
```javascript
var test = [12, 929, 11, 3, 199, 1000, 7, 1, 24, 37, 4,
    19, 300, 3775, 299, 36, 209, 148, 169, 299,
    6, 109, 20, 58, 139, 59, 3, 1, 139
];

test.forEach(function(num,index,array) {
    if (num % 3 === 0) {
     array[index] +=100;
    }
});

console.log(test);
```
