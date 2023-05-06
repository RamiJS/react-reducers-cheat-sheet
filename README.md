# React Reducers

## What's a Reducer?

a Reducer is a function that takes two parameters, a state and an action. State is the current value or state of the application, action is what function or action do we want to perform on this state.


## What is useReducer Hook?

```useReducer()``` is a React hook that's used for managing and dispatching actions. ```useReducer``` takes two arguments, first one is the reducer function we create to manage the state of our app, and the second one is the initial value. Just like ```useState```, the ```useReducer``` returns an array of two elements, a ```value``` and a ```dispatch``` function. the `dispatch` function is used to call/send actions to our reducer function. 
