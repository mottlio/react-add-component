#REACT

##Creating a REACT component

- need to add React, React DOM and React DOM Factories to index.html
```
class Pet extends React.Component {
    render () {
        //return some html we'll put in the DOM (using React factory)

        const h2 = ReactDOMFactories.h2(null, "Moxie"); //(optional attributes, content)
    }
}

```

In REACT all components must be put in SEPARATE DOM elements