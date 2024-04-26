# Managing the Fullstack Application

1. Describe the two ways to bind Data in Vue?

  > v-bind and v-model are the two main ways I know to bind data. v-bind is a one-way binding, meaning that the rendered element is getting it's information from elsewhere, like the database or AppState.
  v-model is an example of two-way binding, meaning that either of the two instances can modify each other. 

2. The `SPA` acronym stands for what?

  > Single Page Application

3. What are some of the advantages/uses of a `SPA` over a traditional one?

  > A SPA will feel quicker to use, since data renders directly to the current page, instead of navigating to different pages for everything.
  Since (mostly) everything is on a single page, the site is more efficient to build and maintain.

4. What does the `onMounted` method in Vue do?

  > It activates the function nested inside it once the necessary responses come back from the api.

5. What is the `v-model` attribute in Vue for, and when might you use it?

  > v-model creates two-way binding between components and data models. It's very useful for structuring data input to a form.

6. What is the package.json file used for?

  > The package.json file holds all kinds of metadata about your application. It is used by npm for many tasks, and must be in place in order to use npm with your application.

7. Which Vue attributes(directives) could you use to conditionally render elements on a page?

  > v-if, v-else, v-else-if

8. What is the purpose of the `key` attribute when using `v-for` on an element?

  > The key tells the v-for directive how to distinguish target objects from each other. For example, if we are wanting to display names of each person attending an event, we could use the profile.id to build that collection of unique profiles.

9. What is the `<slot>` element and what is it used for?

  > The slot element is a reusable wrapper component that can house fragments of text from a parent element. We've used it for a modal that can have anything in it. It could also be used for a particular button style or any other container that you don't want to remake each time it's slightly modified. That's one of the great things about Vue.
