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

- &&且 或||

- array
```javascript
var array = [1, "hello", 100, "J", "Life"];
var name = array[1];


var array2 = [];
array2[2] = "hello"; 
array2[6] = "sss"; // 可任意索引赋值，未赋值的则为undefined

array.pop(); // 弹出最后一个element, 不可指定位置
array.push("one", "two"); // 在最后插入

array.length
array["length"]  // 数组长度

// 不能用array[-1]访问最后一个element


var pets = ["cat", "dog", "lamb", "pony"];
pets.shift(); //"cat" 从第一个位置弹出 // pets ["dog", "lamb", "pony"]
pets.unshift("sanke", "hippo"); // 从最开始插入 // pets["sanke", "hippo", "dog", "lamb", "pony"]
pets.splice(2, 1);// ["dog"] 从索引2的位置开始删掉1个元素
pets.splice(2, 0, "pigeon", "parrot"); // 从索引2的位置删掉0个元素并插入指定的元素 // pets ["sanke", "hippo", "pigeon", "parrot", "lamb", "pony"]
pets.slice(2,4);// ["pigeon", "parrot"] // 索引2到3的切片，不包括4
```


- for loop
```javascript
// i stands for "iteration." 迭代
var pets = ["cat", "dog", "lamb", "pony"];
var len = pets.length;  // get the length of an array
var matchFound = false; // a flag for matching
for (var i = 0; i < len; i++) {
    if (pets[i] === "poney") {
        matchFound = true;
        alert("Good for you!");
        break; // break out
    }
}

if (matchFound === false) {
    alert("Not Found!");
}


var firstNames = ["BlueRay ", "Upchunk ", "Lojack ", "Gizmo ", "Do-Rag "];
var lastNames = ["Zzz", "Burp", "Dogbone", "Droop"];
var fullNames = [];
for (var i = 0; i < firstNames.length; i ++) {
    for (var j = 0; j < lastNames.length; j++) {
        fullNames.push(firstNames[i] + lastNames[j]);
    }
}

for (i = 0; i < fullNames.length; i++) {
    console.log(fullNames[i]);
}
```




