# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?

Stateful components manipulate and/or control some state in the application,
whereas funcional components are more basic, and mostly just render DOM elements.

2. When does a componentWillMount function get called? What about a componentWillUpdate?

After the constructor function fires, but before the render method does

3. Define stateful logic.

Stateful logic is a function/method built into a component. A components stateful
logic can be something like an onClick handler or a React hook

4. What are the three step of creating a successful test? What is done in each phase?

- Arrange - Where you tell the test the component it will be testing on
- Act - Where you elements in the component that you will use in the test
- Assert - Where you define the logic that the test will run and what to expect
  from it.
