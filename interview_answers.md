# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

We use the Context API when we have global data that lots of components share (things like user or theme), or when we have to pass data through intermediate components. The API can help keep your state relatively clean.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions in Redux are packets of information that contain an action type and associated data.
When an action is dispatched, it flows through every reducer in a script. Redux was built on this fundamental principle, among others.Reducers are pure functions, meaning they don't produce any side-effects. A reducer follows the key principles that come from the Array.reduce() function, in that they behave similarly to the callback that you would pass to reduce.
Everything that changes within your application is represented
by a single JavaScript Object known as the store. The store
contains our state for our application.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

Redux Thunk is a separate node package called redux-thunk.Redux Thunk to make the flow asynchronous and make API calls from our action creators.We are changing up the action creators to perform asynchronous API calls.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

I feel like context Api is far easier once i learned how to use it with useReducer.