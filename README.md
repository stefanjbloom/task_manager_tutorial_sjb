# README
Define CRUD. Create, Read, Update, Delete. This is the work flow for operating and dynamically updating, managing and maintaining databases.

Define MVC. Model-View-Controller. The back-end creates and maintains the Model. The Model contains the functionality, logic and manages the data. The View is what the user sees(UI) and interacts with(e.g a webpage). The Controller acts as a bridge between the Model and View. Having these three seperate things working together to create an application or page that a user is able to interact with.

What three files would you need to create/modify for a Rails application to respond to a GET request to /tasks, assuming you have a Task model. config/routes.rb, app/controllers/tasks_controller.rb, and the models/task.rb.

What are params? Where do they come from? Params(or parameters) are the values passed to the methods in the tasks_controller.rb file. In web development, they can come from end-uer interations, like filling out a form or entering data that the back-end will then take in and manipulate a result object.

Check out your routes. Why do we need two routes each for creating a new Task and editing an existing Task? Each route serves a purpose to generate a response based on user input. The user input will, behind the scenes, get/post/patch/or delete data based off of methods defined in the tasks_controller file.