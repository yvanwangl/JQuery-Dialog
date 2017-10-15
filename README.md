# Jquery Dialog
## This is my first plugin which is based on jQuery.
This plugin include some functions, you can create a dialog by 
```
$.dialog()
```
and use 
```
$("element").center() 
```
function to make your element layout center in your screen.

Now , i would like to introduce how to use 
```
$.dialog() 
```
and 
```
$("element").center()
```

## First :

If you want to use a default dialog , you don't have to add any arguments for this function;
## Second :
If you want to custom some text or html in the dialog ,you can do like this:

```
	$.dialog({
		cls : ['class1','class2'],  //with this array you can custom some classes for this dialog ,then you can modify the dialog's style by these classes;
		text : "Here is your custom text",   //you can custom some text for this dialog, such as "This is my first dialog. Haha!!"
		html : '',     //in this part you can use a template or you can use a DOM object which is already exist in your html document. such as "html : $('#dialog')";
		model : true,   //with this argument ,you can decide if you want a model when the dialog alert. The default set is true.
		btns : [{
				text : '确定',
				cls : 'confirm',
				callback : function(){}
			},{
				text : '取消',
				cls : 'cancel',
				callback : function(){}
			}]	//btns ,you need add an array for this argument, you can custom a button or two buttons for your dialog,
				//this array include one or two object, with this object ,you can custom the button's text ,cls and callback function.
		
	});
```
## Third :
If you want to make your element layout center in your screen , you can use center() function like this: 
```
$("#element").center()
``` 
So amazing, you can make element center in your screen.

# Personal website

Here is my [personal website](http://www.yvanwang.com/).
Let's be friends
