
Why can’t browsers read JSX?
because browser read only javasctipt objects but jsx is a es6 so it cant 
understand thats why we use babel that is a transcompiler which converts advance js to pure js

What do you understand by Virtual DOM? Explain its working
 Virtual dom is the light weight copy of real dom
 Virtual dom Have two Copies one virtual is present in the mounting phase and another virtual dom contains updated state values.
 This two virtual doms will compare each other this method is called "DIFF ALOGORITHM"
 After this The Updates will be done in Real Dom this method is called "RECOINCILIATION"

What is the purpose of render() in React.
in react 2 types of components are present functional and class.
in functional componemt the whole component itself responsible for mounting phase 
but in class render only responsible for mounting
Differentiate between states and props.
states and props are used for data flow
states are smart components because state get updated dynamically
but props are dumb they are only static
in state data pass in that component only, but props data flow through parents

How can you update the state of a component?
we can update the state of a cmponent using setState method in class component comming to functional component 
we use the hook useState() to modify the component.

Explain the lifecycle methods of React components in detail.
in react 3 methods are there they are mounting,updating,unmounting.
mounting:when an instance that dom get created first time 
in this 4 methods are there 
constructor
static getDerivedStateFromProps
render
componentdidmount
updating:when user trigger any action the componenet will re-render this is updating phase 
in this 5 methods are there 
static getDerivedStateFromProps
shouldComponentUpdate
Render
getSnapshotBeforeUpdate
componentdidupdate
unmounting:when component will remove from dom 
in this only one method,
componentwillunmount 