Directions:
Create an object called facebookProfile. The object should have 3 properties:

1. your name
2. the number of friends you have
3. and an array of messages you've posted (as strings)

The object should also have 4 methods:

1. postMessage(message) - adds a new message string to the array
2. deleteMessage(index) - removes the message corresponding to the index provided
3. addFriend() - increases the friend count by 1
4. removeFriend() - decreases the friend count by 1


My Code:
```javascript
var facebookProfile = {
	name: "Dan",
	friends: 69,
	messages: ["hi", "bye", "die"],
	postMessage(message) {
		facebookProfile.messages.push(message)
	},
	deleteMessage(index) {
		facebookProfile.messages.splice(index, 1)
	},
	addFriend() {
		facebookProfile.friends += 1
	},
	removeFriend() {
		facebookProfile.friends = facebookProfile.friends - 1
	}
};
console.log(facebookProfile);
```
