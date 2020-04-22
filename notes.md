- Reading a little and practicing a lot is the fastest way to learn.
- writing down all you can remember from a studied prose passage—can deepen the memory of that passage better than further study.

```javascript
var thanx = "Thanks for inputing";
alert(thanx);

alert(133); // alert会把括号内的值转换为字符串
```

- Variable names are case sensitive, use camelCase, (a 1 _ $)

- % is the modulus operator. It doesn't give you the result of dividing one number by
another. It gives you the remainder when the division is executed.

- ++/--
```javascript
var num = 1;
var newNum = num++; // newNum = 1, num = 2

var newNum = ++num; // newNum = 2, num = 2
```

- concatenate
```javascript
var name = "michael" + "Jacson" + 111  // 数字会自动转换为string

alert("2" + 2)  // 22
```

- prompt
```javascript
// All responses to prompts come back as strings. 
var spec = prompt("Your species?", "human")  // 第一个参数是提示语，第二个是默认值，返回string
// 如果点了取消，赋值为null
```

- alert + prompt
```
alert("Hello " + prompt("name?", "lucy"));
```

- if
```javascript
var name = prompt("name?", "Lucy");
if (name === "Lucy") {
    alert("Hello " + name);
}
```

- comparison
```javascript
=== // is equal to 
!== // is unequal to 
==  
!=
```

- if...else
```javascript
var name = prompt("your name?");

if (name === "a") {
    alert("a");
}
else if (name === "b") {
    alert("b");
} 
else {
    alert("c")
}

// In a series of if tests, JavaScript stops testing whenever a condition tests true.
```








