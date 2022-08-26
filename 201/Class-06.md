# Class 6

[Objects](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
## How would you describe an object to a non-technical friend you grew up with?

Say you have a friend and you take down his inforamtion. And you want to display it on a website. Well you could use an object to store all of his information and and then call the bits that you want to post or retrive. You can keep on adding to objects and call any bit of data that you might need.
As you can see below is an Object. We have given the person a name, age and Bio. All three of these can be called any time. It allows us to store large amouts of that can be displayed.

```

const friend{ 

name: ['gary'}
age: 23,
bio: function () {
console.log (' Hi ${this.name} your age is ${this.age}'
}
}
person.name 
person.age
person.bio



```

We use the ${this.name} so that we can bring in the name fromt the object and display it in the string of the bio. The reason we do this is so that there can be lots of different names but the same piece of code. When we put person.name this is calling the object and retriving the name as well. 

### What are some advantages to creating object literals?

It allows us to store lots of values of data in lots of different formats. Eg like having the names of people in a object and inside the {} we give it a name and then we can seperate the data with a (,). This means that we can keep all data in one area and can easily call which bit of data we need. An object is also easy to keep on adding more data to.



#### How do objects differ from arrays?

Ojects can store lots of different types of data such as boolean, arrays and numbers. It can hold large amounts of data that can be called upon. An array stores an ordered collection of data that can be addressed by a number index[0] and if you wanted to keep adding you would need to change more of your code to get the same results.



##### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

Say if you labeled you names in your object like the following 1.James 2.Gary . You can not use Dot notation to call the data you would need to use [] brackeet notation.

##### Evaluate the code below. What does the term this refer to and what is the advantage to using this?

When you use the word {this.} it refers to call to an object. So in the example below you can see that ${this.name} is in the function. This would bring in the name from the data and place it between the {}. It is away of calling (invoking) the object that has the same name in the object data list.


```
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
```


##### What is the DOM?

Document Object Model (DOM) - The DOM is a represention of objects and content of documents on the web. It represents pages so that programs can change the docuemnt structure, style and content.
A website is a document that can be displayed either by windows browser or html source. 

[Dom](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

###### Briefly describe the relationship between the DOM and JavaScript.


DOM is not a programming language but without it Javascript would not have any models or notion of webpages. Javascript needs DOM so that it can see its key compenent parts such as webpages, SVG documents and more.  Even if most web developers will only use the DOM through JavaScript, implementations of the DOM can be built for any language, as this Python example demonstrates:

