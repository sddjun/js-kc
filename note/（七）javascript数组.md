数组对象的作用是：使用单独的变量名来存储一系列的值。
## 创建数组
```
var arr = [1, 2, 3];
```
## 数组的长度
数组只有一个属性，就是``length``，通过length可获取到数组的长度（个数）。

## 访问数组
获取数组中的某一个元素可以使用下标，下标从0开始，依次增加 0,1,2,3,4....
```
var arr = [1, 2, 3];
console.log(arr[1]);  //输出2
```

## 获取数组值的技巧
- 获取第一个值：arr[0]
- 获取最后一个值：arr[arr.length-1] 

## 类数组
类数组和数组有一些相同的特性，但不具备数组的全部的特性。
- 相同特性：结构相同 []，具有length属性，可使用下标获取其中的元素。
- 不相同特性：类数组没有数组的方法。
- 类数组有：函数中的 arguments、document中的getElementsByTagName和querySelectorAll等。
