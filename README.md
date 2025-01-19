Objective: ContextAPI allows us to maintain a global state for our applications that can be used across multiple components without prop drilling. For our application, we have a Header component, which is completely different from our CounterApp component (mapped to the route /counter-app). We want to achieve a feature such that when a button is clicked in one component, the effect can reflect in another component. E.g: Our counter will reflect in both Header and CounterApp Components.

Instructions:

    Duplicate this project alx-project-0x04 with a new name of alx-project-0x05.
    Create a new directory context/ in the project root directory
    Create an empty file CountContext.tsx under the context/ directory
    Replace the content of the CountContext.tsx with the following