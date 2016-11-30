###  Array 

##### Sort Arrays with sort //数组的中的元素排序取最值

```html
/*
1. sort()作用在数组本身，改变了原数组的排序
2. sort()传入一个函数作为参数，这个函数有两个参数，对这两个参数进行操作，返回正负值和0三种情况，确定排序顺序
*/
var a=function(a,b){
  return a-b;
}
array.sort(a);//已经得到排序后的array 

arr.sort(function compareArr(a,b){ 
    return a-b;
  });
```

array.push()  返回新数组的长度属性   push的内容可以是 任何类型
array.splice(start, deleteCount, item1, item2, ...)  删除并添加 返回被删除的元素组成的数组  array不需要赋值直接被删除后的array覆盖
```html
var myFish = ["angel", "clown", "drum", "mandarin", "surgeon"];
var removed = myFish.splice(3, 1);

// removed is ["mandarin"]
// myFish is ["angel", "clown", "drum", "surgeon"]
```


##### array.filter()  数组筛选过滤
```html
function bouncer(arr) {

   arr=arr.filter(function(val){ 
    return val;
    });  //function把val本身return给filter函数进行判断  val为false就移除  这里filter函数本身就可以执行判断语句
return arr;
}
```
//在condition statements即在判断语句if()/else if()/while()/do while()中只接受布尔值(true or false)，所以判断语句中的值会先转换成true和false进行判断 falsy values包括false 0 "" NaN null undefinded,除此之外的其他都会转成true

 


###   string
str.charAt(0).toUpperCase()  取字符串首字母大写  
str.toLowerCase()  字符串小写  
str.substr(start [,length]) 截取字符串中的一部分 length可不写则取至最后 
str.substring(indexStart[, indexEnd]) 通过下标截取字符串
str.slice(beginSlice[, endSlice]） 通过下标截取字符串 endSlice不取

#####  str.indexOf(searchValue[, fromIndex])        
 返回检索到的searchValue第一次出现时的下标 searchValue是单词则返回第一个字母的下标    
fromIndex <= 0 the entire string is searched.  
fromIndex >= str.length, the string is not searched and -1 is returned.                                        不重合返回-1  
searchValue is an empty string, then str.length is returned.

###  Regular Expressions
 regular expression: /the/gi   /--star  
                              the--the pattern you want to match  
                              /--end   
                              g--global  
                              i--ignore case  
\d  --find number  \d+   +  match one or more digits.
\s  --whitespace   whitespace characters 
                                          " " --space
                                          \r --the carriage return 
                                          \n --newline 
                                          \t --tab
                                          \f --the form feed
 /\S/g   \S -- match anything that isn't whitespace

 example  var expression=
          str=str.match(expression)//得到筛选后的元素组成的数组


##### str.spilt()/array.reverse()/array.join()
reverseString("Hello")
  
    // 1.把 传入的字符串 的每个字母都分开组成一个 数组
    // 2.把 数组 反转
    // 3.把 反转后的数组 用join方法拼接成新的字符串

    var array=str.split('')
    array=array.reverse()
    str=array.join('')
    return str;
}



