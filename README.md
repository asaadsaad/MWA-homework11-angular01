# MWA - Homework 11 - Angular 01
## Exercise
1. Create a new Angular application from CLI.
2. From the CLI, create a flat component class `Counter`, with inline template and style.
3. Render this component in `AppComponent` and test if everything is working properly.
4. Add one property (state) `counterValue=0`.
5. The component template should have two buttons and variable bound to the `counterValue` property, when the user clicks on `"-"` or `"+"` buttons the `counterValue` should decrease/increase and the user must see the change.
  
**Update the `Counter` Component:**  
1. Create an `Input` so if the parent component sets its value we will change `counterValue`.
2. Create an `Output` that emits the current value every time it changes.
3. Update your `"-"` and `"+"` methods to reflect the change of `counterValue` to the output.
  
**Update the `AppComponent`:**  
1. Create a property `ChildCounterInitValue` and bind/pass its value to the `Counter` component `Input`.
2. Listen to any output changes of counter and reflect the change to a local property `ChildCounterValue`.
3. Display (bind) `ChildCounterValue` in the template and verify it works.
  
**Add more than one counter component into your `AppComponent` and notice how each one has its own state.**  
  
  
![Counter](http://www.mumstudents.org/cs572/lecture12/counter.png)
