编写一个JS函数fn,随机生成(2,32)之中的数,将随机生成的数保存在arr数组且不重复。

方法一:
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

编写一个JS函数fn,接收一个number类型的值,依次加上千分符号,并输出这个数。

方法一:
```javascript
function fn(number) {
    
}
