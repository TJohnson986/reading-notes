## Class 38 Reading Notes
[Home](https://tjohnson986.github.io/reading-notes/)

#### Table of Contents

## Redux - Asynchronous Actions

Redux by itself doesn't know anything about async logic, but rather only knows how to synchronously dispatch actions and update state. Custom middleware is required to enable async logic in Redux.

The official middleware for Redux is called Thunk. It allows functions to be written with dispatch and getState as arguments. It calls action creators that return a function instead of an action object to be used to dispatch the regular sync actions once the async operations have completed.