# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > let, const, var

02. What is the definition of a function?

    > Functions are subprogram designed to perform specific tasks.

03. What are the `SOLID` principles?

    > Solid is an acronym. It stand for:
     Solid-resposibilty Principle, 
     Open-closed Principle, 
     Liskov Substitution Principle, 
     Interface Segregation Principle,
     Dependency Inversion Principle

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > | fruit.splice(indexOf('pineapple'), 1);

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
    you.friends.push.(them), them.friends.push.(you)

06. Give an example of a JavaScript `Conditional`:

    > an if statement.

07. What is the main difference between `parameters` and `arguments`?

    > Arguments are values passed into functions. Parameters are the name of the values. But the function must be invoked first.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > using devtools as a debugger.

09. What is the difference between a `primitive` value and a `reference` value?

    > | Primitive values are used when you do not want to change the original value but reference values will change the original value when used. 

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100, 1 < 101; 1++>) console.log(i)}
