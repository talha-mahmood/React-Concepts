->reactDom.createPortal(<h1>hello</h1>document.getElementById('other-root'))
React Portals are a powerful feature in React that allows you to render components outside the current React tree hierarchy. With portals, you can easily render elements into different parts of the DOM, such as modals, tooltips, or any other component that needs to break out of the component's container

->useRef 
used to directly change html which you cannot do otherwise in react
Where to use ref
To use:
Managing focus, text selection, media playback, for animations, third party libraries
Use ref as less as possible as it directly manipulates the dom which is against react principle of virtual dom and it slows down the web
->forward ref: to use ref in child component

->React Pure Component( React.memo replacable in functional comp)
Difference between React Pure component and React component is that React Pure Component uses shouldComponentupdate() life cycle method it checks state value in every render that the updated value is the same as previous value if yes the component does not render again eg if x=10 and after modification x remains 10 component will not updates it increases performance React component does not use shouldComponentupdate() method so if modified value is same as previous value it will still re render

-> Memo:
stops internal component to re render if its parent component state changes but its props value is not changed  

->In react data can also be transfered from child component to parent component

->in react we can also send function in props

->controlled component: component controlled by state eg managing input value by usestate var

->uncontrolled component: component in which changes are made to DOM directly