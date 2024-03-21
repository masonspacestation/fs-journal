# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > var, let, or const, but let is preferred these days over let, and for more general use than const.

    var:
    global or function-scoped
    can be updated and redeclared within scope
    
    let:
    block-scoped
    can be updated, but not redeclared
    
    const: 
    cannot be redeclared or updated, but properties can be updated
    initialized at declaration—the others can be initialized and declared separately

02. What is the definition of a function?

    > A function is a subprogram designed to perform a particular task.<br>
<i>    It is executed when called (or invoked) from elsewhere in the script, or from the HTML. Values can be included when passed and within the function.</i>

03. What are the `SOLID` principles?

    > | ANSWER HERE |

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice(2, 1)

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

    > | ANSWER HERE |

06. Give an example of a JavaScript `Conditional`:

    > | ANSWER HERE |

07. What is the main difference between `parameters` and `arguments`?

    > Arguments are values that are passed INTO the function as a Parameter.
    Arguments are the values the function receives to work with. Parameters are names, or aliases, for that argument that are used to define the function.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > Use the debugger in the browser

09. What is the difference between a `primitive` value and a `reference` value?

    > | ANSWER HERE |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > | ANSWER HERE |
