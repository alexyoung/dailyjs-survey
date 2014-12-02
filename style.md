## JavaScript style examples

Code sample from [Mozilla's JavaScript guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators).

### No semicolons

```javascript
function fibonacci(){
  var fn1 = 1
  var fn2 = 1
  while (1){
    var current = fn2
    fn2 = fn1
    fn1 = fn1 + current
    yield current
  }
}
```

### Semicolons

```javascript
function fibonacci(){
  var fn1 = 1;
  var fn2 = 1;
  while (1){
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Commas at the beginning

```javascript
function fibonacci(){
  var fn1 = 1
    , fn2 = 1;

  while (1){
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Commas at the end

```javascript
function fibonacci(){
  var fn1 = 1,
      fn2 = 1;

  while (1){
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Methods and loops with no spaces

```javascript
// No space before the curly brace
function fibonacci(){
  var fn1 = 1;
  var fn2 = 1;

  while (1){
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Methods and loops with one space

```javascript
// The space appears before the curly brace
function fibonacci() {
  var fn1 = 1;
  var fn2 = 1;

  while (1) {
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Functions and loops with two spaces

```javascript
// The function or method name has a space, and so does the curly brace
function fibonacci () {
  var fn1 = 1;
  var fn2 = 1;

  while (1) {
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Indentation with spaces

```javascript
function fibonacci() {
  var fn1 = 1;
  var fn2 = 1;

  while (1) {
    var current = fn2;
    fn2 = fn1;
    fn1 = fn1 + current;
    yield current;
  }
}
```

### Indentation with tabs

```javascript
function fibonacci() {
	var fn1 = 1;
	var fn2 = 1;

	while (1) {
		var current = fn2;
		fn2 = fn1;
		fn1 = fn1 + current;
		yield current;
	}
}
```
