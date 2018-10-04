# Connecting to Redux

- Action
  - Make Action Creator
  - Make Thunk
- Reducer
  - Import Thunk
  - Add to reducer function
- Parent Component
  - Import Action Creator
  - Add Action Creator to Props
  - Add Action Creator to matchDispatchToProps
  - Create Function in Parent Component
  - Pass Function into Child Component
- Child Component
  - Add function from Parent Component to Props
  - Create function to call Parent Component's function (dispatches the Thunk)