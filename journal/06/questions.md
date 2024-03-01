# Single Page Applications with Vue
01. What is the entrypoint of an application?

  > | ANSWER HERE |

02. What is the difference between a vue `component` and `page`?

  > A component is like a small piece of the user interface that grabs its own api, has their own structures and own methods. While a vue page is where the user wants to visit or what will the user view on the page. 

03. What is ***Component-Based Architecture***?

  > A method for encapsulating individual pieces of a large user interface into self-sustaining, independent micro-systems.

04. What are the three tags that make up a Vue component?

  > HTML, CSS, and JavaScript (template, script, style)

05. What are ***lifecycle hooks***? What are lifecycle hooks used for?

  > Lifecycle hooks are a window into how the library you're using works behind-the-scenes. Lifecycle hooks allow you to know when your component is created.

06. Which component in Vue does the vue-router use to mount pages onto?

  > router-link

07. What is the difference between the `AppState` and the state object within a component?

  > The appstate data can be used everywhere in your code or to be called. While the state object is local in a specific file to be called for that data. 

08. What is the responsibility of `Services` in our Vue projects?

  > To grab data from the API or break down data to return to our user

09. What are ***props*** and how are they used? Provide an example

  > Props are how we pass variables and other information around between different components. 
  > props: {
  >   blog: { type: Blog, required: true}
  > }

10. What is the Vue method used to create watchable objects such as `state` or `AppState`?

  > The Watchers Method
