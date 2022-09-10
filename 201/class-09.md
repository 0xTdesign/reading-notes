Class 9

# Why are forms so important in web development?

Forms are a great way to collect data and interact with the user

When designing a form, what are some key things to keep in mind when it comes to user experience?

When designing forms you need to keep in mimd the user that will be using the form. If the form is to big you might end up losing users. Best to keep it simple and only ask the information that you need.

List 5 form elements and explain their importance.

```

<label> - For usability and accessibility, we include an explicit label for each form control
<form> - This element formally defines a form.
<input> - Represents a typed data field usually associated with a control that allows users to edit its value
<textarea> - Represents a multi-line plain-text editing control
<button> - This allows the user to submit his form and can have lots of things asigned to it.
<fieldset> - Is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes.
<legend> - Represents a caption for the content of its parent

```


How would you describe events to a non-technical friend?

Say you have a button on a webpage and you want to click the button and it to do something. Well that is when you would use events.
There are loads of events that you can use and make all sorts of things. Think of a traffic light. We are waiting for the signal to change so that we can start to drive. This is an Event. Something has to be triggered for something else to happen. That is an Event.


When using the addEventListener() method, what 2 arguments will you need to provide?

When using the AddEventListener() we specify two parameters. The NAME of the event that we want to register this handler for and the code that will handle hte function we want to run it with.

Describe the event object. Why is the target within the event object useful?

An Event object is automatically passed to an events handlers to provide extra feature and imformation. Target is a propert of an Event which has a reference to the element which the event was fired. The Target property of the event object is always the reference to the element. It is necessary to have the target property when an event is fired. It will access the properties of the element and will modify some properties of the element. 


What is the difference between event bubbling and event capturing?

Capturing phase checks to see if the elements outer-ancestor has a click event handler on it for the capturing phase and if so it runs it. THen it moves on to the next element inside the HTML and does the same thing. And Bubbling phase does the exact opposite of the capturing phase. The browser checks the parent of the clicked event handler registered on it and runs it. Then it moves on the to the next immediate ancestor element.



