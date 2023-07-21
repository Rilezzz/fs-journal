# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > The entry point of an application is index.html

02. What is the difference between a vue `component` and `page`?

  > A page is what is directly shown on vue while a component is a class of code injected into the page for use.

03. What is ***Component-Based Architecture***?

  > Splitting different pieces of UI into seperate and reusable pieces of code.

04. What are the three tags that make up a Vue component?

  > Template, Script, Style

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifecycle hooks are function called upon at certain parts of a components "lifecycle"

06. Which component in Vue does the vue-router use to mount pages onto?

  > Router-view Component

07. What is the difference between the `AppState` and the state object within a component?

  > The AppState is the most "senior" state which is used for the entire application while the "state" refers to just the component and what that specific component needs.

08. What is the responsibility of `Services` in our Vue projects?

  > Services are utilized to update the AppState.

09. What are ***props*** and how are they used? Provide an example

  > Props are similar to components in the way that they are small pieces of code passed down to be used in other points of code.

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > Reactive()
