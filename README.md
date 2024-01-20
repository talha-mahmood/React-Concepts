
**React Information**

**React Portals**

- **reactDom.createPortal('<h1>hello</h1>', document.getElementById('other-root'))**
- React Portals are a powerful feature in React that allows you to render components outside the current React tree hierarchy.
- With portals, you can easily render elements into different parts of the DOM, such as modals, tooltips, or any other component that needs to break out of the component's container.

**useRef**

- Used to directly change HTML, which you cannot do otherwise in React.
- **Where to use ref:**
  - Managing focus, text selection, media playback, for animations, third-party libraries.
- **Use with caution:**
  - Use **ref** as little as possible as it directly manipulates the DOM, which goes against the React principle of virtual DOM and may slow down the web.

**Forward Ref**

- Used to pass and use refs in child components.

**React Pure Component (React.memo replaceable in functional components)**

- Difference between React Pure Component and React Component is that React Pure Component uses **shouldComponentUpdate()** lifecycle method.
- It checks if the state value in every render is the same as the previous value.
- If yes, the component does not re-render, improving performance.
- React Component does not use **shouldComponentUpdate()** method, so it re-renders even if the modified value is the same as the previous value.

**Memo**

- Stops internal components from re-rendering if their parent component's state changes but their props value remains unchanged.

**Data Transfer in React**

- In React, data can also be transferred from child components to parent components.

**Function Passing in Props**

- In React, functions can also be sent as props.

**Controlled Component**

- Component controlled by state, managing input value using **useState** variable.

**Uncontrolled Component**

- Component in which changes are made to the DOM directly.

![User](Aspose.Words.aa4abcea-7c5e-4121-b7b4-b2f03c39970a.001.jpeg)

**You**

write in readme.md format

ChatGPT

**ChatGPT**

**React Information**

**React Portals**

jsxCopy code

reactDom.createPortal(<h1>hello</h1>, document.getElementById('other-root')) 

React Portals are a powerful feature in React that allows you to render components outside the current React tree hierarchy. With portals, you can easily render elements into different parts of the DOM, such as modals, tooltips, or any other component that needs to break out of the component's container.

**useRef**

- Used to directly change HTML, which you cannot do otherwise in React.
- **Where to use ref:**
  - Managing focus, text selection, media playback, for animations, third-party libraries.
- **Use with caution:**
  - Use **ref** as little as possible as it directly manipulates the DOM, which goes against the React principle of virtual DOM and may slow down the web.

**Forward Ref**

- Used to pass and use refs in child components.

**React Pure Component (React.memo replaceable in functional components)**

- Difference between React Pure Component and React Component is that React Pure Component uses **shouldComponentUpdate()** lifecycle method.
- It checks if the state value in every render is the same as the previous value.
- If yes, the component does not re-render, improving performance.
- React Component does not use **shouldComponentUpdate()** method, so it re-renders even if the modified value is the same as the previous value.

**Memo**

- Stops internal components from re-rendering if their parent component's state changes but their props value remains unchanged.

**Data Transfer in React**

- In React, data can also be transferred from child components to parent components.

**Function Passing in Props**

- In React, functions can also be sent as props.

**Controlled Component**

- Component controlled by state, managing input value using **useState** variable.

**Uncontrolled Component**

- Component in which changes are made to the DOM directly.

