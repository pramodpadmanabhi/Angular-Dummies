# Angular Directives Links - https://www.freecodecamp.org/news/angular-directives-learn-how-to-use-or-create-custom-directives-in-angular-c9b133c24442/



# What is an Angular Directive?
  * Directives are the functions which will execute whenever Angular compiler finds it. Angular Directives enhance the capability of HTML elements by attaching custom behaviors to the DOM.



# From the core concept, Angular directives are categorized into three categories.
  * Attribute Directives
  * Structural Directives
  * Components

# Attribute Directives
  * Attribute Directives are responsible for manipulating the appearance and behavior of DOM elements. We can use attribute directives to change the style of DOM elements. These       directives are also used to hide or show particular DOM elements conditionally. Angular provides many built-in Attribute Directives like NgStyle, NgClass, etc. 
    We can also create our own custom Attribute Directives for our desired functionality.

# Structural Directives
  * Structural Directives are responsible for changing the structure of the DOM. They work by adding or removing the elements from the DOM, unlike Attribute Directives which just change the element’s appearance and behavior.
    You can easily differentiate between the Structural and Attribute Directive by looking at the syntax. The Structural Directive’s name always starts with an asterisk(*) prefix, whereas Attribute Directive does not contain any prefix. The three most popular built-in Structural Directives Angular provides are NgIf, NgFor, and NgSwitch.
  * NgIf - This directive adds and removes the host elements from physical DOM
  * The Ngif condition remvoes gost element from DOM, detaches itself from DOM events, detaches component from change dectection cycle and destroys it.The component and DOM nodes can be garbage collected and free up memeory
  * Why remove rather than hide? refer Docs
  * asterisk (*) prefix importance
    
    
 ##### Rule
 * Only one structural directive per host element
    
# Components  
  * Components are directives with templates. The only difference between Components and the other two types of directives is the Template. Attribute and Structural Directives       don't have Templates. So, we can say that the Component is a cleaner version of the Directive with a template, which is easier to use.
  
  ### Commands to create directive
  * ng generate directive highlight
