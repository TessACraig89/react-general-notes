### Initial Setup
```
$ npm i -g create-react-app
$ create-react-app react-sample-app
$ cd react-sample-app
$ atom .
```

### Run the server:
```
$ npm run start
```

### Props

- Every component has .props

- Properties are immutable. That is, they cannot be changed while your program is running.

- We define properties in development and pass them in as attributes to the JSX element in our .render method.

### State

- mutable attributes

- Like properties, we can access state values, val for example, using this.state.val

- Setting up and modifying state is not as straightforward as properties. It involves explicitly declaring the mutation, and then defining methods to define how to update our state....
