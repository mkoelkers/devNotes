# Connecting to Redux

- Action
  - Make Action Creator
  - Make Thunk
- Reducer
  - Import action
  - Add to reducer function
- Parent Component
  - Import Action Creator
  - Add Action Creator to Props
  - Add Action Creator to matchDispatchToProps
  - Create Function in Parent Component to call Action Creator
  - Pass Function into Child Component
- Child Component
  - Add function from Parent Component to Props
  - Create function to call Parent Component's function (dispatches the Thunk)