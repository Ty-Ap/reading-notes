# HTML Forms

Why are forms so important in web development?

- to give users the ability to input data and interact with the web page.

When designing a form, what are some key things to keep in mind when it comes to user experience?

- accessibility from using proper html elements and naming conventions

List 5 form elements and explain their importance.

- form; defines a form and the attributes that generate its behavior. all following contents get nested in here.
- fieldset; creates groups of "widgets" that share the same purpose. 
- legend; this works as a label to describe the purpose of the fieldset and binds itself to the fieldset. it is used in accessibility tools like screen readers, and will be read alout for each label in legend then label format
- label; formally defines label for a widget; another accessibility tool. are also clickable.
- input; this is the actual moving part of a form, and allows data entry on the client side

## Introduction To Events

How would you describe events to a non-technical friend?

- events are specific signals on the webpage, and event listeners are blocks of sleeping code waiting on said signal to wakeup and run.

When using the addEventListener() method, what 2 arguments will you need to provide?

- the event its listening for and the function to be run when event is heard.

Describe the event object. Why is the target within the event object useful?

- the event object is the object being listened to for the event. the target is what has the code run on it when activated, but both need to exist for the listener to wakeup the handler and execute the code.

What is the difference between event bubbling and event capturing?

- bubbling makes the event inside a parent implicitly fire for other events up to the parent level. event capturing stops this from happening.
