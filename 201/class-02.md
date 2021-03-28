# Basics of HTML, CSS & JS

## HTML elements  
HTML is a hyper text markup language which is used to specify the structure of the page.  
we do that by using elements. an element consists of a tag and the content of the said tag.  
a tag is predifined word or letter enclosed in angular brackets most have opening and closing tags but some are called self closing tags as they dont need a closing tag. example: `<p>` this is an opening tag for a paragraph element the closing tage for differs with a forward slash before the p inside the angular brackets like this:   `</p>`.  
all closing tags start with the forward slash to denote that it is a closing tag. as for self closing tags and example for that is the `<br/>` tag which breaks into a new line. self closing tags are only one tag that optionally ends with a forward slash as writing `<br>` is also perfectly fine.  
there is also something called and attribute which defines somethings in some tags well take and example and go through it for more clarification. here is an image tag:  
`<img src="URL">`  
this is a self closing tag. the new thing here is the **src="URL"**, src is called an attribute which -for this tag- is defining the source of the image and whats in between the quotation is called the value of the said attribute -in our case is the src attribute- and the value of the src attribute of the image tag is the url of the image if the image is online or the relative path of the image in your project.  

we will discuss one tag in detail and it should be enough for you to go and learn about the others yourself and experience the joy of searching and discovering something new.    

## HTML Headings  
HTML has **six** types/levels of headings from h1 up to h6.  
h1 represents the main heading and the others are all supp headings.  
HTML displays h1 the largest and it gets smaller with h2 and smaller with h3 and so on.  
the h1 heading has more importance than the others as the search engings look for h1, as for the size it can be changed with CSS.
heading tags are written bitween angular brakets with the assossiat level like: `<h1>`HEADING TEXT HERE`</h2>` or `<h2>`HEADING TEXT HERE`</h2>`(note that without css h2 heading is smaller that h1 heading).here is a picture to make things clearer:  
![html headings](images/headings.png)  

## what is CSS and why we use it  
CSS stands for cascading style sheets. while the HTML defines the structure of the page, CSS defines **HOW** the structre will look like. as i want the image on the left with this size and the text to appear next to the image with this specific color and i want the back ground to look like this and so on so forth.  

## how to use CSS  
there are 3 ways to implement CSS to our web page:
- inline CSS
- internal CSS
- external CSS
the **inline CSS** is as its name aplied is inside the opening tag and is initiated with the an attripute called style inside the attribute you difine values such as color and background color. example:  
`<p style="backgroun-color: red;">`  

**internal CSS** on the other hand is implemented using the `<style> some CSS code </style>` tags in the head tag.
writing CSS code is fairly simple. you have to specify the tag you want to style and then curly braces and inside the curly braces you specify the values you want to style. example:  
p{  
    color: red;  background-color:blue;  
}  
this will change all p tags to have a red color and a blue background color if you want to style only a specific paragraph (lets say its inside a div tag in the main) you have 2 ways:  
the first way is to go through the parent tags until you reach the p tag you want to modify. example:  
`body main p{  
    CSS code  
}  
this will change all the p tags inside the main to have the same style.  
the other way is to give it an id. an id is uniqe to one tag and one tag only. you can specify and id just like an attribute like this:  
`<p id="ID_NAME">`  
this will give one p tag the id of ID_NAME and you can go inside the style tag and instead of going through the parent tags all you need to do i specify the id like this:  
#ID_NAME{  
    CSS code  
}  
this will style only the p tag with the id of ID_NAME and if you want to change multiple tags you can use class. its the same as the id but can be shared with multiple tags and when calling it in the style tags you call it with a dot instead of a hash(#).  
as for the **external CSS** you create a seperate CSS file with the extintion of css and link it with the link tag inside the head. the code inside the file is the same is the code inside the style tag in the internal CSS.

## basic javascript instruction  
javascript is a programing language we use to make the website or web page more interactive and dynamic.
we will go through simple js instruction going from variables to conditional statments and such.  
### variables  
variables are a name we give to storage to store some data and be able to acces and manipulate with it later.
the data we store inside the variable has a type and js has multiple types such as strings which are texts in quotation marks or numbers like integers and floats or booleans like true or false. these data types can be stored inside variables.  
**creating a variable**  
we create a variable buy writing var equal sign and the vlaue of that variable and end with a semicolon. example:  
**var name = 'khaild' ;**  
now the string khaild is now stored inside the variable called name. you can change the variable's value like this:  
**name = 'mohammad';**  
now the value of the variable called name is mohammad. you can also store numbers and booleans inside variables the same way. like this:  
**var age = 45;**  
**var fact = true;** 
the (=) sign is calle the assignment operator.  
### operators  
operators are symbols used to do some tasks depending on the type of the operators. we have **logical operators, mathmatical operators and comparison operators**.  
operators are fairly easy specialy the mathmatical ones as the + sign does addition and - does subtraction we use * for multiplication and / for division. as for the comparison operators as the name emplys they compare between 2 values this makes an expression we have the less than operator(<), equal operator(==), more than(>) operator and not equal (!=) operator.  
the logical operator are used to evaluate two expressions to give a boolean of true or false. a picture is better than a thousand words so here is a picture for some clarification:  
![logical_operators](images/logical.png)  
### conditional statments
conditional statments are a block of code excuted when a cetain condition is met we will discuss if statemnt briefly the if statment is written easily as followin:  
if(condition){  
    code  
}  
the condition is an expression that might consists of logical operator or a comparison operator and the code inseid the curly braces is excuted only and only if the expression is evaluted to true.  
