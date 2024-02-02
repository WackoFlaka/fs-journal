# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > Var, let, or const are used to delcare a vairable in JavaScript. However each of theses keywords have a different meaning to them.

02. What is the definition of a function?

    > A function is a subprogram designed to perform a particular task. 

03. What are the `SOLID` principles?

    > S - Single responsibility 
    > O - Open / Closed
    > L - Liskov Substitution
    > I - Interface Segreation
    > D - Dependency Inversion

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > let removeElement = fruit.splice(2,1)
    > console.log(fruit)

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

    > you.friends.push('John')
    > them.friends.push('Joaquin')

06. Give an example of a JavaScript `Conditional`:

    > if(JerremyApprovesJournal == true) {
    >       return "good job!"
    >} else {
     > return "How could you"  
    >}

07. What is the main difference between `parameters` and `arguments`?

    > Parameters are used when defining a function, they are the names created in the function definition. Arguments are the valeus the function receives from each parameter when the function is executed.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > Going into your file navigator, to your code editor and the right pane will be a JavaScript Debuggin pane, which allows you to do breakpoints which will pause your code on that line when the function runs.

09. What is the difference between a `primitive` value and a `reference` value?

    > Primitives are strings, Numbers, Booleans, Undefined or Null and reference values are arrays stored in a object.

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for (let i = -100; i < 101; i+=) {
    >   console.log(i)    
   > }
