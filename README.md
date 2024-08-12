[Link to codecademy lesson](https://www.codecademy.com/courses/react-101/lessons/the-state-hook/exercises/review)

The State Hook
Review
6 min
We can now build stateful function components using the useState React Hook!

Let’s review what we learned and practiced in this lesson:

With React, we feed static and dynamic data models to JSX to render a view to the screen.
Hooks are used to “hook into” the internal component state for managing dynamic data in function components.
We employ the State Hook using the code below. The currentState references the current value of the state and initialState initializes the value of the state for the component’s first render.
const [currentState, stateSetter] = useState( initialState );

State setters can be called in event handlers.
We can define simple event handlers inline in our JSX and complex event handlers outside of our JSX.
We use a state setter callback function when our next value depends on our previous value.
We use arrays and objects to organize and manage related data that tend to change together.
Use the spread syntax on collections of dynamic data to copy the previous state into the next state like so: setArrayState((prev) => [ ...prev ]) and setObjectState((prev) => ({ ...prev })).
It’s best practice to have multiple, simpler states instead of having one complex state object.
Instructions
Checkpoint 1 Enabled
1.
Take a look at this task list program from the beginning of this lesson. Read through AppFunction.js again and see how much you can understand!
