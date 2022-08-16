# Class-03 

## When should you use an unordered list in your HTML document?
You would use an Unordered list when you dont need the order to be in a step by step process. These are normally just a bullet point but can also be changed to other shapes such as a dot or a circle. 

How do you change the bullet style of unordered list items?

You would target the tag is CSS and then type the below to change the style of the bullet points.

```
list-style:square;
list-style:inside;
list-style:none;
```

When should you use an ordered list vs an unorder list in your HTML document?

You should use an ordered list when you need the list to go in a certain order since they will be number 1. 2. 3.. This is good for say a recipe or instructions for something that people need to follow in a set of steps.

Describe two ways you can change the numbers on list items provided by an ordered list?

You can change the list items by using a Type atribuite amd can then set it to Roman Numeral. 

```
<ol type="i">
```

Or you could change the way that the order is by using the ```Start``` attribute. This allows us to change the list without deleting anything. Below you can see that the order would start at 2 not 1.

```
<ol start="2">

```

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding; The best way to describe padding is say if you had a cake and you need to put the cake in a cake box. But the box needs to have some space inside so the cake dont touch the side. This is Paddinng. You give space around the element so it can breath. You dont want it to close to the box or your cake will be damaged.

Margin: Now that the cake is safe in the box and not going to touch the sides of the box we now need to put in on the shelf ready to be sold. We dont want to put it to close to the edge just incase it falls off. So we would use Margin to move it from the edge to give it some more space.


List and describe the four parts of an HTML elements box as referred to by the box model.

Margin: Margin helps push elements away from elements to give it more space.
Padding: Padding gives space to the content intside of its own box.
Border: This allows us to put a border around the content to give it some propertys. This is good for displaying certain as one. 
Height and Width: Using height and width you can control how large and small the content will be displayed on the website and keep it all contained. 



What data types can you store inside of an Array?
Arrays can hold  numbers, Characters, Strings or Objects. 


Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
```
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
 
 ```
 
 Yes the above is a vaild Javascript. It contains an array of information that is broken down into name,Age,Job and hobbies. If you wanted to access the info you could use the code. 
 
 ```
 console.log(people)
 
 ```



List five shorthand operators for assignment in javascript and describe what they do.
```
+= This adds the value to a variable and assigns the result to the variable
*= This Multiplies the value and assigns the variable.
/=  This Divides the value and assigns the variable.
= This is used to assign a value to a variable
-=  This Subtracts the value and assigns the variable.
```

Read the code below and evaluate the last expression and explain what the result would be and why.

```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

```

(10 + False) + Dog 

Describe a real world example of when a conditional statement should be used in a JavaScript program.
Give an example of when a Loop is useful in JavaScript.
