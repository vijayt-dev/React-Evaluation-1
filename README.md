# React Evaluation 1

## 1) What is React?

1) React is a javascript library for building user interfaces. 
2) It is an open-source
3) React was created by Jordan Walke.

## 2) What are the major features of React?

1) JSX
2) Components
3) Virtual DOM
4) Larger Community
5) Extensions

## 3) What is JSX?

JSX stands for JavaScript XML.
JSX allows us to write HTML in React.
It is a combination of HTML and Javascript.

## 4) What is the difference between Element and Component?

A element is a single element from the component.
A component is group of element.

## 5) How to create components in React?

Components can create into two ways:
1.	Class components 
2.	Function components

**Example of Function component** 

```javascript
function FirstComponent() {
  return <h2>Hi, I am a FirstComponent!</h2>;
}
```

## 6) What are props in React?

props stands for properties.
Props are used to store data that can be accessed by component.
Props can be passed to component. 

## 7) What is the difference between state and props?

| State  | Props  |
| ------------ | ------------ |
| State is mutable  | Props are immutable  |
| Props allow to pass data from one component to other component.  | State generally refers to data or properties that need to be track.  |

## 8) What is Virtual DOM?

Virtual DOM keeps a lightweight representation of the DOM in memory is sync with Real DOM.

## 9) How Virtual DOM works?

Virtual DOM keeps a lightweight representation of the DOM in memory is sync with Real DOM.
If state changes happen it create updated virutual DOM and it compare with previous-made  virutal DOM than updating the acutal DOM.

## 10) What is the difference between Shadow DOM and Virtual DOM?

| **What it is**  | An API to attach a hidden DOM to an element for encapsulation purposes   |  An in-memory representation of the DOM |
| ------------ | ------------ | ------------ |
| **Purpose**  |  Encapsulate logic and presentation inside an element, protecting it from effects from the rest of the page  | Allowing for better performance  |
| **Who Implements It**  | Browsers  | JavaScript libraries, such as React  |
