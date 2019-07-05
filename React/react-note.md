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

### 4. What is "React Fiber"?
Fiber is the new reconciliation engine in React 16. Its main goal is to enable incremental rendering of the virtual DOM.
[React Fiber](https://github.com/acdlite/react-fiber-architecture)
