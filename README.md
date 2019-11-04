# popover
A jQuery plug-in for Popover

![demo preview](https://github.com/shulkme/popover/blob/master/preview.png)
> Example

```html
<button id='btn'>click me</button>
```
```javascript
$('#btn').popover({
    title : 'popover',//title
    content : 'tooltip',//content
    autoPlace : false,//Set a reasonable place,default true
    trigger : 'hover',//Trigger mode,default 'hover','click','focus'
    placement : 'top',//Preferred placement, if autoPlace is false,Fixed here
    delay : 1000 //Show and hide delay time
});
```
