#Connecting to Redux

1. Action
  - Make Action Creator
  - Make Thunk
2. Reducer
  - Import Thunk
  - Add to reducer function
3. Parent Component
  - Import Action Creator
  - Add Action Creator to Props
  - Add Action Creator to matchDispatchToProps
  - Create Function in Parent Component
  - Pass Function into Child Component
4. Child Component
  - Add function from Parent Component to Props
  - Create function to call Parent Component's function (dispatches the Thunk)