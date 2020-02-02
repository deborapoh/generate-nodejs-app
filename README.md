# Generate NodeJS app

Type in your terminal `npx generate-nodejs-app` and see the magic happens!

## About

This is a tool inspired on `create-react-app` to generate a basic structure 
of a NodeJS app using the most commonly used tools when creating JS APIs.

When running this tool you will have a new NodeJS API with a basic app 
to manage a todo list. All the boilerplate is going to be automatically 
generated for you.

Your new application will include the following items:

- Express (already with body-parser, cors and other configs already set)
- Mongoose (to communicate with MongoDB)
- Jest/Supertest (with some passing tests to help you create your owns)
- Linting with Standard JS

## Todo app

The todo app generated by `generate-nodejs-app` will have the folder structure 
already defined, including 4 endpoints with passing tests so you do not have 
to think about how your app will be structured, leaving you free to spend 
time on what matters, your application. 

The 4 endpoints are the following:

- `GET http://localhost:3000` 
- `POST http://localhost:3000` 
- `PUT http://localhost:3000/todo-item-id` 
- `DELETE http://localhost:3000/todo-item-id` 

The POST and PUT accept the following JSON:

``` json
{
  "task": "Study NodeJS"
}
```

This is just a simple app to get you started, feel free to delete and do 
whatever you want with it!

## Comparing with create-react-app

This is not intended to work the way `create-reat-app` does, it is more like
the "ejected" version of the React one, after running this tool and creating 
your app you will have to manage it the same way you would if you created 
it by yourself, updating the dependencies and all that stuff. 

## Wishlist

- Generate with README.md file
- Organize CLI code 
- Test the CLI itself
- Check for the dependencies to run the app (Mongo...)
- Coverage report for the generated app
- More options when generating the app (without the todo app...)

## Info

This tool was created by Cobasi Labs. We hope you find it useful and inspires 
you to create new apps, and we would be glad if you contribute with some 
improvements as well!
