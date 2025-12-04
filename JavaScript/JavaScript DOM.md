
## 1. 事件类型
##### 点击事件 onclick
```
<button onclick="alert('点击')">Click</button>
```
##### 改变事件 onchange

##### 焦点事件 onfocus
##### 失去焦点 onblur

##### 加载事件 onload
##### 表单事件 onsubmit

## 2. 获取事件源头

##### 按 ID 获取
```
const el = document.getElementById("myId");
```
##### 按 class 获取



## 3. 获取元素值
对象的 .value
```
var obj = document.getElementById('textID');
obj.value = "Hello World"
```


## 元素奇偶变色
寻找子类 `.children`

改变样式 `.style='background-color:` 
```
function changeColor(){
            var allTrObj = document.getElementById('mailTboby').children
            for (let index = 0; index < allTrObj.length; index++) {
                if(index % 2==0){
                    allTrObj[index].style='background-color: beige;'
                }else{
                    allTrObj[index].style='background-color: lightgrey;'
                }
            }
        }
```