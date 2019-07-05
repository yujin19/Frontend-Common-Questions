# React 
### 1. What is react?
 React is component-based library for the frontend view layer.
ReactJS is a component-based javascript library which is used for building an interactive and dynamic user interface for websites and mobile applications specifically for developing single page applications where data reflects in real time.

### 2. What are the features of React?
It uses the virtual DOM instead of the real DOM.
It uses server-side rendering.
Server-side rendering (SSR) is a popular technique for rendering a normally client-side only single page app (SPA) on the server and then sending a fully rendered page to the client.
It follows one way data flow or data binding.
One way data flow means that the model is the single source of truth. Changes in the UI trigger messages that signal user intent to the model (or “store” in React). Only the model has the access to change the app’s state. The effect is that data always flows in a single direction, which makes it easier to understand

### 3. What is Virtual DOM?
In React, for every DOM object, there is a corresponding "virtual DOM object." A virtual DOM object is a representation of a DOM object, it creates a virtual copy of the original DOM. It's a one-way data binding hence manipulating the virtual DOM is quick rather than updating original DOM because nothing gets drawn onscreen.
The virtual DOM (VDOM) is a programming concept where an ideal, or “virtual”, representation of a UI is kept in memory and synced with the “real” DOM by a library such as ReactDOM. This process is called reconciliation.
This approach enables the declarative API of React: You tell React what state you want the UI to be in, and it makes sure the DOM matches that state. This abstracts out the attribute manipulation, event handling, and manual DOM updating that you would otherwise have to use to build your app.Virtual DOM usually associates with React elements. React elements are the objects to represent the user interface.
The Document Object Model, or the “DOM”, is an interface to web pages. It is essentially an API to the page, allowing programs to read and manipulate the pages content,structure, and styles
A virtual DOM object is a a lightweight copy of a DOM object. A virtual DOM object has the same properties as a real DOM object, but it can’t directly update HTML.


### 4. What is "React Fiber"?
Fiber is the new reconciliation engine in React 16. Its main goal is to enable incremental rendering of the virtual DOM.
[React Fiber](https://github.com/acdlite/react-fiber-architecture)

### 5. What is Event Handling in React?
React creates its own event system which is fully compatible with W3C object model. All browser’native events are wrapped by instances of Synthetic Event. It provides a cross-browser interface to a native event. That means you do not need to worry about incompatible event names and fields. Besides, React event system is implemented through event delegation and also has a pool of event objects to reduce memory overhead.

### 6. What is Synthetic Event?
SyntheticEvent, a cross-browser wrapper around the browser’s native event. It has the same interface as the browser’s native event, including stopPropagation() and preventDefault(), except the events work identically across all browsers.

### 7. Explaination of JSX
JSX can best be thought of as a markup syntax that very closely resembles HTML.It is more or less like the combination of Javascript + XML. JSX makes writing React components, the building blocks of React UI, easier by making the syntax developers use for generating these strings of HTML almost identical to the HTML they will inject into the web page.JSX is one of best ReactJS features. Web developers will always go for an easy way out, which is why this is a great choice for many.

### 8. Why say React is component based?
In React everything is component the web page divided into small components to create a view(or UIs). Every part of applications visuals would be wrapped inside a self-contained module known as a component. Since component logic is written in JavaScript instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.Components in ReactJS use to define the visuals and interactions in applications.



