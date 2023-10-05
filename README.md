# Redux Demo

## Three Core Principles

### First Principle

The global state of your application is stored as an object inside a single store.

### Second Principle

The only way to change the state is to dispatch an action, an object that describes what happened

### Third Principle

To specify how the state tree is updated based on actions, you write pure reducers

## Middleware

Is the suggested way to extend Redux with custom functionality

Provides a third-party extension point between dispatching an action, and the moment it reaches the reducer

Use middleware for logging, crash reporting, performing asynchronous tasks etc
