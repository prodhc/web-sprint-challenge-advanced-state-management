# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

A. Context API fixed sharing state down a component tree in react.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

A. Actions in redux carry a payload of information from your application to update store. Reducers take the current state, and an action that has been fire to excute the new state. The store in redux is a single immutable object tree, which is also a state container holding the applications state. Since there is only a single store holding all states its refered to as a 'single source of truth'.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

A. Thunk let's us call action creators that return a function instead of an action object

4. What is your favorite state management system you've learned and this sprint? Please explain why!

A. API CONTEXT!!! Redux takes so much work, with little pay off in small projects and applications. It doesn't make sense to use it at the scale when there's context API. But I understand the importance of Redux and what it can do.