# React-Redux

# Actions 
it sends a message to Redux and can contain data; an action is an event that defines something that happened in the application; it has a type field on a JavaScript object.

# Reducers
An event listener that handles events based on the received action; receives the current state and an actionobject; it can update the state if need be ((state, action) => (newState)).

# Store
It is where the Redux application state lives; some planning is required to "design" the store in order to ensure that updates are performed on the smallest set of data, because updates to the store will trigger updates in the UI.

# Dispatch
Allows you to update the state by calling store.dispatch(); it dispatches actions, i.e., they trigger an event.
