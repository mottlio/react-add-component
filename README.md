# REACT

## Creating a REACT component

- need to add React, React DOM and React DOM Factories to index.html
```
class Pet extends React.Component {
    render () {
        //return some html we'll put in the DOM (using React factory)

        const h2 = ReactDOMFactories.h2(null, "Moxie"); //(optional attributes, content)
    }
}

```

In REACT all components must be put in SEPARATE DOM elements.

Every REACT component will need a CLASS.

Every component extends from React.Component.

Goal of component: be included in the DOM.

A component may consist of several html elements (like h2 and img).

We use ReactDOM.render() to render components in the DOM.

## Including a React Component in the DOM:

```
ReactDOM.render(React.createElement(Pet), document.getElementById("app"))
```
We have an existing div with id "app" and that is where we place a newly created element "pet".