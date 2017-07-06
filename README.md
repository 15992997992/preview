编写一个JS函数fn,随机生成(2,32)之中的数,将随机生成的数保存在arr数组且不重复。
```javascript
function fn() {
    var arr = [];
    var numarr = [];
    while (numarr.length > 30) {
        var number = parseInt((Math.random() * 30) + 2);
        if (!arr[number]) {
            arr[number] = "ture";
            numarr.push(number);
        }
    };
    return numarr;
}
fn();
```

