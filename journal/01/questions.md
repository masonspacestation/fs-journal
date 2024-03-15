# Foundations of Web Development
01. In your own words, why do we use Git?
    > Git provides offsite file backup, version control, and is important when working in a team so that everyone has access to the same code.
    One of the most interesting purposes that I didn't know about is for different projects needing to access the same codebase.

02. In the terminal, what is the command `mkdir` used for?
    > mkdir means "make directory", and it creates a new folder within your current location.

03. What is a ***pseudo-class*** and what are some of the most common ones you think you will use?
    > Pseudo classes specify a state of a targeted selector to apply special styling for that circumstance.
    A few that I can see using often would be :hover, :checked, :valid, :invalid, :visited, :is(), :not()

04. What is ***specificity*** and how might you use it to your benefit?
    > Specificity refers to how you target an element through CSS. By understanding the "points" assigned for different selector types, we can make sure that the right styles are applied. It can benefit by allowing us to create more variety while maintaining fewer classes and ids.
    

05. What problems do you think you could run into if you over-utilized the `!important` feature?
    > I could imagine that over-using "!important" could create confusion if something isn't behaving as expected. Since it's not a common feature to use, we might not think to look for it when troubleshooting.
    With it's power to override any true specificity, it could definitely lead to unexpected results. If it was used in more than one selector on the same element, only one of them would actually work.
    Overall, it seems sloppy and lazy, and it would be better to write the code to accomplish the desired goal.

06. What are the three components that makeup a `CSS` rule? <br> Example:

    ```css
        h1 {
            color: rgba(255, 210, 33, .75);
        }
    ```

    > The three components of a CSS rule are: selector, property, and value.
    The selector targets the element to be styled, the property identifies what effect we want to make, and value of the property defines the change.
    ```css
    selector {
        property: value;
    }
    ```

07. How do you think good design influences people when visiting a website, and what sorts of things could you convey through design alone?
    > | ANSWER HERE |

08. What is the purpose of ***wireframing***?
    > Wireframes are beneficial because we can quickly (and inexpensively) see how the ideas will work together on a page. We can compare and choose from different directions before moving forward. It's very easy to change things around at this phase vs after pages or a product have been built.

09. Do you think wireframes are worth the time, energy, and effort that they require? Why or Why not?
    > I believe they're worth it. There are very few exploits that end better when we start without a plan. Wireframes are that plan, and having them can save us a lot of time and expense before project handoff.

10. Define the display `:flex property:`
    > | ANSWER HERE |

11. What `CSS` properties affect the size of a box model?
    > height and width
