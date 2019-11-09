# popover
> A jQuery plugin for Popover

#### preview
![demo preview](https://github.com/shulkme/popover/blob/master/preview.png)

#### Example
```html
<button id='btn'>click me</button>
```
```javascript
$('#btn').popover({
    title : 'title',//title,string
    content : 'content',//content,string,function,object
    autoPlace : false,//Set a reasonable place,default true
    trigger : 'hover',//Trigger mode,default 'hover','click','focus'
    placement : 'top',//Preferred placement, if autoPlace is false,Fixed here
    delay : 10 //Show and hide delay time
});
```
