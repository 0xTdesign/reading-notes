# Class 7



## Explain why we need domain modeling.

We need Domain modeling allows us to easily describe and model real world entitlies and the relationships bewteen them. They have lots of real world uses that they can be used for. 
[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

### Why should tables not be used for page layouts?

Tables use to be used for layouts when browsers were terrible. But now days they're mot used. I will list a few reason why you dont use tables for page layouts any more.
- Layout tables reduce accessibility for visually impaired usders
- Tables mess with tags and make the results of the code harder to maintain and debug 
- Tables are not automatically responsice. So you will have loads of issues with differant size screens.

#### List and describe 3 different semantic HTML elements used in an HTML ```<table>```.

```<td>```A TD element creates a single cell in a tabvle 
```<tr>``` A TR element is used to wrap all the TD elements in to keep the cells from growing over teh right amount you want to add.
``` <th>```  A TG element is used for the top of your table. To give each column or row and label. 

Below is an example [tables](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

```
<table>
  <tr>
    <th>Data 1</th>
    <th style="background-color: yellow">Data 2</th>
  </tr>
  <tr>
    <td>Calcutta</td>
    <td style="background-color: yellow">Orange</td>
  </tr>
  <tr>
    <td>Robots</td>
    <td style="background-color: yellow">Jazz</td>
  </tr>

```


##### What is a constructor and what are some advantages to using it?

A constructor are better than objects when you need to create more than one object. By using a Constructor you can write less code but still be able to get all the functiosn and data that you require.

###### How does the term this differ when used in an object literal versus when used in a constructor?

When you use this. in an object it is searching for the name inside the object. But when you use this. in an Constructor your binding this. to the new object so you can refer to this in your constructor code 


###### Explain prototypes and inheritance via an analogy from your previous work experience.
NOTE: This is a very common front end developer interview question

every function in JavaScript has a prototype




