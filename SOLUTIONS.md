### Rails MVC

First, start the rails server. Then, make a request to `/tasks/new`, fill out the form and submit it in order to create a new task.

1. Which controller and action handles the data from the form submission? TaskController
2. What controller and action would be used if you did a `GET` request on the `/users` route? UserController -- index
3. Write out the step-by-step process that your rails application will take to render the `tasks/new` route.

    The browser issues a request for the /tasks URL.
    Rails routes /task to the index action in the Tasks controller.
    The create action asks the Task model to create a new task
    The view uses embedded Ruby (.erb) to render the page as HTML.
    The controller passes the HTML back to the browser.

4. What file is responsible for managing the mapping between your application and the `tasks` database table?

### Rails RESTful Actions

5. Explain all 7 of the RESTful actions in Rails

   - List each action by its name
   - Explain which HTTP verbs pair with each action
   - Write a short sentence for each action that summarizes what it does
    index, show, new, and edit. So, create, update, and destroy