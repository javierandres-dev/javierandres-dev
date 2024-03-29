# :memo: Notes
## REACTJS
---
### Resources
- [React](https://reactjs.org/)
- [DOM Elements](https://reactjs.org/docs/dom-elements.html)
- [ViteJS](https://vitejs.dev/)
- [Create React App](https://create-react-app.dev/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [styled-components](https://styled-components.com/)
- [MATERIAL-UI](https://material-ui.com/)
* Extension
  - react developer tools
* Package
  - create react app
  - serve
  - prop-types
### Requirements
- Nodejs
### Setup
#### Vite
```
$ npm create vite@latest my-app --template react
```
#### Vite & TypeScript
```
$ npm create vite@latest my-app --template react-ts
```
#### Deploy to a Github pages a React App (Vite)
Install gh-pages
```
$ npm install --save-dev gh-pages
```
Set package.json
```
"homepage": "https://<user>.github.io/<repo>"
"scripts": {
  "predeploy": "npm run build ",
  "deploy": "gh-pages -d dist"
}
```
Set vite.config.js
```
base: "/<repo>"
```
Run
```
$ npm run predeploy
$ npm run deploy
```
#### CRA
```
$ npx create-react-app <name>
$ cd <name>
$ npm start
```
#### CRA & TypeScript
```
$ npx create-react-app my-app --template typescript
$ npm install --save @types/react
```
#### Deploy to a Github pages a React App (CRA)
Install gh-pages
```
$ npm install --save-dev gh-pages
```
Set package.json
```
"homepage": "https://<user>.github.io/<repo>"
"scripts": {
  "predeploy": "npm run build ",
  "deploy": "gh-pages -d build"
}
```
Run
```
$ npm run predeploy
$ npm run deploy
```
### Terms and concepts
1. What is it
2. What does it do
3. Why to use it
4. Getting started
5. Concepts
6. Code samples
7. Documentation
* React
  - JavaScript library
  - based on components
  - UI
  - client side
  - declarative
  - reactive
  - virtual DOM
  * Unidirectional flow
    - parent to child
  * events
    - nativeEvent
    - SyntheticEvents
  * Syntax
    * jsx (sugar sintactic)

- Structure by default

* Components
  * Parts
    - Content (html)
    - Presentation (css)
    - Interactivity (js)
  * Export
    - Named
    - By default
  * With state or without state
  * Unidirectional, One-way Data Binding
    - Parent to child flow
  * Allow define as class and as function
    - of class
    - functional
  * Communication between components
    - Parent to child (props)
    - Child to parent (event of the son altering the state of the father)
    - Unrelated components

* Lifecycle
  * Mounting
    - always
    - one time
    - set initial state
    - get props
    - first render
    * Methods
      - Constructor
      - componentWillMount
      - render
      - componentDidMount
  * Updating
    - when exists new props
    - when change the state
    - setState
    * Methods
      - componentWillReceiveProps
      - shouldComponentUpdate
      - componentWillUpdate
      - render
      - componentDidUpdate
  * Unmounting
    - one time
    - delete listeners
    - delete DOM references
    * Methods
      - componentWillUnmount
* Error cycle
  * Method
    - componentDidCatch

* Components
  * render
    - props
    - state
  - fragment
  - reactivity

* More components
  - pureComponent

* Properties ― props (inmutable), it's a object
  - Default Props
  - Props like attribute
  - Prop Types
  - key

* State
  - Inmutable
  - Declarative
  - Reactive
  - Asynchronous
  - A functional component can't have state

* Props
  - Children

* Methods
  - setState (asynchronous)

* Events on class components
  - bind
  - Property Initializers
  - arrow function to bind

* Events
  - Native
  - Synthetics
  - Custom

* Events
  - onClick
  - onSubmit
  - onChange
  - onInput
  - onInvalid

* Hooks
  * useState
    - Default props
  * useEffect
    - Render
    * Dependencies list
      * Exists empty
        - componentDidMount, render content only one time
      * Exist with specifit value
        - componentDidUpdate, render content when specific value change, state variable
      * Non-existent
        - componentDidUpdate, render content when any change (discouraged)
    * Return
      - componentWillUnmount
  - useContext
  - useRef
  - useReducer
  - useCallback
  - useMemo
  * custom hooks
    - use<hook_name>

* Refs
  * Class component
    - createRef
  * Functional component
    - useRef

* Forms
  - Controlled input element

* Good practices
  - composition instead of inheritance
  - stateless components
  - pattern: container / content

* parts
  - index
  - app
---
## Software Developer
Built by [javi](https://github.com/javierandres-dev/) :copyright: 2020 - 2023
Found a bug or have an idea? [Contact me](https://www.linkedin.com/in/javierandres-dev/).
