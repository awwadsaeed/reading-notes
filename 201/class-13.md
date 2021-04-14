# HTML storage and CSS transitions

## HTML storage  
it is a way to store the some data (named key vlue pairs) localy on the users web browser. the data still exist even after closing the browser tab, exiting the browser, navigate to another website and the like.  
it has some limitations which is you cannot store more than 5 megabytes and you cannot ask for more storage eather. the only exception there is opera, but even in opera the increase in the storage is a user initiated act and the developer cant do anything about it much less asking for more.  

## CSS transitions  
CSS transitions allow us to apply certain changes on HTML elemnts that look like animations.  
you can change the size of the elemnt when hovering on it. you can change its colors, borders and more.  
the most basic transiton implimentaion is specifing a transition key property and its value is the attribute you would like to change and the duration that the change will happen at. example:  
div{  
    width: 100px;  
    transition: width 2s;  
}  
and in the hover you need to specify the new width:  
div:hover{  
    width:200px;  
}  
**the prevous example is a simplified version of one in W3Schools visit [W3Schools]('https://www.w3schools.com/css/css3_transitions.asp')for more info.**