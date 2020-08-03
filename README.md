# MWA - Homework 11 - Angular 01
## Exercise
1. Create a new Angular application from CLI.
2. From the CLI, create a flat component class `CounterComponent` that has one property as state `counterValue=0`, with inline template and style.
3. The component template should have two buttons and variable bound to the `counterValue` property, when the user clicks on `"-"` or `"+"` buttons the `counterValue` should decrease/increase and the user must see the change.
4. Use this component in `AppComponent` and test if everything is working properly.
  
**Update the `CounterComponent` Component:**  
1. Create an `Input`, so if the parent component sets its value, it will set the initial state.
2. Create an `Output`, that emits the count value any time the state changes.
  
**Update the `AppComponent`:**  
1. Set an initial value for `CounterComponent` component.
2. Listen to state change of `CounterComponent` and display it.
  
**Add more than one counter component into your `AppComponent` and notice how each one has its own state.**  
  
![Counter](http://www.mumstudents.org/cs572/lecture12/counter.png)
